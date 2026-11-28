## Auction summary

### Stake amounts
- Total network stake = `423,902,789.606` SOL
- Total Marinade stake = `4,802,808.725` SOL
  - SAM stake = `4,802,808.725` SOL
  - Unallocated SAM stake (no auction target) = `0` SOL

### Results stats
- Auction winning rev share = `0.17846053364343453` PMPE
- Eligible validators count = `93`
- Staked validators count = `34`

### VAT
- VAT-ineligible validators = `4`
- VAT is the only gate, with Marinade stake = `0`
- No chain VAT verdict, not cut = `0`

<details><summary>VAT-ineligible validators</summary>

- `6XPxXV2VZMNqSquPUF3bjnGt5u8R884A9UVYS6jv8g5f` uptime (also: vatIneligible, noBond): `low_balance`, Marinade stake `35,463.5727` SOL, bond `0` SOL
- `3Z1N2Fkfha4ThNiRwN8RnU6U8dkFJ92DH2TFyLWJf8cj` uptime (also: vatIneligible, noBond): `low_balance`, Marinade stake `0` SOL, bond `0` SOL
- `DqbRPQXbN8GDKWZkKiHnRjiSKPqE3rQaNgTPxdLGPDMK` uptime (also: vatIneligible, noBond): `low_balance`, Marinade stake `0` SOL, bond none
- `sShosKd6uA5c1ZpVMxdsE6do13TLRWSMYsXbSMmNC77` vatIneligible: `low_balance`, Marinade stake `0` SOL, bond `1.0041` SOL

</details>

<details><summary>ⓘ How it works</summary>

A validator is cut only when the chain refused it at the last epoch boundary (`vat_admitted` false) and it still fails VAT in the running epoch. Without a chain verdict it is not cut. ⚠ marks a validator with a bond and Marinade stake whose only failing gate is VAT; the bid floor is not checked for it.

</details>

### Blacklist
- Evaluated windows ending at epochs `1098`, `1097`
- Added = `0`
- Held = `34`: dry run (`blacklistRules.maxNewListings` is 0), would-be listings, not for approval. `1` from the window ending at epoch `1097`, reported by the previous auction unless its data was late. `33` new accounts, `1` already blacklisted.

