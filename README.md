# Building AI-native infrastructure for the BEAM ecosystem.

> *If I solve a problem twice, it becomes open source.*

I design and build production-grade infrastructure for Elixir systems — OTP orchestration, LLM runtimes, AI-assisted development tooling and distributed runtime utilities.

Most of what I build starts as a personal need inside real systems and ends up as open source libraries on Hex.

[LinkedIn](https://linkedin.com/in/lorenzosanchez-fraile) · [hex.pm](https://hex.pm/users/lorenzo-sf) · [Email](mailto:sanchezfrailelorenzo@gmail.com)

---

## What I focus on

- AI-native runtime systems on Elixir (LLM orchestration, tooling, MCP)
- OTP-first distributed systems (reliability, concurrency, supervision trees)
- Developer infrastructure for the BEAM ecosystem
- Small, composable libraries over large frameworks

---

## Core projects

### 🕯️ Candil — LLM runtime for Elixir
Unified runtime for local and cloud LLMs (llama.cpp, OpenAI, Anthropic, Ollama).

Handles streaming (SSE), context management, backend abstraction and runtime orchestration on top of OTP.

---

### 🏛️ Delfos — AI code intelligence server (MCP)
MCP server for AI-assisted development tools (Claude Desktop, Cursor, Zed).

Provides codebase indexing, hybrid search (vector + BM25 + graph), real-time updates, and impact analysis across large repositories.

---

### ⚡ Arrea — OTP orchestration layer
Reliable process orchestration built on OTP primitives.

Includes circuit breakers, retry policies, telemetry integration and dynamic worker supervision.

---

## Ecosystem

A set of focused libraries built for real production constraints:

- [Alaja](https://github.com/Lorenzo-SF/alaja) — CLI framework with DSL macros and terminal rendering
- [Flotilla](https://github.com/Lorenzo-SF/flotilla) — LiveView architecture layer (model / update / view)
- [Válvula](https://github.com/Lorenzo-SF/valvula) — Token bucket rate limiter built on ETS
- [Apero](https://github.com/Lorenzo-SF/apero) — Developer utilities (files, git, HTTP, retry, cache)
- [Pote](https://github.com/Lorenzo-SF/pote) — Color manipulation and palette engine
- [Botica](https://github.com/Lorenzo-SF/botica) — Parallel system health checks
- [Batamanta](https://github.com/Lorenzo-SF/batamanta) — Self-contained Elixir application packaging

---

## Experience

Core Team — Truedat (Bluetab / IBM)

Enterprise data governance platform used in banking, insurance, telecom and retail sectors.

Built and maintained Elixir-based distributed microservice systems in production environments.

---

## Stack

Elixir · OTP · Phoenix · Ecto · PostgreSQL · Redis · Elasticsearch · Rust NIFs · Docker