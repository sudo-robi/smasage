# SMASAGE (Smart Savings Agent) 🚀

**Smasage** is a next-generation personal savings agent built natively on the **Stellar** blockchain. It doesn't just store your money—it actively invests to help you reach your financial goals faster through an intelligent, conversational interface powered by **OpenClaw**.

## 🌟 Features

- **Interactive Goal Setting**: Chat with OpenClaw to define your financial goals, income, and risk tolerance.
- **Smart Investment Allocation**: Automatically distributes savings across:
  - **AAVE/Blend**: For stable, low-risk yield.
  - **Soroswap LPs**: For higher returns through liquidity provision.
  - **Tether Gold (XAUT)**: As a reliable inflation hedge.
- **Dynamic Monitoring**: The agent continuously monitors your portfolio and suggests strategy adjustments based on market conditions and your goal timeline.
- **Premium User Experience**: A sleek, modern dashboard built with Next.js and Vanilla CSS.

## 🛠 Tech Stack

- **Frontend**: [Next.js](https://nextjs.org/) (TypeScript, Vanilla CSS)
- **AI Agent**: [OpenClaw Framework](https://github.com/OpenClaw/openclaw) (Node.js)
- **Smart Contracts**: [Soroban](https://soroban.stellar.org/) (Rust)
- **Protocols**: Stellar DEX, Blend, Soroswap

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v20+)
- [Rust](https://www.rust-lang.org/) & [Soroban CLI](https://soroban.stellar.org/docs/installing-cli)
- [Freighter Wallet](https://www.freighter.app/) extension

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/smasage.git
   cd smasage
   ```

2. **Setup the Frontend**:

   ```bash
   cd frontend
   npm install
   npm run dev
   ```

3. **Setup the Agent**:

   ```bash
   cd agent
   npm install
   npm start
   ```

4. **Build the Contracts**:
   ```bash
   cd contracts
   cargo build --target wasm32-unknown-unknown
   ```

## 🗺 Roadmap

Our development is tracked via a detailed issue list. Key upcoming milestones include:

- [ ] Wallet integration (Freighter/Stellar SDK)
- [ ] Real-time portfolio indexing
- [ ] Automated rebalancing logic
- [ ] Enhanced conversational flow

See [issues.md](./issues.md) for a full breakdown of tasks.

## 🤝 Contributing

We welcome contributions from the community! Whether you're a frontend wizard, a Rust expert, or an AI enthusiast, there's a place for you at Smasage.

Please read our [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines on how to get started.

## 📜 License

Smasage is open-source software licensed under the MIT License.