<details><summary>Held hits</summary>

  - `2Bgb4T6Zdy9iy2S3xxDRpwdgQHpitoDnZt5aBnCwv3Ez` SLOW_SLOTS_1098: epoch 1097 245ms vs network 200ms; epoch 1098 244ms vs network 200ms
  - `2WUCao1mdk4e7KbXUga6hQr2D9piZ1SFYK4KQt8Mdvzv` SLOW_SLOTS_1098: epoch 1097 280ms vs network 200ms; epoch 1098 280ms vs network 200ms
  - `2hK2uke7ssm7QuBzbrgxBs2aStmFmdKyC12yV2iwvvPm` SLOW_SLOTS_1098: epoch 1097 254ms vs network 200ms; epoch 1098 254ms vs network 200ms
  - `2iWXwF2Q5W6o7yntV2mkbxncB4rYHnX61y3NU8a8EFMJ` SLOW_SLOTS_1098: epoch 1097 290ms vs network 200ms; epoch 1098 290ms vs network 200ms
  - `3JD3jMmnR6g88qff2WZ3cMHJRjJMUk9yVZtmYTYeFrXf` SLOW_SLOTS_1098: epoch 1097 254ms vs network 200ms; epoch 1098 254ms vs network 200ms
  - `3hhEWRNAVzqRjmF9hW5nYkrmDMxKKzGziE11Sg7yk3iX` SLOW_SLOTS_1098: epoch 1097 240ms vs network 200ms; epoch 1098 240ms vs network 200ms
  - `4AUED4uj6nSTuANzaAUnGBPJQRmhpDYDwoWJNkoUUBBW` SLOW_SLOTS_1098: epoch 1097 289ms vs network 200ms; epoch 1098 290ms vs network 200ms
  - `4jEHuQZTNTRYAhxRYEjV3HJ1b4wqdQjnBRdPzFWzkCft` SLOW_SLOTS_1098: epoch 1097 240ms vs network 200ms; epoch 1098 240ms vs network 200ms
  - `4tuMshQNpAFpy1YtEHnSsE5EPN1mAT8FevWvn2UPJHNM` SLOW_SLOTS_1098: epoch 1097 240ms vs network 200ms; epoch 1098 240ms vs network 200ms
  - `5DnWqsJceNamPNNUpMnVr1XQ8anSxcj9TXRD5Rn52prJ` SLOW_SLOTS_1098: epoch 1097 280ms vs network 200ms; epoch 1098 280ms vs network 200ms
  - `5iZ5PQPy5Z9XDnkfoWPi6nvUgtxWnRFwZ36WaftPuaVM` SLOW_SLOTS_1098: epoch 1097 236ms vs network 200ms; epoch 1098 236ms vs network 200ms
  - `6SF5cmEXFFEmnFd5BwM4J6NkZhh3WfPkgmqdoAGjLLPX` SLOW_SLOTS_1098: epoch 1097 240ms vs network 200ms; epoch 1098 240ms vs network 200ms
  - `6XtfZoG7P9Hjmecg4Da8pqd9A4TzU4QynbwY94Z1ZLcy` SLOW_SLOTS_1098: epoch 1097 253ms vs network 200ms; epoch 1098 253ms vs network 200ms
  - `7qTwituXJJ5dtUwBZXjMNgtAyXJbx3X8V4B9gXFRjK9d` SLOW_SLOTS_1098: epoch 1097 245ms vs network 200ms; epoch 1098 245ms vs network 200ms
  - `ANCVpxEySGWWLqqkVKw2xWYDE9UP4fmZWMCBr5t96jch` SLOW_SLOTS_1098: epoch 1097 240ms vs network 200ms; epoch 1098 240ms vs network 200ms
  - `AXVwnsmMiaXvwKN9TfRF6eo2JgwrdKf9N9QGyYxYp3Qb` SLOW_SLOTS_1098: epoch 1097 250ms vs network 200ms; epoch 1098 250ms vs network 200ms
  - `CvSb7wdQAFpHuSpTYTJnX5SYH4hCfQ9VuGnqrKaKwycB` SLOW_SLOTS_1098: epoch 1097 287ms vs network 200ms; epoch 1098 287ms vs network 200ms
  - `DdCNGDpP7qMgoAy6paFzhhak2EeyCZcgjH7ak5u5v28m` SLOW_SLOTS_1098: epoch 1097 275ms vs network 200ms; epoch 1098 275ms vs network 200ms
  - `DierScgiTrz5AM7mddeJLHYNvafym3XhjjdM51AnKevU` SLOW_SLOTS_1098: epoch 1097 238ms vs network 200ms; epoch 1098 238ms vs network 200ms
  - `FKsC411dik9ktS6xPADxs4Fk2SCENvAiuccQHLAPndvk` SLOW_SLOTS_1098: epoch 1097 245ms vs network 200ms; epoch 1098 245ms vs network 200ms
  - `FiijvR2ibXEHaFqB127CxrL3vSj19K2Kx1jf2RbK4BWS` SLOW_SLOTS_1098: epoch 1097 260ms vs network 200ms; epoch 1098 260ms vs network 200ms
  - `G83jy4NB16A4mchfRjZvfH8SPH2TxwjSZYxh5fzg2Qys` SLOW_SLOTS_1098: epoch 1097 230ms vs network 200ms; epoch 1098 230ms vs network 200ms
  - `GMeW3doRSeroW6e7gEMLb2Ne8MfmeLzKSBs4XcWtkdBP` SLOW_SLOTS_1098: epoch 1097 253ms vs network 200ms; epoch 1098 253ms vs network 200ms
  - `Gmmjsfpr1cj66zqwaYzEiSPsA1Y438MKXVNPnGZ2zB9Q` SLOW_SLOTS_1098: epoch 1097 254ms vs network 200ms; epoch 1098 254ms vs network 200ms
  - `HCvnhbT3Sn5RsueDisWzzn5FkW8tAqoQK1dr7cvAVzin` SLOW_SLOTS_1098: epoch 1097 275ms vs network 200ms; epoch 1098 275ms vs network 200ms
  - `HMV14UAuULSwqmZhsKHzaVkYAd94iWpEeURgbUegfQLc` SLOW_SLOTS_1098: epoch 1097 240ms vs network 200ms; epoch 1098 240ms vs network 200ms
  - `J6KaKtLRj7eQGuVVL2CAz1AS9kDxsrmej9QbYkEtsiAD` SLOW_SLOTS_1098: epoch 1097 240ms vs network 200ms; epoch 1098 240ms vs network 200ms
  - `QodirbUG8AZQBWpHhPJPfjj1xg4AaQUZCVVtwT8YfPi` SLOW_SLOTS_1098: epoch 1097 259.5ms vs network 200ms; epoch 1098 259.5ms vs network 200ms (already listed: MALICIOUS_SM_826)
  - `TREEvcfDjQPEghHbisphwrvstkxCQNRH3E3jyosGagK` SLOW_SLOTS_1098: epoch 1097 240ms vs network 200ms; epoch 1098 240ms vs network 200ms
  - `fdvtuDvWJZ89Z7TmeLjCwxgoLcmoEWNxruV48DvJtfm` SLOW_SLOTS_1098: epoch 1097 240ms vs network 200ms; epoch 1098 240ms vs network 200ms
  - `mintrNtxN3PhAB45Pt41XqyKghTTpqcoBkQTZqh96iR` SLOW_SLOTS_1098: epoch 1097 245ms vs network 200ms; epoch 1098 245ms vs network 200ms
  - `mnvkHm47ZmRKoSWuQZAfXLRiDPiKCq8PWkMWrp1Wwqe` SLOW_SLOTS_1098: epoch 1097 240ms vs network 200ms; epoch 1098 240ms vs network 200ms
  - `xBLpiTwufjcuFCjbk4aCmFy7HUY5D9xy8L1EX2rBwmC` SLOW_SLOTS_1098: epoch 1097 245ms vs network 200ms; epoch 1098 244ms vs network 200ms
  - `6XPxXV2VZMNqSquPUF3bjnGt5u8R884A9UVYS6jv8g5f` SLOW_SLOTS_1097: epoch 1096 247ms vs network 200ms; epoch 1097 250ms vs network 200ms

