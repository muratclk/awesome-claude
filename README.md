# Awesome Claude [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of the best resources for [Anthropic's Claude](https://claude.ai) — models, apps, Claude Code, the Model Context Protocol, SDKs, tools, and learning material.

[Claude](https://claude.ai) is a family of AI models and products built by [Anthropic](https://www.anthropic.com), designed to be helpful, honest, and harmless. This list gathers high-signal resources for *using* Claude and *building* with it. Everything here is hand-picked and every link is checked — no dead ends, no filler.

**Read this in another language:** **English** · [Türkçe](translations/README.tr.md) · [add yours »](.github/CONTRIBUTING.md#translations)

## Contents

- [Official](#official)
- [Claude Code](#claude-code)
- [Model Context Protocol (MCP)](#model-context-protocol-mcp)
- [SDKs & Libraries](#sdks--libraries)
- [AI Coding Tools](#ai-coding-tools)
- [Chat Clients & Apps](#chat-clients--apps)
- [Notable Open-Source Projects](#notable-open-source-projects)
- [Learning & Prompting](#learning--prompting)
- [Benchmarks & Leaderboards](#benchmarks--leaderboards)
- [Contributing](#contributing)

## Official

### Sites & Docs

- [claude.ai](https://claude.ai) — Claude's web app for chatting, Projects, and Artifacts.
- [Anthropic.com](https://www.anthropic.com) — Anthropic's company site: research, news, safety, and announcements.
- [Claude.com](https://claude.com) — Product hub for Claude apps, plans, and platform offerings.
- [Claude Platform Docs](https://platform.claude.com/docs) — Official developer and API documentation for building with Claude.
- [API Reference](https://platform.claude.com/docs/en/api/overview) — Endpoint reference for the Messages, Batches, Models, and Agents APIs.
- [Claude Console](https://platform.claude.com) — Developer console with Workbench, API keys, workspaces, and usage limits.
- [Claude Status](https://status.claude.com) — Live uptime and incident status for the API, Console, and Claude Code.
- [Plans & Pricing](https://claude.com/pricing) — Consumer and API pricing across Free, Pro, Max, Team, and Enterprise.
- [Trust Center](https://trust.anthropic.com) — Security posture, compliance (SOC 2, ISO 27001/42001, HIPAA, GDPR), and policies.
- [Help Center](https://support.claude.com) — Official support articles for Claude apps, accounts, and features.

### Models

- [Models overview & comparison](https://platform.claude.com/docs/en/about-claude/models/overview) — Specs, model IDs, pricing, and context windows for all current Claude models.
- [Introducing Claude Fable 5 & Mythos 5](https://platform.claude.com/docs/en/about-claude/models/introducing-claude-fable-5-and-claude-mythos-5) — Launch details for Anthropic's Mythos-class frontier models.
- [Introducing Claude Sonnet 5](https://www.anthropic.com/news/claude-sonnet-5) — Announcement of Anthropic's most agentic Sonnet-tier model.
- [Pricing docs](https://platform.claude.com/docs/en/about-claude/pricing) — Full API pricing including batch discounts and prompt caching rates.
- [Release notes](https://platform.claude.com/docs/en/release-notes/overview) — Changelog for the Claude API, SDKs, and Console.
- [Model deprecations](https://platform.claude.com/docs/en/about-claude/model-deprecations) — Retirement schedule and migration guidance for legacy models.
- [Transparency Hub](https://www.anthropic.com/transparency) — Model and system cards, knowledge cutoffs, and safety reporting.

### Apps & Products

- [Download Claude](https://claude.com/download) — Desktop (macOS/Windows/Linux) and mobile (iOS/Android) app downloads.
- [Claude for Chrome](https://claude.com/claude-for-chrome) — Official browser extension that lets Claude read, click, and navigate sites for you.
- [Claude Enterprise](https://www.anthropic.com/product/enterprise) — Enterprise plan with SSO, SCIM, audit logs, and expanded context and admin controls.
- [Artifacts](https://www.anthropic.com/news/claude-powered-artifacts) — Build, host, and share interactive AI-powered apps directly in Claude.
- [Projects](https://support.claude.com/en/articles/9517075-what-are-projects) — Self-contained workspaces with dedicated chat history and a knowledge base.

## Claude Code

[Claude Code](https://claude.com/product/claude-code) is Anthropic's agentic coding tool for the terminal, IDE, and desktop.

### Core

- [anthropics/claude-code](https://github.com/anthropics/claude-code) — Official repository for Claude Code, Anthropic's agentic coding tool that runs in the terminal.
- [Claude Code Documentation](https://code.claude.com/docs) — Official docs covering install, settings, slash commands, hooks, subagents, plugins, and MCP.
- [Claude Agent SDK (TypeScript)](https://github.com/anthropics/claude-agent-sdk-typescript) — Official SDK exposing Claude Code's agent loop, tools, and context management.
- [Claude Agent SDK (Python)](https://github.com/anthropics/claude-agent-sdk-python) — Official Python SDK for building agents on the runtime that powers Claude Code.
- [Agent SDK Overview](https://code.claude.com/docs/en/agent-sdk/overview) — Official guide to programmatically building agents with the Claude Agent SDK.
- [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official) — Anthropic-managed directory of high-quality official Claude Code plugins.
- [Plugin Marketplaces Docs](https://code.claude.com/docs/en/plugin-marketplaces) — Official reference for creating and distributing Claude Code plugin marketplaces.
- [anthropics/claude-code-action](https://github.com/anthropics/claude-code-action) — Official GitHub Action to run Claude Code on PRs and issues via `@claude` mentions.

### Awesome Lists & Curations

- [hesreallyhim/awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) — Flagship curated list of Claude Code resources: skills, agents, statuslines, tooling, and plugins.
- [travisvn/awesome-claude-skills](https://github.com/travisvn/awesome-claude-skills) — Large curated list of Claude Skills, resources, and tools for customizing Claude Code workflows.
- [karanb192/awesome-claude-skills](https://github.com/karanb192/awesome-claude-skills) — Community collection of verified Claude Skills for TDD, debugging, git, and docs.
- [subinium/awesome-claude-code](https://github.com/subinium/awesome-claude-code) — Curated list of tools, skills, plugins, and MCP servers for Claude Code with a high inclusion bar.

### Subagents, Skills & Plugins

- [anthropics/skills](https://github.com/anthropics/skills) — Official repository of example Agent Skills with `SKILL.md` folders for creative, dev, and enterprise tasks.
- [wshobson/agents](https://github.com/wshobson/agents) — Marketplace of production-ready subagents, skills, and commands for Claude Code.
- [VoltAgent/awesome-claude-code-subagents](https://github.com/VoltAgent/awesome-claude-code-subagents) — Collection of specialized Claude Code subagents across development categories.
- [0xfurai/claude-code-subagents](https://github.com/0xfurai/claude-code-subagents) — Comprehensive collection of production-ready development subagents as markdown files.

### Hooks, Commands & Configs

- [disler/claude-code-hooks-mastery](https://github.com/disler/claude-code-hooks-mastery) — Reference project demonstrating every Claude Code hook lifecycle event with advanced patterns.
- [wshobson/commands](https://github.com/wshobson/commands) — Collection of production-ready slash commands (workflows and single-purpose tools) for Claude Code.
- [qdhenry/Claude-Command-Suite](https://github.com/qdhenry/Claude-Command-Suite) — Toolkit of slash commands, agents, and skills for structured software-development workflows.
- [sirmalloc/ccstatusline](https://github.com/sirmalloc/ccstatusline) — Highly customizable Claude Code statusline with powerline support, themes, and usage widgets.
- [ryoppippi/ccusage](https://github.com/ryoppippi/ccusage) — CLI for analyzing Claude Code usage and cost from local JSONL logs, with statusline integration.

### IDE & Editor Integrations

- [Claude Code in VS Code](https://code.claude.com/docs/en/vs-code) — Official VS Code extension with a native chat panel, checkpoints, @-mentions, and diff viewing.
- [Claude Code for JetBrains](https://plugins.jetbrains.com/plugin/27310-claude-code-beta-) — Official JetBrains plugin for IntelliJ, PyCharm, WebStorm, and others.
- [coder/claudecode.nvim](https://github.com/coder/claudecode.nvim) — Pure-Lua Neovim extension protocol-compatible with the official Claude Code IDE integrations.

## Model Context Protocol (MCP)

The [Model Context Protocol](https://modelcontextprotocol.io) is an open standard, created by Anthropic, for connecting AI apps to external tools and data.

### Core

- [Model Context Protocol](https://modelcontextprotocol.io) — Canonical documentation, guides, and specification hub for MCP.
- [Introducing MCP](https://www.anthropic.com/news/model-context-protocol) — Anthropic's original post introducing the open protocol.
- [modelcontextprotocol/modelcontextprotocol](https://github.com/modelcontextprotocol/modelcontextprotocol) — Official specification and documentation source repository.
- [MCP Specification](https://modelcontextprotocol.io/specification/2025-11-25) — The formal protocol spec (latest revision).
- [Python SDK](https://github.com/modelcontextprotocol/python-sdk) — Official Python SDK for building MCP servers and clients.
- [TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) — Official TypeScript SDK for MCP servers and clients.
- [Go SDK](https://github.com/modelcontextprotocol/go-sdk) — Official Go SDK for MCP.
- [C# SDK](https://github.com/modelcontextprotocol/csharp-sdk) — Official C# SDK, maintained with Microsoft.
- [Kotlin SDK](https://github.com/modelcontextprotocol/kotlin-sdk) — Official Kotlin SDK for MCP.
- [Ruby SDK](https://github.com/modelcontextprotocol/ruby-sdk) — Official Ruby SDK for MCP.
- [Rust SDK](https://github.com/modelcontextprotocol/rust-sdk) — Official Rust SDK for MCP.

### Registries & Directories

- [Official MCP Registry](https://registry.modelcontextprotocol.io) — The official centralized registry/API for discovering public MCP servers.
- [modelcontextprotocol/registry](https://github.com/modelcontextprotocol/registry) — Source for the community-driven official registry service.
- [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) — The most popular community-curated list of MCP servers.
- [appcypher/awesome-mcp-servers](https://github.com/appcypher/awesome-mcp-servers) — Large curated catalog of production and experimental MCP servers.
- [wong2/awesome-mcp-servers](https://github.com/wong2/awesome-mcp-servers) — Curated list of MCP servers (companion to mcpservers.org).
- [punkpeye/awesome-mcp-clients](https://github.com/punkpeye/awesome-mcp-clients) — Curated list of apps and tools that act as MCP clients.
- [PulseMCP](https://www.pulsemcp.com) — Searchable directory of MCP servers and clients with usage data.
- [Glama MCP Directory](https://glama.ai/mcp/servers) — Browsable directory of MCP servers and clients.
- [mcpservers.org](https://mcpservers.org) — Web directory of MCP servers and clients.

### Popular Servers

- [Reference servers](https://github.com/modelcontextprotocol/servers) — Anthropic's maintained reference servers: Filesystem, Fetch, Git, Memory, Sequential Thinking, Time, and more.
- [github/github-mcp-server](https://github.com/github/github-mcp-server) — GitHub's official MCP server for repos, issues, PRs, and workflows.
- [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) — Microsoft's Playwright MCP server for browser automation via accessibility snapshots.
- [upstash/context7](https://github.com/upstash/context7) — MCP server that delivers up-to-date library documentation to LLMs.
- [awslabs/mcp](https://github.com/awslabs/mcp) — Official collection of MCP servers for AWS services.
- [microsoft/mcp](https://github.com/microsoft/mcp) — Catalog of official Microsoft MCP server implementations.

### Clients & Tools

- [MCP Clients (official list)](https://modelcontextprotocol.io/clients) — Anthropic's list of applications that support MCP.
- [modelcontextprotocol/inspector](https://github.com/modelcontextprotocol/inspector) — Official visual testing and debugging tool for MCP servers.
- [FastMCP](https://github.com/jlowin/fastmcp) — Popular Pythonic framework for building MCP servers and clients.

> Many editors and agents are also MCP clients — see [Cursor](https://cursor.com), [Zed](https://zed.dev), [Cline](https://cline.bot), [Continue](https://continue.dev), and [Goose](https://github.com/block/goose) under [AI Coding Tools](#ai-coding-tools).

## SDKs & Libraries

### Official SDKs

- [Python SDK](https://github.com/anthropics/anthropic-sdk-python) — Official Python client for the Claude Messages API (sync/async, Pydantic models, streaming).
- [TypeScript SDK](https://github.com/anthropics/anthropic-sdk-typescript) — Official TypeScript/JavaScript SDK for Node.js, Deno, Bun, and browsers.
- [Go SDK](https://github.com/anthropics/anthropic-sdk-go) — Official Go SDK with context-based cancellation and functional options.
- [Java SDK](https://github.com/anthropics/anthropic-sdk-java) — Official Java SDK using the builder pattern and `CompletableFuture` async.
- [Ruby SDK](https://github.com/anthropics/anthropic-sdk-ruby) — Official Ruby SDK with Sorbet types and streaming helpers.
- [PHP SDK](https://github.com/anthropics/anthropic-sdk-php) — Official PHP SDK using value objects and the builder pattern.
- [C#/.NET SDK](https://github.com/anthropics/anthropic-sdk-csharp) — Official C#/.NET SDK (.NET Standard 2.0+) with `IChatClient` integration.

> The Python and TypeScript SDKs also ship first-party `AnthropicBedrock` and `AnthropicVertex` clients for Amazon Bedrock and Google Vertex AI.

### Agent Frameworks

- [LangChain](https://github.com/langchain-ai/langchain) — Popular LLM app framework with first-class Claude support via `langchain-anthropic`.
- [LangGraph](https://github.com/langchain-ai/langgraph) — Stateful, graph-based agent orchestration from the LangChain team; works with Claude.
- [LlamaIndex](https://github.com/run-llama/llama_index) — Data/RAG framework for LLM apps with an Anthropic LLM integration.
- [CrewAI](https://github.com/crewAIInc/crewAI) — Role-based multi-agent orchestration framework; runs Claude via provider configuration.
- [AutoGen](https://github.com/microsoft/autogen) — Microsoft multi-agent conversation framework with an Anthropic client.
- [Pydantic AI](https://github.com/pydantic/pydantic-ai) — Type-safe Python agent framework from the Pydantic team with native Anthropic support.
- [DSPy](https://github.com/stanfordnlp/dspy) — Stanford framework for programming (not prompting) LLMs; supports Claude models.
- [Mastra](https://github.com/mastra-ai/mastra) — TypeScript agent framework (memory, workflows, tools) with an Anthropic provider.
- [Vercel AI SDK](https://github.com/vercel/ai) — TypeScript toolkit for AI apps/agents; Claude via `@ai-sdk/anthropic`.
- [smolagents](https://github.com/huggingface/smolagents) — Hugging Face's minimal code-agents library; uses Claude via LiteLLM.
- [Agno](https://github.com/agno-agi/agno) — High-performance, model-agnostic multi-agent framework with Anthropic support.
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel) — Microsoft AI orchestration SDK (.NET/Python/Java) with an Anthropic connector.
- [Spring AI](https://github.com/spring-projects/spring-ai) — Spring framework for AI apps with a dedicated Anthropic Claude starter.
- [Haystack](https://github.com/deepset-ai/haystack) — deepset's LLM/RAG framework with Anthropic generator and chat components.

### Community Libraries

- [llm-anthropic](https://github.com/simonw/llm-anthropic) — Anthropic/Claude plugin for Simon Willison's `llm` CLI and Python library.
- [anthropix](https://github.com/lebrunel/anthropix) — Unofficial Elixir client for the Anthropic API, including tool use.
- [misanthropy](https://github.com/cortesi/misanthropy) — Idiomatic Rust bindings to the Anthropic API (streaming, tools, images, extended thinking).
- [clust](https://github.com/mochi-neko/clust) — Unofficial Rust client for the Anthropic/Claude API.
- [Anthropic.SDK](https://github.com/tghamm/Anthropic.SDK) — Feature-rich community .NET/C# library (streaming, tools, batching, Semantic Kernel integration).

### Gateways & Observability

- [LiteLLM](https://github.com/BerriAI/litellm) — Open-source SDK/proxy giving an OpenAI-compatible interface to 100+ providers including Anthropic.
- [OpenRouter](https://openrouter.ai) — Unified API gateway routing to hundreds of models, including the Claude family, through one endpoint.
- [Portkey Gateway](https://github.com/Portkey-AI/gateway) — Fast open-source AI gateway with guardrails and routing to many LLMs including Claude.
- [Langfuse](https://github.com/langfuse/langfuse) — Open-source LLM observability, tracing, and evals with Anthropic/Claude support.
- [Helicone](https://github.com/Helicone/helicone) — Open-source LLM observability and monitoring proxy supporting the Anthropic API.
- [Instructor](https://github.com/567-labs/instructor) — Structured (Pydantic) outputs from LLMs across providers, including Anthropic/Claude.

## AI Coding Tools

- [Aider](https://aider.chat) — Terminal-based AI pair programmer with automatic Git commits; Claude models rank among its top backends.
- [Cline](https://cline.bot) — Open-source autonomous coding agent for VS Code and JetBrains with first-class Claude support.
- [Continue](https://continue.dev) — Open-source AI assistant and agent for VS Code and JetBrains, configurable with Anthropic Claude.
- [Cursor](https://cursor.com) — AI-native code editor offering Claude Opus and Sonnet as selectable model backends.
- [Goose](https://github.com/block/goose) — Block's open-source AI agent for coding and workflows, supporting Claude among 15+ providers.
- [Kilo Code](https://github.com/Kilo-Org/kilocode) — Open-source agentic coding extension (VS Code, JetBrains, CLI) supporting Claude Opus/Sonnet.
- [Windsurf](https://windsurf.com) — Agentic AI IDE that runs multi-step coding tasks on Claude and other models.
- [Zed](https://zed.dev) — High-performance open-source editor with built-in agentic features that support Claude.

## Chat Clients & Apps

- [big-AGI](https://big-agi.com) — Expert multi-model AI workspace with direct Anthropic integration for Claude Opus/Sonnet.
- [Cherry Studio](https://github.com/CherryHQ/cherry-studio) — Open-source desktop AI workstation unifying 300+ models, including Anthropic Claude.
- [Chatbox](https://chatboxai.app) — Cross-platform AI client (open-source community edition) supporting Anthropic Claude models.
- [Jan](https://jan.ai) — Open-source, offline-first desktop ChatGPT alternative that connects to Claude via the Anthropic API.
- [LibreChat](https://librechat.ai) — Open-source multi-provider chat platform with native Claude support plus agents, MCP, and artifacts.
- [Lobe Chat](https://github.com/lobehub/lobe-chat) — Open-source modern chat framework supporting Anthropic Claude among many providers.
- [Open WebUI](https://openwebui.com) — Self-hosted, extensible chat UI that connects to Claude via Anthropic and OpenAI-compatible APIs.

## Notable Open-Source Projects

- [OpenHands](https://github.com/OpenHands/OpenHands) — Open-source autonomous software-engineering agent platform that runs on Claude (and other) models.
- [STORM](https://github.com/stanford-oval/storm) — Stanford's LLM knowledge-curation system that writes cited, Wikipedia-style reports; works with Claude via LiteLLM.
- [SWE-agent](https://github.com/SWE-agent/SWE-agent) — Princeton/Stanford agent that auto-fixes GitHub issues, reaching strong SWE-bench results using Claude models.

## Learning & Prompting

### Prompt Engineering

- [Prompt engineering overview](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/overview) — Anthropic's official hub on clarity, examples, XML structure, roles, chaining, and thinking.
- [Prompting best practices](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/claude-prompting-best-practices) — Official model-specific guidance tuned for Claude's latest models.
- [Interactive Prompt Engineering Tutorial](https://github.com/anthropics/prompt-eng-interactive-tutorial) — Official hands-on course with exercises, from basics to advanced techniques.
- [Prompt Engineering Guide (DAIR.AI)](https://www.promptingguide.ai/) — Popular open community guide with dedicated Claude/Anthropic sections.
- [Claude Code prompt library](https://code.claude.com/docs/en/prompt-library) — Copy-paste prompts for Claude Code tagged by task and role.

### Courses & Tutorials

- [Anthropic Academy](https://www.anthropic.com/learn/build-with-claude) — Anthropic's official learning hub organizing courses, guides, quickstarts, and docs.
- [Anthropic Courses (Skilljar)](https://anthropic.skilljar.com) — Free official course catalog including Claude 101 and Building with the Claude API.
- [anthropics/courses](https://github.com/anthropics/courses) — Anthropic's open educational repo: API fundamentals, prompt engineering, evaluations, and tool use.
- [Claude Cookbooks](https://github.com/anthropics/claude-cookbooks) — Official runnable notebooks for tool use, multimodal, evaluation, RAG, and agents.
- [Claude Quickstarts](https://github.com/anthropics/claude-quickstarts) — Deployable starter projects (customer-support agent, computer use, coding agent).

### Reading & Research

- [Building Effective Agents](https://www.anthropic.com/engineering/building-effective-agents) — Widely cited engineering guide on agent vs. workflow patterns and keeping designs simple.
- [Constitutional AI: Harmlessness from AI Feedback](https://arxiv.org/abs/2212.08073) — Anthropic's foundational paper on training models with a principle-based constitution.
- [Claude's Constitution](https://www.anthropic.com/news/claude-new-constitution) — Anthropic's document detailing Claude's intended values and behavior, released under CC0.
- [Mapping the Mind of a Large Language Model](https://www.anthropic.com/research/mapping-mind-language-model) — Interpretability work identifying millions of features inside Claude via dictionary learning.
- [Tracing the Thoughts of a Language Model](https://www.anthropic.com/research/tracing-thoughts-language-model) — Circuit-tracing research revealing how Claude internally computes and reasons.
- [Introducing Computer Use](https://www.anthropic.com/news/3-5-models-and-computer-use) — Announcement of Claude operating a computer by viewing the screen and controlling cursor and keyboard.
- [Anthropic Engineering Blog](https://www.anthropic.com/engineering) — Deep dives on agents, context engineering, tool use, and production practices.

### Newsletters, Blogs & Video

- [Import AI](https://importai.substack.com/) — Anthropic co-founder Jack Clark's weekly newsletter analyzing frontier AI research and policy.
- [Interconnects](https://www.interconnects.ai/) — Nathan Lambert's newsletter with sharp analysis of frontier-lab and open-model research.
- [Latent Space](https://www.latent.space/) — swyx & Alessio's high-signal AI Engineer newsletter and podcast, frequently featuring Anthropic builders.
- [Simon Willison's Weblog — Claude tag](https://simonwillison.net/tags/claude/) — Detailed, hands-on commentary on every major Claude and Anthropic release.
- [The Anthropic Stack](https://theanthropicstack.com/) — Practitioner newsletter on building with Claude, MCP, and AI agents.
- [Anthropic on YouTube](https://www.youtube.com/@anthropic-ai) — Anthropic's official channel with product demos, research talks, and Claude tutorials.
- [Claude Developer Newsletter](https://claude.com/newsletter/developers) — Anthropic's official developer email with announcements and best practices.

### Communities

- [Claude Community](https://claude.com/community) — Anthropic's official community hub linking its Discord, Reddit, and ambassador programs.
- [r/ClaudeAI](https://www.reddit.com/r/ClaudeAI/) — Large community subreddit for Claude discussion, tips, and comparisons.

## Benchmarks & Leaderboards

- [SWE-bench](https://www.swebench.com/) — Benchmark measuring real GitHub issue resolution, where Claude models rank among the top performers.
- [Aider Polyglot Leaderboard](https://aider.chat/docs/leaderboards/) — Multilingual code-editing benchmark that ranks Claude models.
- [Terminal-Bench](https://www.tbench.ai/leaderboard) — Benchmark for agents on real terminal tasks, evaluating Claude models.
- [Arena (formerly LMArena / Chatbot Arena)](https://arena.ai) — Human-preference LLM leaderboard that includes Claude models.
- [GAIA Leaderboard](https://huggingface.co/spaces/gaia-benchmark/leaderboard) — General AI assistant benchmark where Claude-based agents are evaluated.
- [Artificial Analysis](https://artificialanalysis.ai) — Independent LLM benchmarking site tracking Claude across quality, speed, and price.

## Contributing

Contributions are welcome — a single great link is a perfectly good pull request. Please read the [contribution guidelines](.github/CONTRIBUTING.md) first. In short: keep entries relevant to Claude, high quality, non-redundant, and formatted as `- [Name](https://url) — short factual description.`

Adding a translation? See [Translations](.github/CONTRIBUTING.md#translations).

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](LICENSE)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work. See [LICENSE](LICENSE) ([CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/)).
