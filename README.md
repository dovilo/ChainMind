# ChainMind — AI DeFi Strategy Agent Studio

![MiMo v2.5-pro](https://img.shields.io/badge/Powered%20by-MiMo%20v2.5--pro-00d4ff?style=for-the-badge&labelColor=0a0a0f)
![License: MIT](https://img.shields.io/badge/License-MIT-00e88f?style=for-the-badge&labelColor=0a0a0f)
![Web3](https://img.shields.io/badge/Web3-DeFi%20Agents-7b61ff?style=for-the-badge&labelColor=0a0a0f)

> **Build, simulate, and deploy autonomous AI agents that execute DeFi strategies on-chain.**

ChainMind is a visual platform where AI agents interact directly with DeFi protocols — scanning markets, reasoning through strategies, assessing risk, and executing on-chain transactions. Powered by **Xiaomi MiMo v2.5-pro** as the reasoning engine.

---

## 🧠 What Makes ChainMind Different

| Feature | AgentOS / CortexFlow | **ChainMind** |
|---|---|---|
| Focus | General AI pipelines | **DeFi strategy execution** |
| Agents reason about | Code, text, data | **Markets, yields, risk** |
| Execute on | Local tools | **On-chain transactions** |
| Protocols | None | **Uniswap, Aave, Lido, Curve, Maker, Compound** |
| Risk management | Manual | **Built-in risk agent** |
| MiMo usage | Generic reasoning | **Financial chain-of-thought analysis** |

---

## 🏗️ Architecture

```
┌─────────────────────────────────────────────────────────┐
│                    ChainMind Studio                       │
│                                                          │
│  ┌──────────┐    ┌──────────┐    ┌──────────┐           │
│  │ Market    │───▶│ MiMo     │───▶│ Yield    │           │
│  │ Scanner   │    │ Reasoner │    │ Optimizer│           │
│  └──────────┘    └────┬─────┘    └────┬─────┘           │
│                       │               │                  │
│                  ┌────▼─────┐    ┌────▼─────┐           │
│                  │ Risk     │───▶│ TX       │           │
│                  │ Manager  │    │ Executor │           │
│                  └──────────┘    └────┬─────┘           │
│                                       │                  │
│                    ┌──────────────────┼──────────┐       │
│                    ▼          ▼          ▼        ▼       │
│               ┌────────┐ ┌───────┐ ┌───────┐ ┌──────┐   │
│               │Uniswap │ │ Aave  │ │ Lido  │ │Curve │   │
│               │  V3    │ │  V3   │ │       │ │      │   │
│               └────────┘ └───────┘ └───────┘ └──────┘   │
│                                                          │
│  ┌──────────────────────────────────────────────────┐   │
│  │           MiMo v2.5-pro Reasoning Engine          │   │
│  │  • 128K context — full market history              │   │
│  │  • JSON mode — structured strategy output          │   │
│  │  • Chain-of-thought — transparent decision logic   │   │
│  └──────────────────────────────────────────────────┘   │
└─────────────────────────────────────────────────────────┘
```

---

## ✨ Key Features

- **🎨 Visual Strategy Builder** — Drag-and-drop agents and DeFi protocols onto an interactive canvas. Connect them to build execution pipelines.
- **🧠 MiMo Reasoning Engine** — Every strategy decision is powered by MiMo v2.5-pro with full chain-of-thought reasoning visible in real-time.
- **⚡ 5 AI Agent Types** — Market Scanner, MiMo Reasoner, TX Executor, Risk Manager, Yield Optimizer — each with specialized roles.
- **🔗 6 DeFi Protocols** — Uniswap V3, Aave V3, Lido, Compound, Curve, MakerDAO — with live TVL and APY data.
- **📊 Real-Time Dashboard** — Portfolio value, total APY, gas spent, active agents, transaction count, risk score.
- **🛡️ Built-In Risk Management** — Dedicated risk agent monitors exposure, correlation, and drawdown limits.
- **🎬 Live Simulation** — Watch agents reason, decide, and execute strategies step-by-step with animated token flow.
- **🔒 MEV Protection** — Executor agent routes through Flashbots Protect RPC to avoid sandwich attacks.

---

## 🚀 Quick Start

```bash
# Clone
git clone https://github.com/dovilo/ChainMind.git
cd ChainMind

# Open in browser (static site — no build step)
open index.html
# or
python3 -m http.server 8080
# → http://localhost:8080
```

**No dependencies. No build tools. Just open `index.html`.**

---

## 🎮 How to Use

1. **Drag agents** from the sidebar onto the canvas (Scanner, Reasoner, Executor, etc.)
2. **Drag protocols** (Uniswap, Aave, Lido, etc.) to define execution targets
3. **Connect nodes** by clicking output ports → input ports
4. **Click "Demo"** to load a pre-built strategy
5. **Click "Simulate"** to watch MiMo reason through the strategy in real-time
6. **Monitor metrics** in the bottom dashboard

---

## 🤖 Agent Types

| Agent | Role | MiMo Usage |
|---|---|---|
| 🔍 Market Scanner | Monitor prices, volume, volatility across DEXs | Pattern recognition in market data |
| 🧠 MiMo Reasoner | Core strategy analysis with chain-of-thought | Multi-step financial reasoning |
| ⚡ TX Executor | Build calldata, manage gas, submit transactions | Optimal routing decisions |
| 🛡️ Risk Manager | Position limits, correlation checks, drawdown alerts | Risk assessment with 128K context |
| 📈 Yield Optimizer | Cross-protocol APY comparison, optimal routing | Multi-variable optimization |

---

## 📈 Why MiMo v2.5-pro?

ChainMind leverages MiMo's unique capabilities for DeFi:

- **128K Context Window** — Ingest full market history, protocol documentation, and transaction logs in a single prompt
- **JSON Mode** — Structured output for strategy parameters, risk scores, and execution calldata
- **Chain-of-Thought** — Transparent reasoning for every financial decision (audit trail for regulators)
- **Cost Efficiency** — High-frequency strategy analysis at scale without breaking the bank

---

## 📁 Project Structure

```
ChainMind/
├── index.html      # Interactive visual demo (self-contained)
├── README.md       # This file
├── LICENSE         # MIT License
└── .gitignore      # Standard ignores
```

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

<p align="center">
  Built with 🧠 <strong>MiMo v2.5-pro</strong> · 100T AI Agent Competition
</p>
