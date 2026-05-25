# ChainMind

![MiMo](https://img.shields.io/badge/Powered%20by-MiMo%20v2.5--pro-6366f1?style=flat-square)

**AI Agent Swarm Intelligence for Blockchain Operations**

An autonomous network of 5 specialized AI agents that monitor on-chain activity, detect patterns, predict events, and execute strategies in real-time — powered by Xiaomi MiMo v2.5-pro.

## 🤖 Agent Swarm

| Agent | Role | Status |
|-------|------|--------|
| 🔍 Scout | Mempool & block monitoring across 5+ EVM chains | Active |
| 🧠 Analyst | Pattern recognition, whale tracking, smart money flows | Active |
| ⚡ Strategy | MiMo chain-of-thought reasoning for trade signals | Reasoning |
| 🛡️ Sentinel | Rug pull detection, exploit monitoring, risk scoring | Active |
| 🚀 Executor | On-chain TX execution with MEV protection | Standby |

## 🧠 Why MiMo v2.5-pro?

- **128K context window** — analyze entire TX histories in one pass
- **Chain-of-thought reasoning** — deep analysis at each agent node
- **JSON mode** — structured output for agent-to-agent communication
- **Cost efficient** — run 5 agents 24/7 without breaking the bank

## 🏗️ Architecture

```
┌─────────────────────────────────────────┐
│           CHAINMIND AGENT SWARM         │
├─────────────────────────────────────────┤
│  Ethereum │ Base │ Arbitrum │ Polygon   │
│           └──────┬──────┘              │
│                  ▼                      │
│           ┌────────────┐               │
│           │ Scout Agent │               │
│           └──────┬─────┘               │
│                  ▼                      │
│     ┌────────────────────────┐          │
│     │ MiMo v2.5-pro Engine   │          │
│     │ 128K ctx · JSON mode   │          │
│     └─────┬──────────┬───────┘          │
│           ▼          ▼                  │
│    Analyst Agent  Sentinel Agent        │
│           ▼          ▼                  │
│        Strategy Agent                   │
│              ▼                          │
│       Executor Agent → On-chain TX      │
└─────────────────────────────────────────┘
```

## 🚀 Quick Start

```bash
git clone https://github.com/dovilo/ChainMind.git
cd ChainMind
# Open index.html in browser — fully self-contained
open index.html
```

## 📊 Features

- **Real-time mempool monitoring** — catch pending TX before confirmation
- **Whale tracking** — detect large movements and accumulation patterns
- **Rug pull detection** — pattern matching against 10,000+ exploit signatures
- **MEV protection** — private mempool routing via Flashbots
- **Natural language queries** — ask the swarm anything about on-chain activity
- **Multi-chain** — Ethereum, Base, Arbitrum, Polygon, BSC

## 📝 License

MIT © 2026
