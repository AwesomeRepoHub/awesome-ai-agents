<div align="center">
<h3>AwesomeRepoHub</h3>
<h1>Awesome AI Agents</h1>
<p>Agent frameworks and ready-to-use agents that still ship — grouped by what you are actually trying to do</p>

<p><img alt="stars" src="https://img.shields.io/github/stars/AwesomeRepoHub/awesome-ai-agents?style=flat-square&color=0969da&label=stars"> <img alt="license" src="https://img.shields.io/github/license/AwesomeRepoHub/awesome-ai-agents?style=flat-square&color=2da44e"> <img alt="last commit" src="https://img.shields.io/github/last-commit/AwesomeRepoHub/awesome-ai-agents?style=flat-square&color=8250df"></p>

<p><a href="README.md">中文</a> · <a href="CONTRIBUTING.md">Contributing</a> · <a href="https://github.com/AwesomeRepoHub/awesome-index">All collections</a></p>
</div>

> **19 projects, 1.5M stars in total.** Stars, licenses and last-commit dates are pulled from the GitHub API and refreshed on 2026-10-24. Sorted by stars for reference only — popularity is not quality.

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

## Frameworks and orchestration

Pick here when you build your own agent. The real differences: graph execution, multi-agent handoff, and how well it fits an existing stack.

| Project | What it does | Stars | License |
|:--|:--|--:|:--|
| [LangChain](https://github.com/langchain-ai/langchain) | The agent engineering platform. | 148k | `MIT` |
| [AutoGen](https://github.com/microsoft/autogen) | A programming framework for agentic AI | 61.5k | `CC-BY-4.0` |
| [CrewAI](https://github.com/crewAIInc/crewAI) | Framework for orchestrating role-playing, autonomous AI agents. By fostering collaborative intelligence, CrewAI… | 60.0k | `MIT` |
| [LangGraph](https://github.com/langchain-ai/langgraph) | Build resilient agents. | 43.8k | `MIT` |
| [AgentScope](https://github.com/agentscope-ai/agentscope) | Build and run agents you can see, understand and trust. | 33.8k | `Apache-2.0` |
| [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) | A lightweight, powerful framework for multi-agent workflows | 30.2k | `MIT` |
| [Semantic Kernel](https://github.com/microsoft/semantic-kernel) | Integrate cutting-edge LLM technology quickly and easily into your apps | 28.7k | `MIT` |

<sub>[Back to top](#contents)</sub>

## Ready-to-run agents

Deploy or plug in directly — no framework assembly required.

| Project | What it does | Stars | License |
|:--|:--|--:|:--|
| [Browser Use](https://github.com/browser-use/browser-use) | Open-source Python library for AI browser agents, plus Browser Use Cloud: stealth browsers and a hosted agent API. | 119k | `MIT` |
| [TradingAgents](https://github.com/TauricResearch/TradingAgents) | TradingAgents: Multi-Agents LLM Financial Trading Framework | 113k | `Apache-2.0` |
| [Paperclip](https://github.com/paperclipai/paperclip) | The open-source app everyone uses to manage agents at work | 107k | `MIT` |
| [DeerFlow](https://github.com/bytedance/deer-flow) | An open-source long-horizon SuperAgent harness that researches, codes, and creates. With the help of sandboxes… | 84.3k | `MIT` |
| [nanobot](https://github.com/HKUDS/nanobot) | Ultra-lightweight, open-source, self-hosted personal AI agent framework in Python with WebUI, tools, memory, MCP… | 49.3k | `MIT` |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) | AI Agent Assistant & development framework that integrates lots of IM platforms, LLMs, plugins and AI feature, and can… | 43.0k | `AGPL-3.0` |

<sub>[Back to top](#contents)</sub>

## Data, memory and retrieval

Most agent quality problems live here: dirty web data, broken PDF parsing, and no memory.

| Project | What it does | Stars | License |
|:--|:--|--:|:--|
| [Firecrawl](https://github.com/firecrawl/firecrawl) | Supercharge your AI agents with data from the web and beyond. Building the library for superintelligence. 🔥 | 195k | `AGPL-3.0` |
| [RAGFlow](https://github.com/infiniflow/ragflow) | RAGFlow is a leading open-source Retrieval-Augmented Generation (RAG) engine that fuses cutting-edge RAG with Agent… | 92.8k | `Apache-2.0` |
| [Crawl4AI](https://github.com/unclecode/crawl4ai) | Open-source web crawler and scraper for LLMs and AI agents: any website into clean, LLM-ready Markdown. Run it… | 86.1k | `Apache-2.0` |
| [Mem0](https://github.com/mem0ai/mem0) | The Memory Layer for AI Agents - Drop-in memory infrastructure for AI agents and apps. Context that persists. Built for… | 67.7k | `Apache-2.0` |

<sub>[Back to top](#contents)</sub>

## Learning paths

Build the mental model first; you will pick the right framework faster.

| Project | What it does | Stars | License |
|:--|:--|--:|:--|
| [AI Agents for Beginners](https://github.com/microsoft/ai-agents-for-beginners) | 18 Lessons to Get Started Building AI Agents | 77.8k | `MIT` |
| [MetaGPT](https://github.com/FoundationAgents/MetaGPT) | 🌟 The Multi-Agent Framework: First AI Software Company, Towards Natural Language Programming | 71.0k | `MIT` |

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
