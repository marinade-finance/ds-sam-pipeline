# DS SAM pipeline
Automated pipeline to run auctions and apply the results regularly

## Blacklist
The auction lists validators by the `blacklistRules` thresholds in `auction-config.json`, on top of the list
the validators API serves at `/blacklist`. Each run writes its new listings to `outputs/blacklist-added.csv`,
and the validators API imports them once the run is merged. When more accounts are new than
`maxNewListings`, the run lists none of them and names them in its summary: approve them as `manual`
entries of the blacklist config in ops-infra, and unlist an account there with an `exempt` entry.

## Reproducing an auction run
1. Get all the files from the directory `auctions/{epoch}.{slot}/inputs` in this repo and store them in a local directory (`{INPUTS_DIR}`)
2. Checkout the [ds-sam](https://github.com/marinade-finance/ds-sam) repo locally and work in its root directory
3. Prepare an empty local directory for storing the outputs (`{OUTPUTS_DIR}`)
4. Run `pnpm install` to install dependencies
5. Run `pnpm -r build` to build the package
6. Run `pnpm run cli -- auction -c {INPUTS_DIR}/config.json --inputs-source FILES --cache-dir-path {INPUTS_DIR} -o {OUTPUTS_DIR}` to evaluate the auction
7. Get the results of the auction from `{OUTPUTS_DIR}`
