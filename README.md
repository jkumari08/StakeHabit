# StakeHabit

**Put your money where your streak is**

StakeHabit is a Web3 habit-tracking dApp built on Polkadot. Users stake crypto to build accountability: complete daily habits to reclaim their stake (plus rewards); miss a day and your stake is burned.

---

## 🎯 Features

- **Staking Mechanism**: Deposit tokens into a smart contract to create skin-in-the-game.
- **On-Chain Tracking**: Daily habit check-ins logged immutably on-chain.
- **Decentralized Validators**: Community validators verify habit completion.
- **Reward & Burn Model**: Successful streaks return stake + reward; failures burn stake.
- **NFT Badges**: Earn collectible badges for milestone streaks.
- **DAO Governance**: Community-driven proposals & voting on new features.

---

## 🛠 Tech Stack

- **Blockchain**: Substrate / Polkadot parachain
- **Smart Contracts**: Ink! (Rust) or Solidity via PolkaVM
- **Frontend**: React · TypeScript · Tailwind CSS · Polkadot.js
- **Backend**: Node.js (indexer & notifications)
- **Storage**: IPFS (badge metadata)
- **Wallet Integration**: polkadot-js browser extension

---

## 🚀 Installation

### Prerequisites

- Node.js ≥ 16.x
- Rust & `cargo-contract`
- Yarn or npm
- Polkadot.js browser extension
- Substrate testnet (e.g., Westend)

### Clone & Setup

```bash
git clone https://github.com/your-org/stakehabit.git
cd stakehabit
```

### Build Smart Contract

```bash
cd contracts
cargo contract build
```

### Run Frontend

```bash
cd ../frontend
yarn install
yarn start
```

_App will be available at `http://localhost:3000`._

---

## 💡 Usage

1. Connect your wallet via the Polkadot.js extension.
2. Deposit a stake to start a new habit.
3. Check in daily to maintain your streak.
4. Validators confirm your completion.
5. **Success**: Stake returned + reward minted.
6. **Missed Day**: Stake burned.

---

## 🗺 Roadmap

- [x] MVP launch on Westend
- [ ] Parachain deployment on Polkadot mainnet
- [ ] Mobile dApp release
- [ ] Cross-chain support (e.g., Ethereum)<br/>

---

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feat/name`
3. Commit your changes: `git commit -m 'feat: description'`
4. Push to the branch: `git push origin feat/name`
5. Open a pull request

Please follow [Contributing Guidelines](./CONTRIBUTING.md) for details.

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](./LICENSE) file for details.


