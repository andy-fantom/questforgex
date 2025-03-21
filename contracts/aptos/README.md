# Aptos Contracts

This directory contains Move smart contracts for the Aptos blockchain.

## Setup

```bash
aptos move build
aptos move test
aptos move publish --named-addresses questforgex=0x1
```

## Contracts

- `QuestManager.move` - Main quest management contract
- `RewardDistributor.move` - Handles reward distribution
- `QuestVerifier.move` - Verifies quest completion
- `Leaderboard.move` - Manages leaderboard state
