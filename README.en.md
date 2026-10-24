<div align="center">
<h3>AwesomeRepoHub</h3>
<h1>Awesome AI Agents</h1>
<p>Agent frameworks and ready-to-use agents that still ship — grouped by what you are actually trying to do</p>

<p><img alt="stars" src="https://img.shields.io/github/stars/AwesomeRepoHub/awesome-ai-agents?style=flat-square&color=0969da&label=stars"> <img alt="license" src="https://img.shields.io/github/license/AwesomeRepoHub/awesome-ai-agents?style=flat-square&color=2da44e"> <img alt="last commit" src="https://img.shields.io/github/last-commit/AwesomeRepoHub/awesome-ai-agents?style=flat-square&color=8250df"></p>

<p><a href="README.md">中文</a> · <a href="CONTRIBUTING.md">Contributing</a> · <a href="https://github.com/AwesomeRepoHub/awesome-index">All collections</a></p>
</div>

> **30 projects, 2.3M stars in total.** Stars, licenses and last-commit dates are pulled from the GitHub API and refreshed on 2026-10-24. Sorted by stars for reference only — popularity is not quality.

<sub>Reading the tables: stars and "Updated" come from the GitHub API at build time; license is read from the repository; notes in parentheses are limitations worth knowing first.</sub>

## Pick in 30 seconds

