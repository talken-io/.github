# Talken IO

Multi-chain MPC wallet, cross-chain swap infrastructure, and AI agentic wallet ecosystem.

Talken builds wallet and protocol software for moving assets across EVM chains and Solana: swaps, bridges, wallet connectivity, account abstraction, staking, and agent-facing wallet operations.

## Product Surfaces

- [Talken](https://talken.io) - multi-chain wallet and Web3 user experience
- [Swap](https://swap.talken.io) - cross-chain swap interface
- [API](https://api.talken.io/api/v1) - quote, transaction-build, bridge, relayer, and paymaster endpoints

## Repository Quick Links

Most product repositories are private and require organization access.

### Cross-Chain Swap

- [Contracts](https://github.com/talken-io/talken-contracts) - 1-TX cross-chain atomic swap contracts, router, receiver, relayer, paymaster, and quote router
- [SDK](https://github.com/talken-io/talken-sdk) - TypeScript SDK for quoting, encoding, routing, and bridge helpers
- [API](https://github.com/talken-io/talken-api) - NestJS REST API wrapping SDK, quotes, TX builds, relayer, and paymaster flows
- [Swap Frontend](https://github.com/talken-io/talken-swap-frontend) - Next.js swap UI for multi-chain DEX routing and cross-chain execution

### Wallet Platform

- [Wallet Frontend](https://github.com/talken-io/talken-wallet-frontend) - Next.js multi-chain MPC wallet frontend
- [Wallet Backend](https://github.com/talken-io/talken-wallet-backend) - wallet backend for ABC WaaS, staking, rewards, and agent endpoints
- [TalkenKit](https://github.com/talken-io/talken-kit) - React wallet connection library and RainbowKit fork
- [Chrome Extension](https://github.com/talken-io/talken-chrome-extension) - Manifest V3 multi-chain wallet extension
- [Android](https://github.com/talken-io/talken-mfe-aos) - native Android mobile app
- [iOS](https://github.com/talken-io/talken-mfe-ios) - native iOS mobile app

### AI and Agentic Wallet

- [Agentic Wallet](https://github.com/talken-io/talken-agentic-wallet) - CLI and MCP server for agent wallet operations, swaps, bridges, and staking
- [AI Gateway](https://github.com/talken-io/talken-ai-gateway) - vendor-neutral AI access layer in front of Talken APIs

### TALK Token Infrastructure

- [OFT Contracts](https://github.com/talken-io/talken-oft-contracts) - TALK OFT multi-chain bridge contracts on LayerZero V2
- [Staking Contracts](https://github.com/talken-io/talken-staking-contracts) - TALK staking contracts with ve-model mechanics
- [ERC20 Contracts](https://github.com/talken-io/talken-erc20-contracts) - original TALK token contracts and reference material

### Operations

- [DevOps](https://github.com/talken-io/colligence-devops) - infrastructure docs, Docker stacks, GitHub Actions workflows, and operational scripts
- [Team Guide](https://github.com/talken-io/colligence-claude-guide) - shared engineering guidance

## What We Are Building

- One-transaction cross-chain swaps across EVM chains and Solana
- Gasless swap execution using EIP-7702, account abstraction, Permit2, relayers, and paymasters
- MPC wallet experiences across web, mobile, browser extension, Telegram, and desktop surfaces
- Agent-ready wallet tooling through API, CLI, and MCP interfaces
- TALK token bridging, staking, and ecosystem contract infrastructure

## Core Stack

- Solidity 0.8.22, Hardhat, OpenZeppelin, Account Abstraction
- TypeScript, ethers v6, viem, wagmi
- NestJS, Prisma, PostgreSQL, Redis
- Next.js, React, Tailwind CSS
- LayerZero V2, CCTP V2, Uniswap V3/V4, PancakeSwap V3, DragonSwap V3, Jupiter

## Supported Networks

- Ethereum
- Arbitrum
- Base
- BSC
- Polygon
- Kaia
- HyperEVM
- Solana

## Current Focus

- Cross-chain swap production hardening
- Gasless execution and relayer/paymaster reliability
- Wallet and TalkenKit integration quality
- Agentic wallet and AI gateway integration
- TALK OFT and staking operations
