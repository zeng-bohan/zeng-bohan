# Bohan Zeng · 曾博涵

Engineer in the Java and AI-agent ecosystems — RPC frameworks, agent runtimes, and the checkpoint/storage internals underneath them.

## Open source

**Merged**

| Project | Contribution |
| --- | --- |
| [bytedance/deer-flow](https://github.com/bytedance/deer-flow) | Checkpoint-retention deletion contract ([#5255](https://github.com/bytedance/deer-flow/pull/5255)) |
| [agentic-spring-ai](https://github.com/agentic-spring-ai/agentic-spring-ai) | Agent-tool instruction dedup ([#78](https://github.com/agentic-spring-ai/agentic-spring-ai/pull/78)), stream-cancellation checkpoint rollback ([#79](https://github.com/agentic-spring-ai/agentic-spring-ai/pull/79)), reasoning-chunk markers ([#80](https://github.com/agentic-spring-ai/agentic-spring-ai/pull/80)) |
| [alibaba/spring-ai-alibaba](https://github.com/alibaba/spring-ai-alibaba) | Serializer round-trip regression tests ([#4926](https://github.com/alibaba/spring-ai-alibaba/pull/4926)) |

**In review**

- [apache/dubbo](https://github.com/apache/dubbo) — reference-bean naming strategy against `@Resource` by-name conflicts ([#16438](https://github.com/apache/dubbo/pull/16438))
- [bytedance/deer-flow](https://github.com/bytedance/deer-flow) — checkpoint-retention service ([#5308](https://github.com/bytedance/deer-flow/pull/5308)), serve.sh fail-fast ([#5180](https://github.com/bytedance/deer-flow/pull/5180)), content-addressed blob-store contract ([#5361](https://github.com/bytedance/deer-flow/pull/5361)) — the ongoing storage campaign on [#4189](https://github.com/bytedance/deer-flow/issues/4189)
- [alibaba/spring-ai-alibaba](https://github.com/alibaba/spring-ai-alibaba) — agentic RAG multi-agent example ([#4902](https://github.com/alibaba/spring-ai-alibaba/pull/4902))

Also reported a checkpoint-storage regression on [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope) ([#2504](https://github.com/agentscope-ai/agentscope/issues/2504)), fixed upstream by community PR [#2526](https://github.com/agentscope-ai/agentscope/pull/2526).

## Projects

| Repository | What it is |
| --- | --- |
| [sentiment-analysis-agents](https://github.com/zeng-bohan/sentiment-analysis-agents) | Multi-agent public-sentiment analysis: parallel agents, SSE task progress, HTML/Markdown/PDF reporting |
| [enterprise-rag-qa](https://github.com/zeng-bohan/enterprise-rag-qa) | Document-grounded RAG service: hybrid retrieval with reranking, streaming citations, evaluated (Recall@1 87.4% / Faithfulness 94.1%) |
| [agent-orchestration-framework](https://github.com/zeng-bohan/agent-orchestration-framework) | Lightweight DAG/StateGraph agent framework with SQLite checkpoint resume and an MCP tool registry |
| [room-layout-solver](https://github.com/zeng-bohan/room-layout-solver) | Deterministic rectangle-packing solver for polygon rooms: wall-flush placement and door-clearance constraints |
| [zengbohan-skill](https://github.com/zeng-bohan/zengbohan-skill) | A five-stage development pipeline for AI coding agents, shipped as a single installable skill |
