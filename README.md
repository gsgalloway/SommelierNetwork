# SommelierNetwork

Sommelier Network will go live on `7 Sept 21 @ 15:00 UTC`.

```bash
$ shasum -a 256 genesis.json
6337fa8078949fb7eeb7dda951c2844e3991e7f23872ad36c92154bdff6ae030  genesis.json
```

When you have your node ready to go, [please share you peering information with the other validators.](https://docs.google.com/spreadsheets/d/13LzGA2-0sgXQxdGPknCYDyUsjbBtMoY4VeLKxHNZzW8/edit#gid=0)

We expect the network to start sometime after `7 Sept 21 @ 15:00 UTC` and want to allow a full day for delegations to the new network to stabilize before deploying the gravity contract and starting the bridge. We will stop waiting for delegations at `8 Sept 21 @ 15:00 UTC` and at that time we will begin to deploy the gravity contract. After the contract is deployed we will share the contract address this repository and validators will need to start their orchestrator processes (i.e. `gorc orchestrator start`). Once all the validators start their processes and the first `SignerSetTx` gets sent then the bridge will be operational.