</details>

- Removed = `59`
  - `2Y2opv8Kq8zFATg6ipqb2AjgCf18tkv1CLMLXQGif2NH`
  - `2mxWiqtwdpE8zgkWxwFaJLn127dbuuHY4D32d8A6UnPL`
  - `5K8qgC9nHzKHSSyo9fKLsMfYmavYdMgEaYx86cMmVKVv`
  - `5afRnmkFn1pRU9oussqwk1RRBVyoDgUkL16Jz4qNf574`
  - `5ni6KoVM62cRJNfFFKGdiyDfYbKWWAGZ21cfGZcj1y66`
  - `6anBvYWGwkkZPAaPF6BmzF6LUPfP2HFVhQUAWckKH9LZ`
  - `6jf9Hwx4ChqUpi8skCqmh7bnfTWXHXsqbfqAPHmSzPYc`
  - `6n8taYki7RscA1XW7xGmevLcqj855oSgDgjPe1dZyHfW`
  - `6x9uLhegx488uA3dPoq8DWHS488K4FsEqeeMXeW7kQPx`
  - `6yg4Usyr8VkvY8m7wrbLHegKVnKaAQmEwS6cuGnwB6wT`
  - `6zzAPhyFZgS6rdknHNZLcsoooZ744GtVmTDyfvRmN37Q`
  - `7emL18Bnve7wbYE9Az7vYJjikxN6YPU81igf6rVU5FN8`
  - `7obieMdVPKKcwEhhKizSkpdLaW1HMZh2ENrUDUhdGvVr`
  - `94qeNkhspb7DjuqNPcGUgVcnnsNuibGYuqNTvm9FnX9m`
  - `9RXDftY5xyhtYyzk4z7U9ddvBF2Z8DMfXmV6P6du9dxS`
  - `9hHEiSDTz9LeA4B4N2tJp6SPchwWZbV1X7zWN8hYoMhb`
  - `AEtdq4CwtuktCEUWLLpRTNPBZs6tr7BBqxkHJ1DjAttR`
  - `ANCVpxEySGWWLqqkVKw2xWYDE9UP4fmZWMCBr5t96jch`
  - `AZoCYB4VgoM9DR9f1ZFcBn8xPSbtbqoxZnKJR7tkvEoX`
  - `BfxZj7ckfRGHxByn7aHgH2puyXhfjAUvULtRjJo4rd8C`
  - `BmMVRAVef2qmJ1tJpG3JwRUtnfEiTbvDw9ZeFEi4wE7D`
  - `CHiaohVV2SQCFhiYP73iQzWT6HxnZqnAZJJqAYTeLAo`
  - `Chorus6Kis8tFHA7AowrPMcRJk3LbApHTYpgSNXzY5KE`
  - `DdCNGDpP7qMgoAy6paFzhhak2EeyCZcgjH7ak5u5v28m`
  - `DriFTm3wM9ugxhCA1K3wVQMSdC4Dv4LNmyZMmZiuHRpp`
  - `DzPT1ZWDeURdTj38QBSceWnrpYFxZRBLPRXmUgHVDAGR`
  - `EogKVYgic8LKAuV1kR9nRqJaS5zpwCvSMfqoehzmAMpK`
  - `EpicsoqLdDP8qRn3wQRKTSKAXbjK9dUgFfNPRQS77MQD`
  - `FWwnxVb7Q59MoMraDN2k8gqkdJJVd2qu9o5iiQsxpoUp`
  - `Fe5zMqkmoYbwnXH9RHjFy7YMRnak9so2bzPBroPJ4iiX`
  - `FpTQXdt7NjYsJWXaE9UgG2yPUshoFiW3nzXbXKz1CjKh`
  - `G8hvpQDLe7hGgYtWYt4TJJEbGbgLFCBJYiMi9pMD9Kk2`
  - `GFWtwTkSkgc9RcAUkUxs7LyZ124DsBtcSnWGWwbrA113`
  - `GLCrZmxWYcrGMA5uRa8mmNnQurGBL2p9zrKk9DKugSZX`
  - `GVYt3tbokX7mH4i86AA6Nh5hPiHEekercNZyNevviotL`
  - `Gar9q7Ru2sKfVxFnR5xmV8GieJeUSTp7Uf3ixai9BQKS`
  - `GiJj4MFyM4sCQ1aYQRQA9tqwtZFoaBdSxgNitWjHc2o9`
  - `GqcuMuWq4gKeCuCrD8iAjXTozCET2EP6qJXmZDFsSTWK`
  - `HCvnhbT3Sn5RsueDisWzzn5FkW8tAqoQK1dr7cvAVzin`
  - `Haz7b47sZBpxh9SwggGndN3fAyNQ1S949BPdxWXS3ab6`
  - `HdQ1Ap8wm6Mz65FaP8jMNBVfCDv5T9NdS8UTSvHmcotn`
  - `HjQugFHAUm7XbaZhmjnGioNUccdMUnFmwFTJgepm5q3n`
  - `JDMq8hxZnad2smKLGkFbfg8zVMZHKQcMugD4tMR9u2da`
  - `LNRmxHyXAzgBkgxDmb4ZefwLAnSv3fdsjPgjmThoa1T`
  - `LimeNKYH66uR9BwnrPtxPbpqmkambxHVcutGoSaWPiq`
  - `MS1kjUoVPfy4AgyJLiJ3eC6Gv34Cwr839MryJgNKdwJ`
  - `Pond1QyT1sQtiru3fi9G5LGaLRGeUpJKR1a2gdbq2u4`
  - `QUANT7qKUEW4PS4eP9jq4K35rDHpgWkWcgjbW1CwnGJ`
  - `R4spmF6oFW6wMQHv9L3PCEKumkspN3nveQihWyDAdRy`
  - `SmithX2hngQMZXVN36C6TsyjthTU3YnsALAs1MaDghV`
  - `Ste11vRHQJyQjcTKrDbTWAYsTXkX6PCnoEw3mSH3u2k`
  - `SyNdica7qx3njeVKNgXvV7KC1NjPYNS4fyb3NxgevLH`
  - `XzMLju7T6BSSngmsPogeuryd6uswiimkPU87gB2chho`
  - `fuyugZxM5S4NyV3ZYoc6ebs3fmRTrZ3X27MKCFvHpVD`
  - `gridZ5cMHjWGktAQt6o36NtF7XSv19nJBrW83zmo7BM`
  - `masvNDXtxVVMrYSV84RMry97JyHXAFcdfTZJ5VzpSYR`
  - `mesh3Px7WMi7Dkxke4ZZBULoKHM6sp37wKtg4DwPqPY`
  - `nateBZg7oHVPLB2samBLkKvfzedU3ALZBexMFPMKjn1`
  - `reyYoUdFgtDLxAWW1hyn5xk2PHstA3j8zUrerQi9Ayq`
- Penalties = `0` validators, estimated `0` SOL

<details><summary>ⓘ How it works</summary>

Each hit is one rule matching one validator. More new accounts than `blacklistRules.maxNewListings` (now `0`) holds every hit and adds none; `0` is a dry run. An account already listed under the same rule gives no hit.

</details>
