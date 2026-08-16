# Awesome Claude [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of the best resources for Anthropic's Claude - models, apps, Claude Code, the Model Context Protocol, SDKs, tools, and learning material.

Claude is a family of AI models and products built by Anthropic, designed to be helpful, honest, and harmless. This list gathers high-signal resources for *using* Claude and *building* with it. Everything here is hand-picked and every link is checked - no dead ends, no filler.

**Read this in another language:** **English** · [Türkçe](translations/README.tr.md) · [add yours »](.github/CONTRIBUTING.md#translations)

## Contents

- [Official](#official)
- [Claude Code](#claude-code)
- [Skills](#skills)
- [Model Context Protocol (MCP)](#model-context-protocol-mcp)
- [SDKs & Libraries](#sdks--libraries)
- [AI Coding Tools](#ai-coding-tools)
- [Chat Clients & Apps](#chat-clients--apps)
- [Notable Open-Source Projects](#notable-open-source-projects)
- [Learning & Prompting](#learning--prompting)
- [Benchmarks & Leaderboards](#benchmarks--leaderboards)

## Official

### Sites & Docs

- [claude.ai](https://claude.ai) - Claude's web app for chatting, Projects, and Artifacts.
- [Anthropic.com](https://www.anthropic.com) - Anthropic's company site: research, news, safety, and announcements.
- [Claude.com](https://claude.com) - Product hub for Claude apps, plans, and platform offerings.
- [Claude Platform Docs](https://platform.claude.com/docs) - Official developer and API documentation for building with Claude.
- [API Reference](https://platform.claude.com/docs/en/api/overview) - Endpoint reference for the Messages, Batches, Models, and Agents APIs.
- [Claude Console](https://platform.claude.com) - Developer console with Workbench, API keys, workspaces, and usage limits.
- [Claude Status](https://status.claude.com) - Live uptime and incident status for the API, Console, and Claude Code.
- [Plans & Pricing](https://claude.com/pricing) - Consumer and API pricing across Free, Pro, Max, Team, and Enterprise.
- [Trust Center](https://trust.anthropic.com) - Security posture, compliance (SOC 2, ISO 27001/42001, HIPAA, GDPR), and policies.
- [Help Center](https://support.claude.com) - Official support articles for Claude apps, accounts, and features.

### Models

- [Models overview & comparison](https://platform.claude.com/docs/en/about-claude/models/overview) - Specs, model IDs, pricing, and context windows for all current Claude models.
- [Introducing Claude Opus 5](https://www.anthropic.com/news/claude-opus-5) - Anthropic's July 2026 Opus release with a 1M-token context window and adaptive thinking.
- [Introducing Claude Fable 5 & Mythos 5](https://platform.claude.com/docs/en/about-claude/models/introducing-claude-fable-5-and-claude-mythos-5) - Launch details for Anthropic's Mythos-class frontier models.
- [Introducing Claude Sonnet 5](https://www.anthropic.com/news/claude-sonnet-5) - Announcement of Anthropic's most agentic Sonnet-tier model.
- [Introducing Claude Opus 4.5](https://www.anthropic.com/news/claude-opus-4-5) - November 2025 launch of the model that completed the Claude 4.5 family, tuned for coding and agents.
- [Pricing docs](https://platform.claude.com/docs/en/about-claude/pricing) - Full API pricing including batch discounts and prompt caching rates.
- [Release notes](https://platform.claude.com/docs/en/release-notes/overview) - Changelog for the Claude API, SDKs, and Console.
- [Model deprecations](https://platform.claude.com/docs/en/about-claude/model-deprecations) - Retirement schedule and migration guidance for legacy models.
- [Transparency Hub](https://www.anthropic.com/transparency) - Model and system cards, knowledge cutoffs, and safety reporting.

### Apps & Products

- [Artifacts](https://www.anthropic.com/news/claude-powered-artifacts) - Build, host, and share interactive AI-powered apps directly in Claude.
- [Bringing memory to Claude](https://claude.com/blog/memory) - Optional memory that lets Claude remember your projects, preferences, and context across conversations.
- [Claude Code on the web](https://claude.com/blog/claude-code-on-the-web) - Delegate coding tasks from the browser or mobile app, running in parallel on Anthropic-managed cloud sandboxes.
- [Claude Cowork](https://claude.com/blog/cowork-research-preview) - Agentic knowledge-work companion that reads and writes local files and works across connected apps like Slack and Google Drive.
- [Claude Enterprise](https://www.anthropic.com/product/enterprise) - Enterprise plan with SSO, SCIM, audit logs, and expanded context and admin controls.
- [Claude for Chrome](https://claude.com/claude-for-chrome) - Official browser extension that lets Claude read, click, and navigate sites for you.
- [Claude for Microsoft 365](https://claude.com/claude-for-excel) - Native Claude integration inside Excel, PowerPoint, Word, and Outlook that edits files and carries context across the apps.
- [Download Claude](https://claude.com/download) - Desktop (macOS/Windows/Linux) and mobile (iOS/Android) app downloads.
- [Projects](https://support.claude.com/en/articles/9517075-what-are-projects) - Self-contained workspaces with dedicated chat history and a knowledge base.

## Claude Code

[Claude Code](https://claude.com/product/claude-code) is Anthropic's agentic coding tool for the terminal, IDE, and desktop.

### Core

- [anthropics/claude-code](https://github.com/anthropics/claude-code) - Official repository for Claude Code, Anthropic's agentic coding tool that runs in the terminal.
- [Claude Code Documentation](https://code.claude.com/docs) - Official docs covering install, settings, slash commands, hooks, subagents, plugins, and MCP.
- [Claude Agent SDK (TypeScript)](https://github.com/anthropics/claude-agent-sdk-typescript) - Official SDK exposing Claude Code's agent loop, tools, and context management.
- [Claude Agent SDK (Python)](https://github.com/anthropics/claude-agent-sdk-python) - Official Python SDK for building agents on the runtime that powers Claude Code.
- [Agent SDK Overview](https://code.claude.com/docs/en/agent-sdk/overview) - Official guide to programmatically building agents with the Claude Agent SDK.
- [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official) - Anthropic-managed directory of high-quality official Claude Code plugins.
- [Plugin Marketplaces Docs](https://code.claude.com/docs/en/plugin-marketplaces) - Official reference for creating and distributing Claude Code plugin marketplaces.
- [anthropics/claude-code-action](https://github.com/anthropics/claude-code-action) - Official GitHub Action to run Claude Code on PRs and issues via `@claude` mentions.

### Awesome Lists & Curations

- [hesreallyhim/awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) - Flagship curated list of Claude Code resources: skills, agents, statuslines, tooling, and plugins.
- [subinium/awesome-claude-code](https://github.com/subinium/awesome-claude-code) - Curated list of tools, skills, plugins, and MCP servers for Claude Code with a high inclusion bar.

### Subagents & Plugins

- [wshobson/agents](https://github.com/wshobson/agents) - Marketplace of production-ready subagents, skills, and commands for Claude Code.
- [VoltAgent/awesome-claude-code-subagents](https://github.com/VoltAgent/awesome-claude-code-subagents) - Collection of specialized Claude Code subagents across development categories.
- [0xfurai/claude-code-subagents](https://github.com/0xfurai/claude-code-subagents) - Comprehensive collection of production-ready development subagents as markdown files.

### Hooks, Commands & Configs

- [disler/claude-code-hooks-mastery](https://github.com/disler/claude-code-hooks-mastery) - Reference project demonstrating every Claude Code hook lifecycle event with advanced patterns.
- [wshobson/commands](https://github.com/wshobson/commands) - Collection of production-ready slash commands (workflows and single-purpose tools) for Claude Code.
- [qdhenry/Claude-Command-Suite](https://github.com/qdhenry/Claude-Command-Suite) - Toolkit of slash commands, agents, and skills for structured software-development workflows.
- [sirmalloc/ccstatusline](https://github.com/sirmalloc/ccstatusline) - Highly customizable Claude Code statusline with powerline support, themes, and usage widgets.
- [ryoppippi/ccusage](https://github.com/ryoppippi/ccusage) - CLI for analyzing Claude Code usage and cost from local JSONL logs, with statusline integration.
- [Haleclipse/CCometixLine](https://github.com/Haleclipse/CCometixLine) - High-performance Claude Code statusline written in Rust with Git integration, usage tracking, and TUI configuration.
- [Maciek-roboblog/Claude-Code-Usage-Monitor](https://github.com/Maciek-roboblog/Claude-Code-Usage-Monitor) - Real-time terminal usage monitor with token and cost tracking, burn-rate predictions, and limit warnings.

### Tools & Extensions

- [dagger/container-use](https://github.com/dagger/container-use) - MCP server giving each coding agent a fresh container on its own Git branch so multiple agents work in parallel.
- [davila7/claude-code-templates](https://github.com/davila7/claude-code-templates) - CLI for configuring and monitoring Claude Code, with a catalog of agents, commands, hooks, and MCP configs.
- [musistudio/claude-code-router](https://github.com/musistudio/claude-code-router) - Local proxy that routes Claude Code requests across different models and providers with rule-based routing.
- [slopus/happy](https://github.com/slopus/happy) - Mobile and web client for Claude Code with realtime voice, end-to-end encryption, and remote control from your phone.
- [smtg-ai/claude-squad](https://github.com/smtg-ai/claude-squad) - Terminal manager for running multiple Claude Code agents in parallel, each in its own Git worktree and tmux session.
- [SuperClaude-Org/SuperClaude_Framework](https://github.com/SuperClaude-Org/SuperClaude_Framework) - Configuration framework that extends Claude Code with specialized slash commands, personas, and methodologies.
- [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem) - Persistent memory plugin that compresses each session and injects relevant context into future Claude Code sessions.

### IDE & Editor Integrations

- [Claude Code in VS Code](https://code.claude.com/docs/en/vs-code) - Official VS Code extension with a native chat panel, checkpoints, @-mentions, and diff viewing.
- [Claude Code for JetBrains](https://plugins.jetbrains.com/plugin/27310-claude-code-beta-) - Official JetBrains plugin for IntelliJ, PyCharm, WebStorm, and others.
- [coder/claudecode.nvim](https://github.com/coder/claudecode.nvim) - Pure-Lua Neovim extension protocol-compatible with the official Claude Code IDE integrations.

## Skills

Agent Skills are folders with a `SKILL.md` file that package instructions, scripts, and resources Claude loads on demand - they work across Claude apps, Claude Code, the API, and the Agent SDK.

### Official & Docs

- [Introducing Agent Skills](https://claude.com/blog/skills) - Anthropic's launch announcement for Agent Skills.
- [Equipping agents for the real world with Agent Skills](https://www.anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills) - Anthropic engineering deep dive on how Agent Skills work and how to design them.
- [Agent Skills overview](https://platform.claude.com/docs/en/agents-and-tools/agent-skills/overview) - Official documentation on what Agent Skills are and the SKILL.md format.
- [Skill authoring best practices](https://platform.claude.com/docs/en/agents-and-tools/agent-skills/best-practices) - Official guide to writing effective SKILL.md files that Claude can discover and use.
- [Using Agent Skills with the API](https://platform.claude.com/docs/en/build-with-claude/skills-guide) - Official guide to uploading and invoking Skills through the Claude API.
- [Skills in Claude Code](https://code.claude.com/docs/en/skills) - Official Claude Code docs for creating, managing, and invoking Skills.
- [Introduction to Agent Skills](https://anthropic.skilljar.com/introduction-to-agent-skills) - Free official Anthropic Academy course on building and sharing Skills.
- [The Complete Guide to Building Skills for Claude](https://resources.anthropic.com/hubfs/The-Complete-Guide-to-Building-Skill-for-Claude.pdf) - Anthropic's downloadable handbook on designing and authoring Skills.
- [Agent Skills open standard](https://agentskills.io) - The open specification for the SKILL.md format, originated by Anthropic.

### Collections & Marketplaces

- [anthropics/skills](https://github.com/anthropics/skills) - Anthropic's official repository of open-source example Skills.
- [travisvn/awesome-claude-skills](https://github.com/travisvn/awesome-claude-skills) - Popular curated list of Claude Skills, resources, and tools.
- [karanb192/awesome-claude-skills](https://github.com/karanb192/awesome-claude-skills) - Community collection of verified Skills for Claude Code, claude.ai, and the API.
- [Claude Code Marketplaces](https://claudemarketplaces.com/) - Searchable directory of Claude Code Skills, plugins, and MCP servers.
- [nvidia/skills](https://github.com/nvidia/skills) - Official NVIDIA Agent Skills for Claude Code and other agents, covering robotics, simulation, CUDA, and RAG.
- [obra/superpowers](https://github.com/obra/superpowers) - Composable Agent Skills framework and software-development methodology, installable via the Claude Code plugin marketplace.

### Tools for Building Skills

- [skill-creator](https://github.com/anthropics/skills/tree/main/skills/skill-creator) - Anthropic's meta-Skill that guides you through creating and refining new Skills.
- [claudelint Skills validator](https://claudelint.com/validators/skills) - Linter that checks SKILL.md files for correctness, security, and quality.
- [agent-ecosystem/skill-validator](https://github.com/agent-ecosystem/skill-validator) - CLI that validates and scores Agent Skill packages.

## Model Context Protocol (MCP)

The Model Context Protocol is an open standard, created by Anthropic, for connecting AI apps to external tools and data.

### Core

- [Model Context Protocol](https://modelcontextprotocol.io) - Canonical documentation, guides, and specification hub for MCP.
- [Introducing MCP](https://www.anthropic.com/news/model-context-protocol) - Anthropic's original post introducing the open protocol.
- [modelcontextprotocol/modelcontextprotocol](https://github.com/modelcontextprotocol/modelcontextprotocol) - Official specification and documentation source repository.
- [MCP Specification](https://modelcontextprotocol.io/specification/2025-11-25) - The formal protocol spec (latest revision).
- [Python SDK](https://github.com/modelcontextprotocol/python-sdk) - Official Python SDK for building MCP servers and clients.
- [TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) - Official TypeScript SDK for MCP servers and clients.
- [Go SDK](https://github.com/modelcontextprotocol/go-sdk) - Official Go SDK for MCP.
- [C# SDK](https://github.com/modelcontextprotocol/csharp-sdk) - Official C# SDK, maintained with Microsoft.
- [Kotlin SDK](https://github.com/modelcontextprotocol/kotlin-sdk) - Official Kotlin SDK for MCP.
- [Ruby SDK](https://github.com/modelcontextprotocol/ruby-sdk) - Official Ruby SDK for MCP.
- [Rust SDK](https://github.com/modelcontextprotocol/rust-sdk) - Official Rust SDK for MCP.

### Registries & Directories

- [Official MCP Registry](https://registry.modelcontextprotocol.io) - The official centralized registry/API for discovering public MCP servers.
- [modelcontextprotocol/registry](https://github.com/modelcontextprotocol/registry) - Source for the community-driven official registry service.
- [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) - The most popular community-curated list of MCP servers.
- [appcypher/awesome-mcp-servers](https://github.com/appcypher/awesome-mcp-servers) - Large curated catalog of production and experimental MCP servers.
- [wong2/awesome-mcp-servers](https://github.com/wong2/awesome-mcp-servers) - Curated list of MCP servers (companion to mcpservers.org).
- [punkpeye/awesome-mcp-clients](https://github.com/punkpeye/awesome-mcp-clients) - Curated list of apps and tools that act as MCP clients.
- [PulseMCP](https://www.pulsemcp.com) - Searchable directory of MCP servers and clients with usage data.
- [Glama MCP Directory](https://glama.ai/mcp/servers) - Browsable directory of MCP servers and clients.
- [mcpservers.org](https://mcpservers.org) - Web directory of MCP servers and clients.
- [Smithery](https://smithery.ai) - Registry and hosting platform indexing thousands of MCP servers with CLI install and remote endpoints.
- [Docker MCP Catalog](https://hub.docker.com/mcp) - Docker's curated catalog of verified, containerized MCP servers integrated with Docker Hub and Desktop.
- [awesome-mcp-gateways](https://github.com/e2b-dev/awesome-mcp-gateways) - Curated list of open-source and commercial MCP gateway products.

### Popular Servers

- [Reference servers](https://github.com/modelcontextprotocol/servers) - Anthropic's maintained reference servers: Filesystem, Fetch, Git, Memory, Sequential Thinking, Time, and more.
- [GitHub MCP Server](https://github.com/github/github-mcp-server) - GitHub's official MCP server for repos, issues, PRs, and workflows.
- [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) - Microsoft's Playwright MCP server for browser automation via accessibility snapshots.
- [upstash/context7](https://github.com/upstash/context7) - MCP server that delivers up-to-date library documentation to LLMs.
- [awslabs/mcp](https://github.com/awslabs/mcp) - Official collection of MCP servers for AWS services.
- [microsoft/mcp](https://github.com/microsoft/mcp) - Catalog of official Microsoft MCP server implementations.
- [Apify MCP](https://github.com/apify/apify-mcp-server) - Official Apify MCP server exposing thousands of Actors for web scraping and automation.
- [Atlassian Rovo MCP](https://www.atlassian.com/platform/remote-mcp-server) - Official Atlassian remote MCP server connecting Jira, Confluence, and Compass.
- [Chrome DevTools MCP](https://github.com/ChromeDevTools/chrome-devtools-mcp) - Official Chrome DevTools MCP server to control and inspect a live Chrome browser.
- [Cloudflare MCP](https://github.com/cloudflare/mcp-server-cloudflare) - Official Cloudflare MCP servers for Workers, KV, R2, D1, and observability.
- [Firecrawl MCP](https://github.com/firecrawl/firecrawl-mcp-server) - Official Firecrawl MCP server adding web scraping and search to LLM clients.
- [Grafana MCP](https://github.com/grafana/mcp-grafana) - Official Grafana MCP server for dashboards, datasources, alerts, and incidents.
- [Hugging Face MCP](https://github.com/huggingface/hf-mcp-server) - Official Hugging Face MCP server for searching models, datasets, Spaces, and docs.
- [Linear MCP](https://linear.app/docs/mcp) - Official hosted Linear MCP server for issues, projects, and product workflows.
- [Neon MCP](https://github.com/neondatabase/mcp-server-neon) - Official Neon MCP server for the Neon Management API and serverless PostgreSQL.
- [Notion MCP](https://github.com/makenotion/notion-mcp-server) - Official Notion MCP server for reading, writing, and searching Notion workspaces.
- [Sentry MCP](https://github.com/getsentry/sentry-mcp) - Official Sentry MCP server for querying issues, errors, and performance data via LLMs.
- [Stripe MCP](https://github.com/stripe/ai) - Stripe's official AI toolkit and hosted MCP server for payments, billing, and customer data.
- [Supabase MCP](https://github.com/supabase/mcp) - Official Supabase MCP server to manage and query PostgreSQL databases and projects.

### Clients & Tools

- [MCP Clients (official list)](https://modelcontextprotocol.io/clients) - Anthropic's list of applications that support MCP.
- [modelcontextprotocol/inspector](https://github.com/modelcontextprotocol/inspector) - Official visual testing and debugging tool for MCP servers.
- [FastMCP](https://github.com/jlowin/fastmcp) - Popular Pythonic framework for building MCP servers and clients.
- [mcp-use](https://github.com/mcp-use/mcp-use) - Open-source framework for building MCP apps and connecting LLMs to any MCP server.
- [MetaMCP](https://github.com/metatool-ai/metamcp) - MCP aggregator, orchestrator, middleware, and gateway in one self-hostable app.
- [mcpo](https://github.com/open-webui/mcpo) - Proxy that exposes any MCP server as an OpenAPI-compatible HTTP endpoint.
- [OpenAPI-MCP](https://github.com/gujord/OpenAPI-MCP) - Proxy that translates OpenAPI specs into MCP tools, resources, and prompts.
- [MCP-Scan](https://github.com/invariantlabs-ai/mcp-scan) - Security scanner detecting prompt injection, tool poisoning, and rug pulls in MCP servers.

## SDKs & Libraries

### Official SDKs

- [Python SDK](https://github.com/anthropics/anthropic-sdk-python) - Official Python client for the Claude Messages API (sync/async, Pydantic models, streaming).
- [TypeScript SDK](https://github.com/anthropics/anthropic-sdk-typescript) - Official TypeScript/JavaScript SDK for Node.js, Deno, Bun, and browsers.
- [Go SDK](https://github.com/anthropics/anthropic-sdk-go) - Official Go SDK with context-based cancellation and functional options.
- [Java SDK](https://github.com/anthropics/anthropic-sdk-java) - Official Java SDK using the builder pattern and `CompletableFuture` async.
- [Ruby SDK](https://github.com/anthropics/anthropic-sdk-ruby) - Official Ruby SDK with Sorbet types and streaming helpers.
- [PHP SDK](https://github.com/anthropics/anthropic-sdk-php) - Official PHP SDK using value objects and the builder pattern.
- [C#/.NET SDK](https://github.com/anthropics/anthropic-sdk-csharp) - Official C#/.NET SDK (.NET Standard 2.0+) with `IChatClient` integration.

> The Python and TypeScript SDKs also ship first-party `AnthropicBedrock` and `AnthropicVertex` clients for Amazon Bedrock and Google Vertex AI.

### Agent Frameworks

- [LangChain](https://github.com/langchain-ai/langchain) - Popular LLM app framework with first-class Claude support via `langchain-anthropic`.
- [LangGraph](https://github.com/langchain-ai/langgraph) - Stateful, graph-based agent orchestration from the LangChain team; works with Claude.
- [LlamaIndex](https://github.com/run-llama/llama_index) - Data/RAG framework for LLM apps with an Anthropic LLM integration.
- [CrewAI](https://github.com/crewAIInc/crewAI) - Role-based multi-agent orchestration framework; runs Claude via provider configuration.
- [AutoGen](https://github.com/microsoft/autogen) - Microsoft multi-agent conversation framework with an Anthropic client.
- [Pydantic AI](https://github.com/pydantic/pydantic-ai) - Type-safe Python agent framework from the Pydantic team with native Anthropic support.
- [DSPy](https://github.com/stanfordnlp/dspy) - Stanford framework for programming (not prompting) LLMs; supports Claude models.
- [Mastra](https://github.com/mastra-ai/mastra) - TypeScript agent framework (memory, workflows, tools) with an Anthropic provider.
- [Vercel AI SDK](https://github.com/vercel/ai) - TypeScript toolkit for AI apps/agents; Claude via `@ai-sdk/anthropic`.
- [smolagents](https://github.com/huggingface/smolagents) - Hugging Face's minimal code-agents library; uses Claude via LiteLLM.
- [Agno](https://github.com/agno-agi/agno) - High-performance, model-agnostic multi-agent framework with Anthropic support.
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel) - Microsoft AI orchestration SDK (.NET/Python/Java) with an Anthropic connector.
- [Spring AI](https://github.com/spring-projects/spring-ai) - Spring framework for AI apps with a dedicated Anthropic Claude starter.
- [Haystack](https://github.com/deepset-ai/haystack) - LLM/RAG framework by deepset with Anthropic generator and chat components.
- [Deep Agents](https://github.com/langchain-ai/deepagents) - LangChain's Claude Code-style agent harness with planning, sub-agents, and a virtual filesystem.
- [Google ADK](https://github.com/google/adk-python) - Google's open-source Agent Development Kit; runs Claude via its Anthropic integration or LiteLLM.
- [Inngest AgentKit](https://github.com/inngest/agent-kit) - TypeScript framework for multi-agent networks with deterministic routing and a built-in Anthropic provider.
- [Letta](https://github.com/letta-ai/letta) - Framework for stateful agents with long-term memory (formerly MemGPT); connects to Claude as a provider.
- [LiveKit Agents](https://github.com/livekit/agents) - Realtime voice-AI agent framework with a dedicated Anthropic Claude LLM plugin.
- [Rivet](https://github.com/Ironclad/rivet) - Ironclad's open-source visual programming environment for AI agents, with an Anthropic plugin.
- [Strands Agents](https://github.com/strands-agents/sdk-python) - AWS-built open-source agent SDK for Python and TypeScript with first-class Anthropic Claude support.
- [VoltAgent](https://github.com/VoltAgent/voltagent) - Observability-first TypeScript agent framework; swap in Anthropic Claude via config.

### Community Libraries

- [llm-anthropic](https://github.com/simonw/llm-anthropic) - Anthropic/Claude plugin for Simon Willison's `llm` CLI and Python library.
- [anthropix](https://github.com/lebrunel/anthropix) - Unofficial Elixir client for the Anthropic API, including tool use.
- [misanthropy](https://github.com/cortesi/misanthropy) - Idiomatic Rust bindings to the Anthropic API (streaming, tools, images, extended thinking).
- [clust](https://github.com/mochi-neko/clust) - Unofficial Rust client for the Anthropic/Claude API.
- [Anthropic.SDK](https://github.com/tghamm/Anthropic.SDK) - Feature-rich community .NET/C# library (streaming, tools, batching, Semantic Kernel integration).
- [BAML](https://github.com/BoundaryML/baml) - DSL for typed, testable LLM functions with guaranteed structured outputs; supports Claude as a provider.
- [Cognee](https://github.com/topoteretes/cognee) - Open-source AI memory platform building self-hosted knowledge graphs, with Claude Code and MCP integrations.
- [Graphiti](https://github.com/getzep/graphiti) - Temporal knowledge-graph memory for agents (open-source core of Zep); works with Anthropic Claude.
- [Mem0](https://github.com/mem0ai/mem0) - Universal memory layer for AI agents with Anthropic support and a Claude Agent SDK integration.

### Gateways & Observability

- [LiteLLM](https://github.com/BerriAI/litellm) - Open-source SDK/proxy giving an OpenAI-compatible interface to 100+ providers including Anthropic.
- [OpenRouter](https://openrouter.ai) - Unified API gateway routing to hundreds of models, including the Claude family, through one endpoint.
- [Portkey Gateway](https://github.com/Portkey-AI/gateway) - Fast open-source AI gateway with guardrails and routing to many LLMs including Claude.
- [Langfuse](https://github.com/langfuse/langfuse) - Open-source LLM observability, tracing, and evals with Anthropic/Claude support.
- [Helicone](https://github.com/Helicone/helicone) - Open-source LLM observability and monitoring proxy supporting the Anthropic API.
- [Instructor](https://github.com/567-labs/instructor) - Structured (Pydantic) outputs from LLMs across providers, including Anthropic/Claude.
- [Arize Phoenix](https://github.com/Arize-ai/phoenix) - Open-source LLM tracing and evaluation built on OpenTelemetry, with Anthropic and Claude Agent SDK instrumentation.
- [Bifrost](https://github.com/maximhq/bifrost) - High-performance open-source LLM gateway (by Maxim AI) that is a drop-in replacement for the Anthropic SDKs.
- [Braintrust](https://www.braintrust.dev) - Eval and observability platform that calls and traces Anthropic Claude, including streaming, caching, and tool use.
- [Cloudflare AI Gateway](https://developers.cloudflare.com/ai-gateway/) - Edge AI gateway adding caching, rate limiting, analytics, and logging in front of providers including Anthropic.
- [OpenLLMetry](https://github.com/traceloop/openllmetry) - OpenTelemetry-based LLM observability (by Traceloop) shipping a dedicated Anthropic instrumentation package.
- [Opik](https://github.com/comet-ml/opik) - Open-source LLM observability and evaluation platform (by Comet) with a one-line Anthropic integration.
- [Promptfoo](https://github.com/promptfoo/promptfoo) - Open-source tool for testing, evaluating, and red-teaming LLM apps, with Anthropic Claude among supported providers.

## AI Coding Tools

- [Aider](https://aider.chat) - Terminal-based AI pair programmer with automatic Git commits; Claude models rank among its top backends.
- [Amp](https://ampcode.com) - Sourcegraph's agentic coding tool for the terminal and editors, powered by frontier models including Claude.
- [Augment Code](https://www.augmentcode.com) - Agentic software-development platform whose orchestrated agents run on Claude Sonnet and Opus.
- [Cline](https://cline.bot) - Open-source autonomous coding agent for VS Code and JetBrains with first-class Claude support.
- [Codebuff](https://www.codebuff.com) - Open-source multi-agent coding agent that runs Claude and other models via OpenRouter.
- [Continue](https://continue.dev) - Open-source AI assistant and agent for VS Code and JetBrains, configurable with Anthropic Claude.
- [Crush](https://github.com/charmbracelet/crush) - Charm's terminal coding agent supporting Anthropic Claude and other providers.
- [Cursor](https://cursor.com) - AI-native code editor offering Claude Opus and Sonnet as selectable model backends.
- [Goose](https://github.com/block/goose) - Block's open-source AI agent for coding and workflows, supporting Claude among 15+ providers.
- [Kilo Code](https://github.com/Kilo-Org/kilocode) - Open-source agentic coding extension (VS Code, JetBrains, CLI) supporting Claude Opus/Sonnet.
- [Kiro](https://kiro.dev) - AWS's spec-driven agentic IDE, CLI, and web app powered by Anthropic Claude models.
- [OpenCode](https://opencode.ai) - Open-source, provider-agnostic AI coding agent for the terminal with first-class Claude support.
- [Plandex](https://github.com/plandex-ai/plandex) - Open-source terminal AI coding agent for large, real-world projects, with Anthropic Claude support.
- [Warp](https://www.warp.dev) - Agentic development environment and terminal that runs Claude and pairs with Claude Code.
- [Windsurf](https://windsurf.com) - Agentic AI IDE that runs multi-step coding tasks on Claude and other models.
- [Zed](https://zed.dev) - High-performance open-source editor with built-in agentic features that support Claude.

## Chat Clients & Apps

- [AnythingLLM](https://anythingllm.com) - All-in-one desktop and Docker AI app with RAG and agents, supporting Anthropic Claude.
- [big-AGI](https://big-agi.com) - Expert multi-model AI workspace with direct Anthropic integration for Claude Opus/Sonnet.
- [Cherry Studio](https://github.com/CherryHQ/cherry-studio) - Open-source desktop AI workstation unifying 300+ models, including Anthropic Claude.
- [Chatbox](https://chatboxai.app) - Cross-platform AI client (open-source community edition) supporting Anthropic Claude models.
- [ChatWise](https://chatwise.app) - Fast, privacy-friendly desktop AI chat client supporting Claude and Claude Pro/Max subscriptions.
- [Jan](https://jan.ai) - Open-source, offline-first desktop ChatGPT alternative that connects to Claude via the Anthropic API.
- [LibreChat](https://librechat.ai) - Open-source multi-provider chat platform with native Claude support plus agents, MCP, and artifacts.
- [Lobe Chat](https://github.com/lobehub/lobe-chat) - Open-source modern chat framework supporting Anthropic Claude among many providers.
- [Msty](https://msty.ai) - Privacy-focused desktop AI chat app for local and cloud models, including Anthropic Claude.
- [Open WebUI](https://openwebui.com) - Self-hosted, extensible chat UI that connects to Claude via Anthropic and OpenAI-compatible APIs.
- [TypingMind](https://www.typingmind.com) - Bring-your-own-key chat frontend for Claude and other LLMs.

## Notable Open-Source Projects

- [opcode](https://github.com/winfunc/opcode) - Desktop GUI and toolkit for managing Claude Code sessions and custom agents (formerly Claudia).
- [OpenHands](https://github.com/OpenHands/OpenHands) - Open-source autonomous software-engineering agent platform that runs on Claude (and other) models.
- [STORM](https://github.com/stanford-oval/storm) - Stanford's LLM knowledge-curation system that writes cited, Wikipedia-style reports; works with Claude via LiteLLM.
- [SWE-agent](https://github.com/SWE-agent/SWE-agent) - Princeton/Stanford agent that auto-fixes GitHub issues, reaching strong SWE-bench results using Claude models.
- [Task Master](https://github.com/eyaltoledano/claude-task-master) - AI-powered task-management system that drops into Claude Code, Cursor, and other agents.

## Learning & Prompting

### Guides

- [Best practices for Claude Code](https://code.claude.com/docs/en/best-practices) - Anthropic's official guide to agentic coding workflows, CLAUDE.md, context management, and tool setup.
- [Building agents with the Claude Agent SDK](https://claude.com/blog/building-agents-with-the-claude-agent-sdk) - Anthropic's guide to the gather-context, act, and verify agent loop built on the Agent SDK.
- [Code execution with MCP](https://www.anthropic.com/engineering/code-execution-with-mcp) - Anthropic engineering post on cutting token use by having agents write code to call MCP tools.
- [Context windows](https://platform.claude.com/docs/en/build-with-claude/context-windows) - Official reference on how the context window, extended thinking, and tool use consume tokens.
- [Effective context engineering for AI agents](https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents) - Anthropic engineering guide on curating the context window to counter context rot in agents.
- [Effective harnesses for long-running agents](https://www.anthropic.com/engineering/effective-harnesses-for-long-running-agents) - Anthropic engineering guide to sustaining agent progress across many context windows and sessions.
- [Prompt caching](https://platform.claude.com/docs/en/build-with-claude/prompt-caching) - Official guide to caching prompt prefixes to cut latency and cost on repeated context.
- [Writing effective tools for AI agents](https://www.anthropic.com/engineering/writing-tools-for-agents) - Anthropic engineering guide on designing, evaluating, and optimizing the tools that agents call.

### Prompt Engineering

- [Prompt engineering overview](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/overview) - Anthropic's official hub on clarity, examples, XML structure, roles, chaining, and thinking.
- [Prompting best practices](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/claude-prompting-best-practices) - Official model-specific guidance tuned for Claude's latest models.
- [Interactive Prompt Engineering Tutorial](https://github.com/anthropics/prompt-eng-interactive-tutorial) - Official hands-on course with exercises, from basics to advanced techniques.
- [Prompt Engineering Guide (DAIR.AI)](https://www.promptingguide.ai/) - Popular open community guide with dedicated Claude/Anthropic sections.
- [Claude Code prompt library](https://code.claude.com/docs/en/prompt-library) - Copy-paste prompts for Claude Code tagged by task and role.

### Courses & Tutorials

- [Anthropic Academy](https://www.anthropic.com/learn/build-with-claude) - Anthropic's official learning hub organizing courses, guides, quickstarts, and docs.
- [Anthropic Courses (Skilljar)](https://anthropic.skilljar.com) - Free official course catalog including Claude 101 and Building with the Claude API.
- [anthropics/courses](https://github.com/anthropics/courses) - Anthropic's open educational repo: API fundamentals, prompt engineering, evaluations, and tool use.
- [Claude Cookbooks](https://github.com/anthropics/claude-cookbooks) - Official runnable notebooks for tool use, multimodal, evaluation, RAG, and agents.
- [Claude Quickstarts](https://github.com/anthropics/claude-quickstarts) - Deployable starter projects (customer-support agent, computer use, coding agent).
- [Claude Code: A Highly Agentic Coding Assistant](https://www.deeplearning.ai/courses/claude-code-a-highly-agentic-coding-assistant) - DeepLearning.AI short course with Anthropic's Elie Schoppik on real-world Claude Code workflows.
- [Agent Skills with Anthropic](https://www.deeplearning.ai/courses/agent-skills-with-anthropic) - DeepLearning.AI short course on authoring and deploying Agent Skills, built with Anthropic.
- [MCP: Build Rich-Context AI Apps with Anthropic](https://www.deeplearning.ai/courses/mcp-build-rich-context-ai-apps-with-anthropic) - DeepLearning.AI short course on building, connecting, and deploying MCP servers and clients.

### Reading & Research

- [Building Effective Agents](https://www.anthropic.com/engineering/building-effective-agents) - Widely cited engineering guide on agent vs. workflow patterns and keeping designs simple.
- [Constitutional AI: Harmlessness from AI Feedback](https://arxiv.org/abs/2212.08073) - Anthropic's foundational paper on training models with a principle-based constitution.
- [Claude's Constitution](https://www.anthropic.com/news/claude-new-constitution) - Anthropic's document detailing Claude's intended values and behavior, released under CC0.
- [Mapping the Mind of a Large Language Model](https://www.anthropic.com/research/mapping-mind-language-model) - Interpretability work identifying millions of features inside Claude via dictionary learning.
- [Tracing the Thoughts of a Language Model](https://www.anthropic.com/research/tracing-thoughts-language-model) - Circuit-tracing research revealing how Claude internally computes and reasons.
- [Introducing Computer Use](https://www.anthropic.com/news/3-5-models-and-computer-use) - Announcement of Claude operating a computer by viewing the screen and controlling cursor and keyboard.
- [Anthropic Engineering Blog](https://www.anthropic.com/engineering) - Deep dives on agents, context engineering, tool use, and production practices.

### Newsletters, Blogs & Video

- [Import AI](https://importai.substack.com/) - Anthropic co-founder Jack Clark's weekly newsletter analyzing frontier AI research and policy.
- [Interconnects](https://www.interconnects.ai/) - Nathan Lambert's newsletter with sharp analysis of frontier-lab and open-model research.
- [Latent Space](https://www.latent.space/) - High-signal AI Engineer newsletter and podcast by swyx & Alessio, frequently featuring Anthropic builders.
- [Simon Willison's Weblog - Claude tag](https://simonwillison.net/tags/claude/) - Detailed, hands-on commentary on every major Claude and Anthropic release.
- [The Anthropic Stack](https://theanthropicstack.com/) - Practitioner newsletter on building with Claude, MCP, and AI agents.
- [Anthropic on YouTube](https://www.youtube.com/@anthropic-ai) - Anthropic's official channel with product demos, research talks, and Claude tutorials.
- [Claude Developer Newsletter](https://claude.com/newsletter/developers) - Anthropic's official developer email with announcements and best practices.
- [IndyDevDan](https://www.youtube.com/@indydevdan) - Popular YouTube channel with opinionated, spec-driven Claude Code and agentic-engineering walkthroughs.
- [Chain of Thought (Every)](https://every.to/chain-of-thought) - Dan Shipper's column and AI & I podcast on building with AI, with frequent Claude and Anthropic coverage.

### Communities

- [Claude Community](https://claude.com/community) - Anthropic's official community hub linking its Discord, Reddit, and ambassador programs.
- [r/ClaudeAI](https://www.reddit.com/r/ClaudeAI/) - Large community subreddit for Claude discussion, tips, and comparisons.
- [r/ClaudeCode](https://www.reddit.com/r/ClaudeCode/) - Active subreddit focused on Claude Code workflows, tips, tooling, and troubleshooting.

## Benchmarks & Leaderboards

- [SWE-bench](https://www.swebench.com/) - Benchmark measuring real GitHub issue resolution, where Claude models rank among the top performers.
- [Aider Polyglot Leaderboard](https://aider.chat/docs/leaderboards/) - Multilingual code-editing benchmark that ranks Claude models.
- [Terminal-Bench](https://www.tbench.ai/leaderboard) - Benchmark for agents on real terminal tasks, evaluating Claude models.
- [Arena (formerly LMArena / Chatbot Arena)](https://arena.ai) - Human-preference LLM leaderboard that includes Claude models.
- [GAIA Leaderboard](https://huggingface.co/spaces/gaia-benchmark/leaderboard) - General AI assistant benchmark where Claude-based agents are evaluated.
- [Artificial Analysis](https://artificialanalysis.ai) - Independent LLM benchmarking site tracking Claude across quality, speed, and price.
- [ARC-AGI (ARC Prize)](https://arcprize.org) - Abstract-reasoning benchmark and prize whose public leaderboard includes Claude models.
- [Design Arena](https://www.designarena.ai) - Crowdsourced leaderboard for AI-generated design and UI where Claude models compete.
- [LiveBench](https://livebench.ai) - Contamination-resistant LLM benchmark with monthly-rotating questions where Claude models are ranked.
- [LiveCodeBench](https://livecodebench.github.io) - Contamination-free coding benchmark using post-cutoff problems, evaluating Claude and other models.
- [tau-bench](https://github.com/sierra-research/tau-bench) - Sierra's benchmark for tool-agent-user interaction in real-world domains, with Claude among evaluated models.
- [tau2-bench](https://github.com/sierra-research/tau2-bench) - Sierra's dual-control agent benchmark for real-world tool use, evaluating Claude models.
- [WebArena](https://webarena.dev) - Realistic, reproducible web-environment benchmark for autonomous agents, with Claude among evaluated models.

## Contributing

Contributions are welcome - a single great link is a perfectly good pull request. Please read the [contribution guidelines](.github/CONTRIBUTING.md) first. In short: keep entries relevant to Claude, high quality, non-redundant, and formatted as `- [Name](https://url) - short factual description.` Translations live in the `translations/` folder.
