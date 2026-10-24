<div align="center">
<h3>AwesomeRepoHub</h3>
<h1>AI 智能体精选</h1>
<p>能跑起来、还在维护的智能体项目，按用途分类，中文写清该选谁</p>

<p><img alt="stars" src="https://img.shields.io/github/stars/AwesomeRepoHub/awesome-ai-agents?style=flat-square&color=0969da&label=stars"> <img alt="license" src="https://img.shields.io/github/license/AwesomeRepoHub/awesome-ai-agents?style=flat-square&color=2da44e"> <img alt="last commit" src="https://img.shields.io/github/last-commit/AwesomeRepoHub/awesome-ai-agents?style=flat-square&color=8250df"></p>

<p><a href="README.en.md">English</a> · <a href="CONTRIBUTING.md">参与贡献</a> · <a href="https://github.com/AwesomeRepoHub/awesome-index">全部合集</a></p>
</div>

> **19 个项目，共 1.5M Stars。** Stars、许可证、最近提交时间由 GitHub API 实时读取，数据更新于 2026-10-24。排名按 Stars 排序，仅作热度参考，不代表质量。

## 30 秒选型

| 你的情况 | 从这里开始 |
|:--|:--|
| 一周内做出能用的智能体 | [CrewAI](https://github.com/crewAIInc/crewAI) — 角色 + 任务 + 流程三件套，照着例子就能拼出第一条业务链路 |
| 流程有分支、重试、人工介入 | [LangGraph](https://github.com/langchain-ai/langgraph) — 状态图写法，能画出来也能回放，适合上生产 |
| 让 AI 自己开网页办事 | [Browser Use](https://github.com/browser-use/browser-use) — 直接操作浏览器，点按钮、填表单，不用为每个站点写爬虫 |
| 给智能体接私有文档和记忆 | [RAGFlow](https://github.com/infiniflow/ragflow) — 复杂表格和扫描件解析比通用 RAG 稳，配上 mem0 还能跨会话记住用户 |

## 目录

- [框架与编排](#框架与编排)
- [拿来就能用的智能体](#拿来就能用的智能体)
- [数据、记忆与检索](#数据记忆与检索)
- [入门与体系化学习](#入门与体系化学习)

## 框架与编排

从零写 agent 时选这里。区别主要在：要不要图结构、要不要多智能体分工、接不接现有系统。

| 项目 | 一句话说明 | Stars | 许可证 |
|:--|:--|--:|:--|
| [LangChain](https://github.com/langchain-ai/langchain) | 统一接模型、工具、检索和记忆，生态最全，适合先跑通原型 | 148k | `MIT` |
| [AutoGen](https://github.com/microsoft/autogen) | 微软的多智能体对话框架，擅长让多个 agent 分工协作并互相校验 | 61.5k | `CC-BY-4.0` |
| [CrewAI](https://github.com/crewAIInc/crewAI) | 用角色、任务、流程编排团队式智能体，概念少、上手快 | 60.0k | `MIT` |
| [LangGraph](https://github.com/langchain-ai/langgraph) | 状态图写有循环、分支和中断的智能体，适合长流程与生产环境 | 43.8k | `MIT` |
| [AgentScope](https://github.com/agentscope-ai/agentscope) | 阿里开源，强调可观测的分布式多智能体，适合研究型系统 | 33.8k | `Apache-2.0` |
| [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) | 官方轻量框架，工具调用与 agent 交接写得最直白 | 30.2k | `MIT` |
| [Semantic Kernel](https://github.com/microsoft/semantic-kernel) | 微软企业级 SDK，Python/.NET/Java 多语言，方便接现有系统 | 28.7k | `MIT` |

<sub>[回到目录](#目录)</sub>

## 拿来就能用的智能体

不用自己搭框架，直接部署或接入现有渠道。

| 项目 | 一句话说明 | Stars | 许可证 |
|:--|:--|--:|:--|
| [Browser Use](https://github.com/browser-use/browser-use) | 让模型直接操作浏览器点页面、填表单，Web 自动化首选 | 119k | `MIT` |
| [TradingAgents](https://github.com/TauricResearch/TradingAgents) | 多智能体模拟投研团队做交易决策，金融场景的参考实现 | 113k | `Apache-2.0` |
| [Paperclip](https://github.com/paperclipai/paperclip) | 把多个 agent 当同事管理的工作台，适合团队统一调度 | 107k | `MIT` |
| [DeerFlow](https://github.com/bytedance/deer-flow) | 字节的长任务超级智能体，调研、写代码、出报告串成一条链 | 84.3k | `MIT` |
| [nanobot](https://github.com/HKUDS/nanobot) | 极轻量的自托管个人助理，代码少，适合边用边读源码 | 49.3k | `MIT` |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) | 接 QQ、微信、Telegram 等多平台的机器人框架，中文生态活跃 | 43.0k | `AGPL-3.0` |

<sub>[回到目录](#目录)</sub>

## 数据、记忆与检索

智能体效果上限，多半卡在这一层：网页抓不干净、文档解析错、记不住用户。

| 项目 | 一句话说明 | Stars | 许可证 |
|:--|:--|--:|:--|
| [Firecrawl](https://github.com/firecrawl/firecrawl) | 把任意网页抓成干净 Markdown 喂给模型，站点批量抓取稳定 | 195k | `AGPL-3.0` |
| [RAGFlow](https://github.com/infiniflow/ragflow) | 深度文档解析 + 检索增强，表格和扫描件处理比通用方案稳 | 92.8k | `Apache-2.0` |
| [Crawl4AI](https://github.com/unclecode/crawl4ai) | 异步爬虫，直接输出 LLM 友好的结构化内容，自带反爬处理 | 86.1k | `Apache-2.0` |
| [Mem0](https://github.com/mem0ai/mem0) | 给智能体加长期记忆层，跨会话记住用户偏好与事实 | 67.7k | `Apache-2.0` |

<sub>[回到目录](#目录)</sub>

## 入门与体系化学习

先建立心智模型，再挑框架，能少走很多弯路。

| 项目 | 一句话说明 | Stars | 许可证 |
|:--|:--|--:|:--|
| [AI Agents for Beginners](https://github.com/microsoft/ai-agents-for-beginners) | 微软的入门课程，从工具调用写到多智能体，每节都有可跑代码 | 77.8k | `MIT` |
| [MetaGPT](https://github.com/FoundationAgents/MetaGPT) | 用软件公司分工模拟多智能体，从需求一路产出设计与文档 | 71.0k | `MIT` |

<sub>[回到目录](#目录)</sub>

## 为什么值得看

智能体领域最常见的坑是“演示惊艳、落地就崩”。这份清单把**框架**（自己写 agent）和**成品**（拿来就能用）分开列，每条都标注许可证与最近提交时间；已归档或长期停更的项目不留在主表里。

## 收录标准

- 有明确用途，README 能看懂、能跑起来；不收录只发概念或演示视频的项目。
- 许可证明确，仓库未归档；长期不更新的项目会标注并移出主表。
- 同一定位只留一个首选，同类项目放进同一小节横向对比，不做堆砌。
- Stars 只作参考，主要看维护频率、issue 响应和文档质量。
- 每条说明写清“解决什么问题、适合谁”，不搬运项目自述。

## 参与贡献

发现更好的项目、链接失效或说明有误？欢迎开 issue 或直接提交 PR，格式与要求见 [CONTRIBUTING.md](CONTRIBUTING.md)。收录后会在下一次生成时自动带上真实 Stars 与许可证。

## 关于这份清单

- 表里的 Stars、许可证、最近提交都是生成时从 GitHub API 拉取的，不是手写数字，所以不会过期。
- 每次增删项目只改一份精选数据，再跑生成脚本，中英文两个版本与 Stars 同时更新。
- 如果这份清单帮你少翻了十几个仓库，点个 **Star** 是最直接的支持：[⭐ Star awesome-ai-agents](https://github.com/AwesomeRepoHub/awesome-ai-agents/stargazers)

## 许可

内容采用 [MIT](LICENSE) 许可，可自由转载，注明来源即可。项目本身的版权与许可归各作者所有。

---

<sub>本文件由脚本从精选数据与 GitHub API 自动生成，请勿直接编辑；增删条目见 [CONTRIBUTING.md](CONTRIBUTING.md)。</sub>
