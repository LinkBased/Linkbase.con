# LBD jobs

This folder contains cron job required for maintenance of LBD protocol

Cron job runs `rebase()` function on LBDTokenMonetaryPolicy and `sync()` function on UniswapV2Pair

## Build
```shell
go build -v
```

### Input arguments
- rpc - network rpc endpoint
- private key - private key of the orchestrator contract's owner
- orchestrator address - address of the orchestrator contract
- uniswap pair address - address of the uniswap pair contract 
