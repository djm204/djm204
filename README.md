<div align="center">
  <img src="./banner.svg" alt="DJM204 Profile Banner" width="100%" />

  <br/><br/>

  [![GitHub Repos](https://img.shields.io/badge/GitHub-120%2B_Repos-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/djm204?tab=repositories)
  [![Frankenbeast](https://img.shields.io/badge/Frankenbeast-Agent_Runtime-00FF9D?style=for-the-badge&logo=typescript&logoColor=black)](https://github.com/djm204/frankenbeast)
  [![MCP Servers](https://img.shields.io/badge/Protocol-MCP_Suite-00F3FF?style=for-the-badge&logo=anthropic&logoColor=black)](https://github.com/djm204/mcp-servers)
  [![Agent Workflows](https://img.shields.io/badge/Workflows-Hermes_%26_Codex-FFD700?style=for-the-badge&logo=probot&logoColor=black)](https://github.com/djm204/codex-review)

</div>

---

### 👋 Hi, I'm David (`djm204`)

I build **deterministic agent runtimes**, **modular multi-agent systems**, and **tool-augmented LLM infrastructure**. 

My work focuses on bridging foundation models with reliable engineering: strict type validation (`Zod`), multi-loop orchestration, Model Context Protocol (`MCP`) tooling, and automated review/testing pipelines.

---

### 🛠️ Key Active Projects

#### 🦖 [Frankenbeast](https://github.com/djm204/frankenbeast)
> *A modular, deterministic agent runtime and guardrails framework built with TypeScript & Turborepo.*

- **The Beast Loop**: Interlocking execution loops for planning, execution, self-critique, and human-in-the-loop governance.
- **Modular Monorepo Packages**:
  - `franken-brain` — Memory systems, vector context, and persistence (SQLite/ChromaDB).
  - `franken-planner` — Task decomposition and execution trees.
  - `franken-critique` — Self-reflection and output quality gating.
  - `franken-governor` — HITL approval and safety policies.
  - `franken-mcp-suite` — MCP server registry, hooks, and execution proxies.
  - `live-bench` — Real-time CLI benchmarking for agent performance.

#### 🐝 [SmartSwarm](https://github.com/djm204/smart-swarm)
> *Production-grade multi-agent swarm platform and client interface for orchestrated task execution.*

#### 🤖 Agent Review & Automation Tools
- **[hermes-agent](https://github.com/djm204/hermes-agent)** — Autonomous workflow agent for pull request reviews and Hermes loops.
- **[codex-review](https://github.com/djm204/codex-review)** — Reusable Claude & Codex review loops for PR gating.
- **[resolve-issues](https://github.com/djm204/resolve-issues)** — Agent plugins for automated GitHub issue triage and resolution.
- **[agent-skills](https://github.com/djm204/agent-skills)** — Custom skill templates for agentic coding workflows.

#### 🔌 [mcp-servers](https://github.com/djm204/mcp-servers) & [mcp-web](https://github.com/djm204/mcp-web)
> *Custom Model Context Protocol (MCP) servers connecting LLMs with web scraping, local tool execution, and workspace state.*

#### ⚡ [ollama-orchestrator](https://github.com/djm204/ollama-orchestrator)
> *Lightweight local LLM orchestration tooling for privacy-focused Ollama setups.*

---

### 🧰 Real Stack & System Architecture

| Layer | Tools & Technologies |
| :--- | :--- |
| **Languages & Runtimes** | TypeScript, Node.js, Python, PyTorch, C++ / Rust |
| **Agent Runtimes** | `frankenbeast` (Custom), `hermes-agent`, `LangGraph`, `AutoGen`, `Ollama` |
| **Tool Protocols** | Model Context Protocol (MCP), REST / WebSocket APIs, CLI Execution |
| **Testing & Quality** | Vitest, Zod Schema Boundaries, Turborepo, Docker, SQLite |
| **Vector DBs & Memory** | ChromaDB, SQLite Memory Store, Hybrid Search |

---

### 🗺️ The Frankenbeast Architecture

```
                        ┌──────────────────────────────────────────────┐
                        │          🎯 REASONING & TASK INPUT           │
                        └──────────────────────┬───────────────────────┘
                                               │
                                               ▼
                        ┌──────────────────────────────────────────────┐
                        │         🦖 FRANKENBEAST ORCHESTRATOR         │
                        │           (The Beast Execution Loop)         │
                        └──────┬───────────────┬───────────────┬───────┘
                               │               │               │
         ┌─────────────────────┘               │               └─────────────────────┐
         ▼                                     ▼                                     ▼
┌─────────────────┐                   ┌──────────────────┐                  ┌──────────────────┐
│ 🧠 franken-brain│                   │📋franken-planner │                  │🧪franken-critique│
│ (Memory & State)│                   │(Task Trees & Plan│                  │ (Self-Reflection)│
└─────────────────┘                   └──────────────────┘                  └──────────────────┘
         │                                     │                                     │
         └─────────────────────┬───────────────┴───────────────┬─────────────────────┘
                               │                               │
                               ▼                               ▼
                    ┌─────────────────────┐         ┌─────────────────────┐
                    │🔌 franken-mcp-suite │         │🛡️ franken-governor  │
                    │(Tools & External API│         │(HITL & Policy Safety│
                    └─────────────────────┘         └─────────────────────┘
```

---

### 📫 Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/djm204)
[![Portfolio](https://img.shields.io/badge/Portfolio-00F3FF?style=for-the-badge&logo=react&logoColor=black)](https://github.com/djm204/cursor-portfolio)

</div>

<br/>

<div align="center">
  <sub>⚡ Building deterministic agent infrastructure & modular LLM tooling</sub>
</div>
