# QuestForgeX

AI-powered on-chain quest engine using Move AI Agent Kit

## Overview

QuestForgeX is an advanced, AI-driven, on-chain quest generator that dynamically creates, tracks, and rewards Web3 user activities across multiple blockchains. The system is interactive, adaptive, and supports competitive gameplay mechanics, allowing users to engage in unique missions while earning blockchain-based rewards.

## Features

### AI-Driven Quest System
- Move AI Agent Kit analyzes user activity (NFT trades, DeFi interactions, in-game actions) to generate personalized missions
- Adaptive difficulty: AI learns from user behavior and adjusts quest complexity
- Real-time quest recommendations & challenges based on Web3 trends

### Smart Contract-Based Quest Execution
- Quests are on-chain, ensuring transparency
- Move Smart Contracts verify quest completion and automate rewards
- Modular quest templates allow projects to create custom missions

### Competitive Gameplay & Leaderboards
- Seasonal leaderboards for users to compete for top rewards
- Live quest tracking & progress visualization
- Multi-chain competition: users can complete quests across different blockchains

### Automated Reward System
- Reward users with NFTs, governance tokens, and in-game assets
- Uses IPFS for decentralized storage of NFT rewards
- Dynamic reward pools: AI adjusts reward structures based on engagement

### Cross-Chain & dApp Integration
- Supports Aptos, Sui, and other Move-compatible chains
- APIs for Web3 games, DeFi platforms, and NFT marketplaces to integrate dynamic quests
- AI suggests cross-chain quests (e.g., bridge assets between Aptos & Sui)

## Tech Stack

| Component | Technology |
|-----------|------------|
| AI Agent | Move AI Agent Kit |
| Blockchain | Aptos Testnet / Sui Testnet |
| Smart Contracts | Move Language |
| Backend | MongoDB |
| Frontend | Next.js with Vercel |
| Authentication | Wallet Authentication (Petra, Martian Wallets) |
| Storage | IPFS via Web3.Storage |
| Analytics & Tracking | MongoDB |
| Leaderboards | MongoDB |
| Charts & UI | Recharts.js |

## Project Structure

```
├── frontend/               # Next.js frontend application
├── backend/                # Backend services
├── contracts/              # Move smart contracts
│   ├── aptos/              # Aptos-specific contracts
│   └── sui/                # Sui-specific contracts
├── ai-agent/               # Move AI Agent Kit integration
└── docs/                   # Project documentation
```

## Setup & Development

See individual README files in each directory for setup instructions.

## License

MIT
