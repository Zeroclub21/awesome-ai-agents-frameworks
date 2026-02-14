# 顶级 AI 智能体框架合集

精选的 AI 智能体框架列表，每日更新。

[English](README.md) | [Русский](README_RU.md) | **中文**

*最后更新时间: 2026-02-14 05:28:57*

## 对比表

| 排名 | 框架 | 星标 | 贡献者 | 变化 |
| :--- | :--- | :--- | :--- | :--- |
| 1 | [openclaw](#openclaw) | 192,509 | 595 | — |
| 2 | [nanobot](#nanobot) | 18,485 | 45 | — |
| 3 | [moltis](#moltis) | 537 | 5 | — |
| 4 | [MetaGPT](#metagpt) | 64,165 | 148 | ↑1 |
| 5 | [open-interpreter](#open-interpreter) | 62,135 | 132 | ↑1 |
| 6 | [autogen](#autogen) | 54,535 | 532 | ↑1 |
| 7 | [crewAI](#crewai) | 44,090 | 279 | ↑1 |
| 8 | [agno](#agno) | 37,839 | 390 | ↑1 |
| 9 | [AgentGPT](#agentgpt) | 35,700 | 72 | ↑1 |
| 10 | [smolagents](#smolagents) | 25,412 | 197 | ↑1 |
| 11 | [gpt-researcher](#gpt-researcher) | 25,305 | 216 | ↑1 |
| 12 | [langgraph](#langgraph) | 24,698 | 272 | ↑1 |
| 13 | [haystack](#haystack) | 24,185 | 323 | ↑1 |
| 14 | [babyagi](#babyagi) | 22,133 | 2 | ↑1 |
| 15 | [swarm](#swarm) | 20,950 | 14 | ↑1 |
| 16 | [eliza](#eliza) | 17,506 | 651 | ↑1 |
| 17 | [SuperAGI](#superagi) | 17,171 | 74 | ↑1 |
| 18 | [camel](#camel) | 16,015 | 192 | ↑1 |
| 19 | [pydantic-ai](#pydantic-ai) | 14,869 | 368 | ↑1 |
| 20 | [E2B](#e2b) | 10,887 | 44 | ↑1 |
| 21 | [PraisonAI](#praisonai) | 5,592 | 30 | ↑1 |
| 22 | [ms-agent](#ms-agent) | 3,977 | 47 | ↑1 |
| 23 | [agency-swarm](#agency-swarm) | 3,952 | 23 | ↑1 |
| 24 | [anthropic-sdk-python](#anthropic-sdk-python) | 2,760 | 51 | ↑1 |

---

### <a name="openclaw"></a>[openclaw](https://github.com/openclaw/openclaw) - Your own personal AI assistant. Any OS. Any Platform. The lobster way. 🦞 

192,509 星标 · 32,983 分叉 · 595 贡献者 · 5,468 问题 · TypeScript · MIT

    - 跨操作系统支持：兼容Windows、macOS、Linux等任意操作系统
    - 跨平台部署：支持桌面、移动和嵌入式任意平台
    - 本地化个人AI助手：提供高度个性化的本地运行AI服务
    - 模块化龙虾架构：轻量高效、可扩展的框架设计

### <a name="nanobot"></a>[nanobot](https://github.com/HKUDS/nanobot) - Ultra-lightweight AI agent kernel. Supports multiple providers, custom skills, cron jobs, and multi-channel communication (Telegram, Slack, etc.). Designed for efficiency and extensibility.

18,485 星标 · 2,702 分叉 · 45 贡献者 · 401 问题 · Python · MIT

    - 超轻量级 AI 代理内核
    - 支持多个提供商
    - 自定义技能
    - 支持 cron 定时任务和多渠道通信（Telegram、Slack 等）

### <a name="moltis"></a>[moltis](https://github.com/moltis-org/moltis) - A personal AI assistant built in Rust. Single binary, multi-provider LLMs, long-term memory, sandboxed execution, voice, MCP tools, and multi-channel access (web, Telegram, API).

537 星标 · 40 分叉 · 5 贡献者 · 33 问题 · Rust · MIT

    - Rust 单二进制构建
    - 多提供商 LLM 支持
    - 长期记忆机制
    - 沙箱化执行

### <a name="metagpt"></a>[MetaGPT](https://github.com/FoundationAgents/MetaGPT) - 🌟 The Multi-Agent Framework: First AI Software Company, Towards Natural Language Programming

64,165 星标 · 8,060 分叉 · 148 贡献者 · 78 问题 · Python · MIT

    - 多代理协作框架
    - 模拟AI软件公司角色分工
    - 标准化操作流程（SOP）
    - 自然语言编程生成可执行代码

### <a name="open-interpreter"></a>[open-interpreter](https://github.com/openinterpreter/open-interpreter) - A natural language interface for computers

62,135 星标 · 5,342 分叉 · 132 贡献者 · 294 问题 · Python · AGPL-3.0

    - 自然语言指令解析：利用大语言模型将用户自然语言描述转换为可执行代码。
    - 本地代码执行：在用户本地计算机上直接运行Python或其他编程语言代码，实现自动化操作。
    - 多模态支持：集成视觉能力，可分析截图或图像并据此执行计算机操作。
    - 安全交互机制：要求用户逐一确认代码执行，提供沙箱选项以确保安全性。

### <a name="autogen"></a>[autogen](https://github.com/microsoft/autogen) - A programming framework for agentic AI

54,535 星标 · 8,216 分叉 · 532 贡献者 · 586 问题 · Python · CC-BY-4.0

    - 多代理协作框架
    - 对话式智能体交互
    - 工具与函数调用集成
    - 灵活的工作流编排

### <a name="crewai"></a>[crewAI](https://github.com/crewAIInc/crewAI) - Framework for orchestrating role-playing, autonomous AI agents. By fostering collaborative intelligence, CrewAI empowers agents to work together seamlessly, tackling complex tasks.

44,090 星标 · 5,904 分叉 · 279 贡献者 · 276 问题 · Python · MIT

    - 角色扮演自主AI代理的编排框架
    - 促进协作智能的多代理协作机制
    - 实现代理间无缝协作执行
    - 高效处理复杂任务的能力

### <a name="agno"></a>[agno](https://github.com/agno-agi/agno) - Build multi-agent systems that learn and improve with every interaction.

37,839 星标 · 5,006 分叉 · 390 贡献者 · 565 问题 · Python · Apache-2.0

    - 多代理协作架构：支持构建高效的多代理系统，实现代理间无缝协作。
    - 交互式持续学习：代理在每一次交互中自动学习并更新知识，提升决策能力。
    - 实时自我优化机制：基于交互反馈动态调整代理行为，实现性能持续改进。
    - 适应性进化引擎：代理通过累积交互经验自主进化，适应复杂动态环境。

### <a name="agentgpt"></a>[AgentGPT](https://github.com/reworkd/AgentGPT) - 🤖 Assemble, configure, and deploy autonomous AI Agents in your browser.

35,700 星标 · 9,454 分叉 · 72 贡献者 · 220 问题 · TypeScript · GPL-3.0

    - 浏览器内组装自主AI代理
    - 灵活配置AI代理行为
    - 一键部署无服务器代理
    - 支持浏览器原生自主运行

### <a name="smolagents"></a>[smolagents](https://github.com/huggingface/smolagents) - 🤗 smolagents: a barebones library for agents that think in code.

25,412 星标 · 2,289 分叉 · 197 贡献者 · 369 问题 · Python · Apache-2.0

    - 代理通过生成代码进行思考和决策
    - 极简设计，轻量级库实现
    - 支持代码执行沙箱环境
    - 易集成多种代码生成模型

### <a name="gpt-researcher"></a>[gpt-researcher](https://github.com/assafelovic/gpt-researcher) - An autonomous agent that conducts deep research on any data using any LLM providers.

25,305 星标 · 3,359 分叉 · 216 贡献者 · 180 问题 · Python · Apache-2.0

    - 自主代理架构，支持独立执行复杂任务
    - 深度研究引擎，能够进行多步骤推理和信息合成
    - 通用数据处理，支持任意类型和来源的数据输入
    - 多LLM提供商兼容，可无缝集成各种大型语言模型

### <a name="langgraph"></a>[langgraph](https://github.com/langchain-ai/langgraph) - Build resilient language agents as graphs.

24,698 星标 · 4,301 分叉 · 272 贡献者 · 289 问题 · Python · MIT

    - 图状结构建模：将语言代理构建为节点与边的图状工作流
    - 弹性状态管理：支持检查点和持久化状态，实现容错恢复
    - 循环与分支支持：允许复杂决策路径和循环执行
    - 多代理协作：集成LLM构建可靠的多actor系统

### <a name="haystack"></a>[haystack](https://github.com/deepset-ai/haystack) - Open-source AI orchestration framework for building context-engineered, production-ready LLM applications. Design modular pipelines and agent workflows with explicit control over retrieval, routing, memory, and generation. Built for scalable agents, RAG, multimodal applications, semantic search, and conversational systems.

24,185 星标 · 2,598 分叉 · 323 贡献者 · 112 问题 · MDX · Apache-2.0

    - 模块化管道和代理工作流设计
    - 对检索、路由、内存和生成的明确控制
    - 支持可扩展代理、RAG和多模态应用
    - 适用于语义搜索和对话系统

### <a name="babyagi"></a>[babyagi](https://github.com/yoheinakajima/babyagi)

22,133 星标 · 2,849 分叉 · 2 贡献者 · 17 问题 · Python · No License

    - 自主任务生成：利用LLM基于现有结果创建新任务
    - 任务优先级排序：通过LLM对任务列表进行优先级评估
    - 任务执行循环：迭代执行高优先级任务并存储结果
    - 向量数据库集成：使用Pinecone存储任务嵌入以支持上下文检索

### <a name="swarm"></a>[swarm](https://github.com/openai/swarm) - Educational framework exploring ergonomic, lightweight multi-agent orchestration. Managed by OpenAI Solution team.

20,950 星标 · 2,228 分叉 · 14 贡献者 · 16 问题 · Python · MIT

    - 轻量级架构设计
    - 人体工程学优化接口
    - 多代理智能体编排
    - 教育性框架示例

### <a name="eliza"></a>[eliza](https://github.com/elizaOS/eliza) - Autonomous agents for everyone

17,506 星标 · 5,413 分叉 · 651 贡献者 · 140 问题 · TypeScript · MIT

    - 无代码自主代理构建器
    - 内置规划与执行引擎
    - 多代理协作框架
    - 易部署的开源架构

### <a name="superagi"></a>[SuperAGI](https://github.com/TransformerOptimus/SuperAGI) - <⚡️> SuperAGI - A dev-first open source autonomous AI agent framework. Enabling developers to build, manage & run useful autonomous agents quickly and reliably.

17,171 星标 · 2,158 分叉 · 74 贡献者 · 211 问题 · Python · MIT

    - 开发者优先设计
    - 开源自主AI代理框架
    - 快速构建和管理代理工具
    - 可靠运行自主代理

### <a name="camel"></a>[camel](https://github.com/camel-ai/camel) - 🐫 CAMEL: The first and the best multi-agent framework. Finding the Scaling Law of Agents. https://www.camel-ai.org

16,015 星标 · 1,771 分叉 · 192 贡献者 · 444 问题 · Python · Apache-2.0

    - 多代理协作框架
    - 首个多代理系统
    - 最佳性能表现
    - 代理缩放定律探索

### <a name="pydantic-ai"></a>[pydantic-ai](https://github.com/pydantic/pydantic-ai) - GenAI Agent Framework, the Pydantic way

14,869 星标 · 1,640 分叉 · 368 贡献者 · 535 问题 · Python · MIT

    - 基于 Pydantic 模型的严格类型验证与结构化输出
    - Schema 驱动的 GenAI 代理配置与工具定义
    - 自动 LLM 响应解析与数据验证
    - 无缝集成主流 LLM 提供商与 Python 类型系统

### <a name="e2b"></a>[E2B](https://github.com/e2b-dev/E2B) - Open-source, secure environment with real-world tools for enterprise-grade agents.

10,887 星标 · 769 分叉 · 44 贡献者 · 58 问题 · MDX · Apache-2.0

    - 开源框架
    - 安全运行环境
    - 集成真实世界工具
    - 支持企业级代理

### <a name="praisonai"></a>[PraisonAI](https://github.com/MervinPraison/PraisonAI) - PraisonAI is a production-ready Multi AI Agents framework, designed to create AI Agents to automate and solve problems ranging from simple tasks to complex challenges. It provides a low-code solution to streamline the building and management of multi-agent LLM systems, emphasising simplicity, customisation, and effective human-agent collaboration.

5,592 星标 · 763 分叉 · 30 贡献者 · 58 问题 · Python · MIT

    - 生产就绪的多AI代理框架
    - 低代码解决方案，支持简单到复杂任务自动化
    - 简化多代理LLM系统的构建与管理
    - 强调简单性、可定制性和高效人机协作

### <a name="ms-agent"></a>[ms-agent](https://github.com/modelscope/ms-agent) - MS-Agent: a lightweight framework to empower agentic execution of complex tasks

3,977 星标 · 460 分叉 · 47 贡献者 · 7 问题 · Python · Apache-2.0

    - 轻量级架构设计
    - 代理式任务自主执行
    - 复杂任务高效分解
    - 模块化组件集成

### <a name="agency-swarm"></a>[agency-swarm](https://github.com/VRSEN/agency-swarm) - Reliable Multi-Agent Orchestration Framework

3,952 星标 · 999 分叉 · 23 贡献者 · 14 问题 · Python · MIT

    - 可靠的多代理协调机制
    - 内置容错与自动恢复功能
    - 动态代理生命周期管理
    - 高效的任务调度与扩展支持

### <a name="anthropic-sdk-python"></a>[anthropic-sdk-python](https://github.com/anthropics/anthropic-sdk-python)

2,760 星标 · 456 分叉 · 51 贡献者 · 101 问题 · Python · MIT

    - 支持同步和异步API调用
    - 内置类型提示和Pydantic模型验证
    - 支持消息流式传输和工具调用
    - 简易API密钥认证和错误处理

---
### @tsingular
电报频道: [@tsingular](https://t.me/tsingular)
