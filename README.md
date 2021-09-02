# SommelierNetwork

Validators: please add your gentxs to the `gentxs` folder with the following filename: `{validator_name}.json`.

```bash
# copy the genesis file from this repository
cp genesis.json ~/.sommelier/config/genesis.json

sommelier gentx validator {self-delegation-amount} \
    $(gorc --config $HOME/gorc/config.toml keys eth show signer) \
    $(sommelier keys show orchestrator --bech acc -a) \
    $(gorc sign-delegate-keys signer $(sommelier keys show validator --bech val -a) 0) \
    --chain-id sommelier-1
```
