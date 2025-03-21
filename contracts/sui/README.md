# Sui Contracts

This directory contains Move smart contracts for the Sui blockchain.

## Setup

```bash
sui move build
sui move test
sui client publish --gas-budget 10000000
```

## Contracts

- `quest_manager.move` - Main quest management contract
- `reward_distributor.move` - Handles reward distribution
- `quest_verifier.move` - Verifies quest completion
- `leaderboard.move` - Manages leaderboard state
