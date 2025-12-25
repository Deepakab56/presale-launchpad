A decentralized launchpad factory smart contract inspired by platforms like PinkSale.
This protocol enables token creators to create and manage fair, secure, and feature-rich token presales, with built-in liquidity auto-locking, vesting, whitelisting, and flexible payment options — all fully on-chain and non-custodial.

📌 Table of Contents

Overview

Features

Tech Stack

Smart Contract Architecture

Workflow

Usage

Deployment

Security Notes

License

📖 Overview

Presale Launchpad Factory allows anyone to deploy and manage token presales without intermediaries.
Each presale is created via a factory contract, ensuring standardized logic, security, and transparency.

The protocol supports:

ETH and ERC-20 based presales

Automated liquidity provisioning on DEXs (e.g., Uniswap)

Fair launch mechanics

Vesting and locking for tokens and liquidity

Designed to be multi-chain EVM compatible, making it deployable on Ethereum, BNB Smart Chain, Polygon, and more.

✨ Features

✅ Create token presales with ETH or ERC-20 payment tokens
✅ 100% Token Supply Entered into Presale (no reserved or hidden allocation)
✅ 100% Liquidity Burn (LP tokens permanently burned, zero unlock risk)
✅ Auto-listing & liquidity provision on DEXs (e.g., Uniswap)
✅ Rug-proof liquidity mechanism (no LP withdrawal possible)
✅ Token vesting for both buyers and project owners
✅ Token burn and lock mechanisms
✅ Whitelist sale support
✅ Configurable soft cap, hard cap, min/max buy limits
✅ Fair launch detection and validation
✅ Admin withdrawal and fee settings
✅ Fully on-chain and non-custodial
✅ Multi-chain EVM compatible



PresaleFactory
 ├── creates → PresaleContract
 ├── enforces → 100% supply presale rule
 └── manages → platform fees

PresaleContract
 ├── accepts → 100% token supply
 ├── handles → user contributions
 ├── adds → 100% liquidity to DEX
 ├── burns → LP tokens permanently
 └── distributes → vested / claimable tokens
