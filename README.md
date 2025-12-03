# Metana Bootcamp - Solidity Development
## Jakob Johnson

Smart contracts and DApps built during the Metana Blockchain Development Bootcamp (Aug 2024 - Jan 2025).

## 🛠️ Tech Stack

- Solidity ^0.8.20
- Foundry
- OpenZeppelin
- Sepolia Testnet

## 📚 Modules

- **M1:** Auction & Crowdfunding contracts
- **M2:** Escrow factory with CREATE2
- **M3:** Role-based rewards pool
- **M4:** ERC-20, ERC-721, ERC-1155 implementations
- **M5:** Token sale with frontend DApp
- **M6:** Time-locked wallet
- **M7:** DAO with Governor + Timelock
- **M8-M14:** In progress

## 🚀 Running Tests
```bash
cd [module-directory]
forge test
```

## 📫 Connect

- GitHub: [@jakejohndoe]
- Twitter: [@jakejohnhello]

---

Building towards a Web3 development career.


-------------------


## Foundry

**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

Foundry consists of:

- **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
- **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
- **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
- **Chisel**: Fast, utilitarian, and verbose solidity REPL.

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
