# DS SAM pipeline
Automated pipeline to run auctions and apply the results regularly

## Blacklist
The auction lists validators by the `blacklistRules` thresholds in `auction-config.json`, on top of the list
the validators API serves at `/blacklist`. Each rule is judged on the window ending at the last closed epoch
and on the one ending an epoch earlier, so an epoch whose data arrived late is still judged, one auction later.
Each run writes its new listings to `outputs/blacklist-added.csv`, and the validators API imports them once
the run is merged. When more accounts are new than `maxNewListings`, the run adds none of its hits and holds
them in its summary and in `outputs/blacklist-held.csv`, which nothing imports: approve them as `manual`
entries of the blacklist config in ops-infra. `maxNewListings` `0` holds every hit as a dry run, not for approval.
An account leaves the list only through an `exempt` entry without `until_epoch` there; with just its `manual`
line removed it stays listed and the summary flags it as Kept.

## Reproducing an auction run
1. Get all the files from the directory `auctions/{epoch}.{slot}/inputs` in this repo and store them in a local directory (`{INPUTS_DIR}`)
2. Checkout the [ds-sam](https://github.com/marinade-finance/ds-sam) repo locally and work in its root directory
3. Prepare an empty local directory for storing the outputs (`{OUTPUTS_DIR}`)
4. Run `pnpm install` to install dependencies
5. Run `pnpm -r build` to build the package
6. Run `pnpm run cli -- auction -c {INPUTS_DIR}/config.json --inputs-source FILES --cache-dir-path {INPUTS_DIR} -o {OUTPUTS_DIR}` to evaluate the auction
7. Get the results of the auction from `{OUTPUTS_DIR}`
