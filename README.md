# Pieverse

Pieverse's AI-powered calendar aggregator acts as your central assistant for daily life, built on **BNB Smart Chain (BSC)** and compatible with other EVM networks.

## Technology Stack

- **Blockchain**: BNB Smart Chain + EVM-compatible chains  
- **Smart Contracts**: Solidity ^0.8.0
- **Frontend**: Next.js

## Supported Networks

- **BNB Smart Chain Mainnet** (Chain ID: 56)  
- **opBNB Testnet** (Chain ID: 5611)  

## Contract Addresses

| Network  | Time Challenge Contract | 
|----------|---------------|
| BNB Mainnet | 0x2b7c8b4a815e43e24abf562175de326822b2fc70 |

## Features

- On-chain Daily Beats proofs (privacy-preserving): Batch each day’s completions into a deterministic hash root and publish to BNB Chain. Titles/details stay off-chain; proofs are verifiable on-chain.
- Gas sponsorship via MegaFuel: Eligible users receive 1 sponsored upload per day; sponsored txs are sent with gasPrice=0. Automatically falls back to a normal transaction if not sponsorable.
- Smart-contract Time Challenges: Create, join, and finalize personal/prediction/commit challenges on BNB Chain with ERC-20 staking and on-chain state tracking.
  Earn points and unlock badges on successful on-chain uploads and challenge milestones; backend confirms and records rewards.
- Multi-chain and wallet integration: Built for BNB Smart Chain (Mainnet) and opBNB Testnet with Particle ConnectKit wallet support and gas-optimized defaults for BSC.
