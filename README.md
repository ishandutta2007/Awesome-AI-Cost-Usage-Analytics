# Awesome-AI-Cost-Usage-Analytics

# Top AI Cost & Usage Analytics Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on AI Spend Attribution, Token & Quota Analytics, AI Proxy Gateways, Coding-Agent Usage Monitors & FinOps for LLMs*  
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Cost & Usage Analytics**. These tools meter prompt and completion token consumption across multi-provider LLM APIs, track coding-agent subscription quotas and burn rates (`Claude Code`, `Codex`, `Cursor`), enforce team/tenant budget alerts, and optimize AI FinOps via semantic caching and model routing.

**Examples** include Helicone, Langfuse, Portkey, PromptLayer, Martian, LiteLLM Proxy, Keywords AI, BerriAI, Cloudflare AI Gateway, Datadog LLM Observability, and claude-usage/claude-usage-monitor (the category leaders). 

**Open-source emphasis**: This section is heavily expanded with every major active project for real-time CLI/TUI/menu-bar usage monitors, self-hosted LLM billing & analytics gateways, OpenTelemetry FinOps dashboards, and programmatic token-cost calculators — ideal for FinOps teams, AI platform engineers, and developers tracking token usage across cloud and local workflows.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Helicone](https://helicone.ai)**  
  Proxy-based AI gateway and cost analytics platform offering real-time token metering, per-user/customer spend attribution, semantic caching savings reports, and custom budget alerts.

- **[Langfuse Cloud](https://langfuse.com)**  
  Managed cloud deployment of the open-source LLM engineering platform providing automated model pricing tables, trace- and session-level cost rollups, and usage analytics.

- **[Portkey](https://portkey.ai)**  
  Enterprise AI gateway and FinOps suite featuring virtual API keys, granular spend caps, automatic fallback routing, semantic caching, and unified cost/usage dashboards.

- **[Keywords AI](https://keywordsai.co)**  
  Unified LLM gateway and monitoring platform delivering a single OpenAI-compatible endpoint with real-time cost breakdown, latency analytics, user spend limits, and caching.

- **[Cloudflare AI Gateway](https://cloudflare.com)**  
  Managed edge proxy sitting between applications and AI providers to provide unified request analytics, token/cost estimation, response caching, and rate limiting.

- **[Datadog LLM Observability](https://datadoghq.com)**  
  Enterprise cloud monitoring solution tracking end-to-end LLM and agent traces, token consumption, operational spend, latency bottlenecks, and drift metrics.

- **[PromptLayer](https://promptlayer.com)**  
  Prompt management and LLM analytics platform offering request history logging, token-per-template cost breakdowns, latency tracking, and A/B test evaluations.

- **[Martian](https://withmartian.com)**  
  Dynamic model-routing and cost-optimization API platform that automatically dispatches prompts to the lowest-cost LLM capable of meeting quality benchmarks.

- **[BerriAI (LiteLLM Cloud)](https://litellm.ai)**  
  Managed enterprise deployment of LiteLLM Proxy providing centralized spend governance, team/project chargebacks, SSO, and multi-provider quota enforcement.


## Open-Source GitHub Projects

- **[claude-usage/claude-usage-monitor](https://github.com)**  
  Open-source usage monitoring tool built for tracking real-time Claude and Claude Code token consumption, session window limits, burn rates, and usage analytics.

- **[LiteLLM Proxy (`BerriAI/litellm`)](https://github.com)**  
  Leading open-source (`MIT`) AI gateway and Python SDK providing a unified OpenAI-compatible proxy across 100+ LLMs with virtual keys, team/user budget caps, and real-time spend analytics.

- **[Langfuse (`langfuse/langfuse`)](https://github.com)**  
  Self-hostable open-source LLM engineering platform featuring customizable model token pricing, hierarchical trace/session cost aggregation, and prompt-level usage dashboards.

- **[Helicone (`Helicone/helicone`)](https://github.com)**  
  Open-source (`Apache-2.0`) AI gateway and observability proxy enabling self-hosted request logging, token/cost metrics, caching savings tracking, and rate limiting.

- **[TensorZero (`tensorzero/tensorzero`)](https://github.com)**  
  Open-source (`Apache-2.0`) industrial-grade LLM gateway, observability, and optimization engine written in Rust with ClickHouse-backed token, latency, and cost analytics.

- **[One-API / New-API (`MartialBE/one-api` / `Calcium-Ion/new-api`)](https://github.com)**  
  Popular open-source (`MIT`) multi-provider LLM key aggregation and billing gateway featuring token quota management, user groups, rate limiting, and detailed consumption logs.

- **[Portkey AI Gateway (`Portkey-AI/gateway`)](https://github.com)**  
  Ultra-fast open-source (`MIT`) AI gateway written in TypeScript providing multi-provider routing, automatic retries, token/cost metadata headers, and lightweight self-hosting.

- **[OpenLIT (`openlit/openlit`)](https://github.com)**  
  Open-source (`Apache-2.0`) OpenTelemetry-native AI observability and FinOps platform providing zero-code token/cost tracking, GPU utilization metrics, and customizable pricing files.

- **[OpenLLMetry (`traceloop/openllmetry`)](https://github.com)**  
  Open-source (`Apache-2.0`) OpenTelemetry instrumentation extensions exporting standardized `gen_ai.usage.input_tokens` and `output_tokens` metrics to Prometheus, Grafana, or Datadog.

- **[ccusage (`ryoppippi/ccusage`)](https://github.com)**  
  Fast open-source (`MIT`) CLI analyzer for parsing local Claude Code JSONL logs to display daily, monthly, and session-level token usage, prompt cache hit rates, and equivalent USD spend.

- **[Claude-Code-Usage-Monitor (`Maciek-roboblog/Claude-Code-Usage-Monitor`)](https://github.com)**  
  Real-time open-source (`MIT`) terminal dashboard built with Rich that monitors Claude Code token burn velocity, 5-hour session reset countdowns, plan limits, and predictive exhaustion warnings.

- **[claude-usage (`phuryn/claude-usage`)](https://github.com)**  
  Open-source macOS menu-bar utility and CLI monitor built for tracking real-time Claude Code and Claude subscription token consumption, rolling quota burn rates, and session costs.

- **[TokenCost (`AgentOps-AI/tokencost`)](https://github.com)**  
  Lightweight open-source (`MIT`) Python utility library for calculating exact USD prompt and completion costs across hundreds of commercial and hosted LLM models.

- **[Bifrost (`maximhq/bifrost`)](https://github.com)**  
  High-throughput open-source (`Apache-2.0`) AI gateway built in Go featuring sub-millisecond overhead, virtual key budgets, fallback routing, and OpenTelemetry usage metrics.

- **[BricksLLM (`bricks-cloud/BricksLLM`)](https://github.com)**  
  Open-source (`MIT`) cloud-native AI gateway written in Go providing enterprise API key management, granular spend limits, rate policies, and Prometheus usage telemetry.

- **[RouteLLM (`lm-sys/RouteLLM`)](https://github.com)**  
  Open-source (`Apache-2.0`) framework from LMSYS for training and serving cost-aware LLM routers that dynamically dispatch simple queries to cheaper models while preserving quality.

- **[GPTCache (`zilliztech/GPTCache`)](https://github.com)**  
  Open-source (`MIT`) semantic caching library that intercepts repetitive LLM prompts and serves cached completions to dramatically reduce API token expenditure.

### Additional Strong Open-Source Options

- **[Lunary (`lunary-ai/lunary`)](https://github.com)** and **[Opik (`comet-ml/opik`)](https://github.com)** for self-hosted LLM observability suites with built-in per-user, per-agent, and per-trace cost analytics.
- **[tiktoken (`openai/tiktoken`)](https://github.com)** and **[Tokenizers (`huggingface/tokenizers`)](https://github.com)** for high-speed pre-flight token counting and context budget enforcement before calling paid APIs.
- **[Grafana + Prometheus + OpenTelemetry Collector](https://github.com)** for building custom real-time FinOps token burn and quota dashboards from standardized OpenTelemetry `gen_ai` metrics.
- **[hoangsonww/Claude-Code-Agent-Monitor](https://github.com)** for a web-based real-time dashboard monitoring Claude Code sub-agent sessions, tool calls, and token spend.
- **[vLLM (`vllm-project/vllm`)](https://github.com)** and **[Ollama (`ollama/ollama`)](https://github.com)** for self-hosting open-weight models with Prometheus token-throughput metrics to eliminate per-token cloud API costs.

**Frameworks for building custom systems**: Combine **LiteLLM Proxy** or **TensorZero** (for multi-provider budget caps & routing) with **Langfuse / OpenLIT** (for trace-level FinOps attribution), **claude-usage/claude-usage-monitor / ccusage** (for local coding-agent quota monitoring), and **TokenCost** for end-to-end AI cost and usage analytics.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
