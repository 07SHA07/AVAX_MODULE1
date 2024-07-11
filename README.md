# DeFi Kingdom Clone on Avalanche

## Introduction

This project aims to create a decentralized game similar to DeFi Kingdom on the Avalanche blockchain. Players can collect, build, and battle with digital assets, earning rewards through various game activities.

## Features

- **Custom EVM Subnet:** Deploy smart contracts on a custom Avalanche subnet.
- **ERC20 Token Contract:** Create and manage your own game token.
- **Vault Contract:** Deposit and withdraw tokens.
- **Game Activities:** Implement battling, exploring, and trading.

## Smart Contracts

### ERC20 Token Contract

This contract implements a basic ERC20 token with the following features:
- **Total Supply:** The total number of tokens in existence.
- **Balance Of:** The balance of a specific account.
- **Transfer:** Transfer tokens to a specified address.
- **Allowance:** The number of tokens that an owner allowed to a spender.
- **Approve:** Approve the passed address to spend the specified amount of tokens.
- **Transfer From:** Transfer tokens from one address to another using the allowance mechanism.
- **Mint:** Create new tokens and add them to the total supply.
- **Burn:** Destroy tokens and reduce the total supply.

### Vault Contract

This contract allows users to deposit and withdraw ERC20 tokens with the following features:
- **Deposit:** Deposit tokens into the vault and receive shares in return.
- **Withdraw:** Withdraw tokens from the vault by burning shares.
- **Mint:** Mint new shares for the depositor.
- **Burn:** Burn shares of the withdrawer.
