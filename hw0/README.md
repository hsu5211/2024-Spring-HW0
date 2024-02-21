Wallet address : "0x00056CAba996e1E8C6CF8d04Ae8e3180159E2094"

Contract address : "0xbCe50eaf662A50DeCBAa7d7Ac9F36E1dDA2D82A7" 

<img width="316" alt="截圖 2024-02-21 晚上9 29 30" src="https://github.com/hsu5211/2024-Spring-HW0/assets/141152413/2c1d25ba-f9c5-466f-af07-56b86c7cb3ab">

<img width="1470" alt="截圖 2024-02-21 晚上9 35 14" src="https://github.com/hsu5211/2024-Spring-HW0/assets/141152413/140e7524-caf2-4e86-8bef-76ce2d01774a">

**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

Foundry consists of:

-   **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
-   **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
-   **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
-   **Chisel**: Fast, utilitarian, and verbose solidity REPL.

## Documentation

https://book.getfoundry.sh/

## Usage

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```

### Anvil

```shell
$ anvil
```


### Deploy

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### Cast

```shell
$ cast <subcommand>
```

### Help

```shell
$ forge --help
$ anvil --help
$ cast --help
```