| Your situation | Start here |
|:--|:--|
| Ship a working agent this week | [CrewAI](https://github.com/crewAIInc/crewAI) — roles, tasks and flows — enough to model a real business process on day one |
| Branches, retries, human approval | [LangGraph](https://github.com/langchain-ai/langgraph) — stateful graphs you can draw, replay and debug in production |
| An agent that uses the web | [Browser Use](https://github.com/browser-use/browser-use) — drives a real browser instead of writing a scraper per site |
| Private docs and long-term memory | [RAGFlow](https://github.com/infiniflow/ragflow) — handles messy PDFs and tables; pair with mem0 for cross-session memory |

## Contents

- [Frameworks and orchestration](#frameworks-and-orchestration)
- [Ready-to-run agents](#ready-to-run-agents)
- [Data, memory and retrieval](#data-memory-and-retrieval)
- [Learning paths](#learning-paths)
- [Vertical agents](#vertical-agents)

## Frameworks and orchestration

_Pick here when you build your own agent. The real differences: graph execution, multi-agent handoff, and how well it fits an existing stack._

| Project | What it does | Stars | License | Updated |
|:--|:--|--:|:--|--:|
| [LangChain](https://github.com/langchain-ai/langchain) | The agent engineering platform. | 148k | `MIT` | 2026-10 |
| [AutoGen](https://github.com/microsoft/autogen) | A programming framework for agentic AI | 61.5k | `CC-BY-4.0` | 2026-10 |
| [CrewAI](https://github.com/crewAIInc/crewAI) | Framework for orchestrating role-playing, autonomous AI agents. By fostering collaborative intelligence, CrewAI… | 60.0k | `MIT` | 2026-10 |
| [LangGraph](https://github.com/langchain-ai/langgraph) | Build resilient agents. | 43.8k | `MIT` | 2026-10 |
| [Claude Code Agents](https://github.com/wshobson/agents) | Multi-harness agentic plugin marketplace for Claude Code, Codex, Cursor, OpenCode, GitHub Copilot, Google Antigravity… | 41.6k | `MIT` | 2026-10 |
| [AgentScope](https://github.com/agentscope-ai/agentscope) | Build and run agents you can see, understand and trust. | 33.8k | `Apache-2.0` | 2026-10 |
| [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) | A lightweight, powerful framework for multi-agent workflows | 30.2k | `MIT` | 2026-10 |
| [Semantic Kernel](https://github.com/microsoft/semantic-kernel) | Integrate cutting-edge LLM technology quickly and easily into your apps | 28.7k | `MIT` | 2026-10 |

<sub>[Back to top](#contents)</sub>

## Ready-to-run agents

_Deploy or plug in directly — no framework assembly required._

| Project | What it does | Stars | License | Updated |
|:--|:--|--:|:--|--:|
| [Dify](https://github.com/langgenius/dify) | Build Agentic workflows, RAG pipelines, with rich AI model and tool support on one collaborative workspace. Deploy on…（需自建服务） | 159k | `custom` | 2026-10 |
| [Browser Use](https://github.com/browser-use/browser-use) | Open-source Python library for AI browser agents, plus Browser Use Cloud: stealth browsers and a hosted agent API. | 119k | `MIT` | 2026-10 |
| [Paperclip](https://github.com/paperclipai/paperclip) | The open-source app everyone uses to manage agents at work | 107k | `MIT` | 2026-10 |
| [Odysseus](https://github.com/odysseus-dev/odysseus) | Self-hosted AI workspace. | 94.3k | `AGPL-3.0` | 2026-10 |
| [DeerFlow](https://github.com/bytedance/deer-flow) | An open-source long-horizon SuperAgent harness that researches, codes, and creates. With the help of sandboxes… | 84.3k | `MIT` | 2026-10 |
| [nanobot](https://github.com/HKUDS/nanobot) | Ultra-lightweight, open-source, self-hosted personal AI agent framework in Python with WebUI, tools, memory, MCP… | 49.3k | `MIT` | 2026-10 |
| [CowAgent](https://github.com/zhayujie/CowAgent) | Open-source personal AI assistant & Agent Harness. Plans tasks, runs tools and skills, self-evolves with memory and… | 47.5k | `MIT` | 2026-10 |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) | AI Agent Assistant & development framework that integrates lots of IM platforms, LLMs, plugins and AI feature, and can… | 43.0k | `AGPL-3.0` | 2026-10 |
| [Codewhale](https://github.com/codewhale-hq/Codewhale) | Open-source agent for the terminal written in Rust. Use any provider or model. Issues & PRs always welcome | 41.1k | `MIT` | 2026-10 |

<sub>[Back to top](#contents)</sub>

## Data, memory and retrieval

_Most agent quality problems live here: dirty web data, broken PDF parsing, and no memory._

| Project | What it does | Stars | License | Updated |
|:--|:--|--:|:--|--:|
| [Firecrawl](https://github.com/firecrawl/firecrawl) | Supercharge your AI agents with data from the web and beyond. Building the library for superintelligence. 🔥 | 195k | `AGPL-3.0` | 2026-10 |
| [Graphify](https://github.com/Graphify-Labs/graphify) | Turn any codebase, with its docs, SQL schemas, configs, and PDFs, into a queryable knowledge graph. A /graphify skill… | 134k | `Apache-2.0` | 2026-10 |
| [claude-mem](https://github.com/thedotmack/claude-mem) | Persistent Context Across Sessions for Every Agent – Captures everything your agent does during sessions, compresses it… | 103k | `Apache-2.0` | 2026-10 |
| [RAGFlow](https://github.com/infiniflow/ragflow) | RAGFlow is a leading open-source Retrieval-Augmented Generation (RAG) engine that fuses cutting-edge RAG with Agent… | 92.8k | `Apache-2.0` | 2026-10 |
| [Crawl4AI](https://github.com/unclecode/crawl4ai) | Open-source web crawler and scraper for LLMs and AI agents: any website into clean, LLM-ready Markdown. Run it… | 86.1k | `Apache-2.0` | 2026-10 |
| [Mem0](https://github.com/mem0ai/mem0) | The Memory Layer for AI Agents - Drop-in memory infrastructure for AI agents and apps. Context that persists. Built for… | 67.7k | `Apache-2.0` | 2026-10 |
| [Serviette](https://github.com/pathwaycom/serviette) | A no-code RAG server that keeps answers in sync with your documents. Works with 8 vector databases. Built on Pathway. | 58.8k | `MIT` | 2026-10 |

<sub>[Back to top](#contents)</sub>

## Learning paths

_Build the mental model first; you will pick the right framework faster._

| Project | What it does | Stars | License | Updated |
|:--|:--|--:|:--|--:|
| [AI Agents for Beginners](https://github.com/microsoft/ai-agents-for-beginners) | 18 Lessons to Get Started Building AI Agents | 77.8k | `MIT` | 2026-10 |
| [MetaGPT](https://github.com/FoundationAgents/MetaGPT) | 🌟 The Multi-Agent Framework: First AI Software Company, Towards Natural Language Programming | 71.0k | `MIT` | 2026-01 |
| [《深入理解 AI Agent》](https://github.com/bojieli/ai-agent-book) | 《深入理解 AI Agent：设计原理与工程实践》（李博杰 著）开源主仓库：全书正文、编译版 PDF 与按章配套代码 | 55.6k | `Apache-2.0` | 2026-10 |

<sub>[Back to top](#contents)</sub>

## Vertical agents

| Project | What it does | Stars | License | Updated |
|:--|:--|--:|:--|--:|
| [TradingAgents](https://github.com/TauricResearch/TradingAgents) | TradingAgents: Multi-Agents LLM Financial Trading Framework | 113k | `Apache-2.0` | 2026-10 |
| [BettaFish](https://github.com/666ghj/BettaFish) | 微舆：人人可用的多Agent舆情分析助手，打破信息茧房，还原舆情原貌，预测未来走向，辅助决策！从0实现，不依赖任何框架。 | 42.5k | `GPL-2.0` | 2026-10 |
| [Vibe-Trading](https://github.com/HKUDS/Vibe-Trading) | "Vibe-Trading: Your Personal Trading Agent" | 36.4k | `MIT` | 2026-10 |

<sub>[Back to top](#contents)</sub>

## Why this list

Most agent demos look great and break in production. This list separates **frameworks** (you build the agent) from **finished tools** (you use the agent), and keeps license plus last-commit date on every row. Archived or stale projects are dropped.

## Selection criteria

- A clear use case, a README you can follow and code that runs. No concept-only or demo-video projects.
- Explicit license and a repository that is not archived. Unmaintained projects are flagged and moved out of the main tables.
- One first choice per use case; alternatives sit in the same section for comparison instead of piling up.
- Stars are context, not a verdict. Maintenance cadence, issue response and docs matter more.
- Every line states the problem it solves and who it is for. No copy-pasted marketing copy.

## Contributing

Found a better project, a dead link or a wrong description? Open an issue or send a PR — see [CONTRIBUTING.md](CONTRIBUTING.md). Accepted entries get real stars and license data on the next build.

## About this list

- Stars, licenses and last-commit dates are fetched from the GitHub API at build time — never hand-copied, never stale.
- Adding or dropping a project edits one curated data file; the generator refreshes both languages and all numbers.
- If this saved you from opening a dozen repos, a **star** is the cheapest way to say thanks: [⭐ Star awesome-ai-agents](https://github.com/AwesomeRepoHub/awesome-ai-agents/stargazers)

## License

Content is licensed under [MIT](LICENSE) — reuse freely with attribution. Each project keeps its own copyright and license.

---

<sub>Generated from curated data and the GitHub API. Do not edit directly — see [CONTRIBUTING.md](CONTRIBUTING.md).</sub>
