# Building an ecosystem of Elixir developer tools.

> *If I solve a problem twice, it probably becomes open source.*

I build small, focused libraries for the BEAM ecosystem — OTP orchestration, LLM inference, CLI frameworks, LiveView tooling and developer productivity. When something doesn't exist in Elixir and I need it, I build it.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/lorenzosanchez-fraile)
[![hex.pm](https://img.shields.io/badge/hex.pm-6B3FA0?style=flat&logo=erlang&logoColor=white)](https://hex.pm/users/lorenzo-sf)
[![Email](https://img.shields.io/badge/email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:sanchezfrailelorenzo@gmail.com)

---

## Highlights

```
📦  10 open source libraries published on hex.pm
⚡  OTP-first architecture — GenServers, Supervisors, ETS, Telemetry
🤖  MCP servers and LLM inference for the BEAM
🏢  Enterprise-scale Elixir systems in production (Bluetab / IBM)
🦾  Elixir NIFs with Rust via Rustler
```

---

## Featured projects

### ⚡ [Arrea](https://github.com/Lorenzo-SF/arrea) — OTP async process orchestrator
Circuit breaker (open/closed/half-open, atomic decision), configurable retry policies,
telemetry integration and ephemeral workers under DynamicSupervisor.
Built because Elixir needed a proper orchestrator without the overhead of a full queue system.

### 🕯️ [Candil](https://github.com/Lorenzo-SF/candil) — LLM inference for Elixir
Run local models via llama.cpp (GenServer + OS Port) or remote via OpenAI, Anthropic and Ollama —
same interface, any backend. SSE streaming, context window management, ETS registry, OS/GPU detection.

### 🏛️ [Delfos](https://github.com/Lorenzo-SF/delfos) — MCP server for AI-assisted coding
Indexes your codebase and exposes it to AI assistants (Claude Desktop, Cursor, Zed) via MCP.
Hybrid search (vector + BM25 + graph with RRF), 40+ languages via Tree-sitter NIFs,
real-time re-indexing, BFS impact analysis and technical debt metrics.

---

## The ecosystem

| Project | What it does |
|---------|-------------|
| [**Alaja**](https://github.com/Lorenzo-SF/alaja) | Declarative CLI framework — DSL macros, terminal rendering (tables, boxes, gradients, images) |
| [**Flotilla**](https://github.com/Lorenzo-SF/flotilla) | Declarative Phoenix LiveView — Elm Architecture (model → update → view), 15+ VDOM components |
| [**Válvula**](https://github.com/Lorenzo-SF/valvula) | Zero-dependency token bucket rate limiter on OTP/ETS |
| [**Apero**](https://github.com/Lorenzo-SF/apero) | Utility toolkit — file ops, Git, Docker, crypto, HTTP, retry, ETS cache |
| [**Pote**](https://github.com/Lorenzo-SF/pote) | Color library — parsing, conversion, palettes, xterm256, HSL, CMYK |
| [**Botica**](https://github.com/Lorenzo-SF/botica) | Health checks and environment diagnostics with parallel execution |
| [**Batamanta**](https://github.com/Lorenzo-SF/batamanta) | Package Elixir apps as self-contained executables with embedded ERTS |

---

## By day

Core Team at **[Truedat](https://www.truedat.io)** (Bluetab / IBM) —
enterprise open source Data Governance platform used by multinationals in banking,
insurance, telecoms and retail.
11 Elixir microservices · REST + GraphQL · PostgreSQL · Elasticsearch · Redis · React.js

---

## Primary stack

`Elixir/OTP` `Phoenix` `Ecto` `PostgreSQL` `React.js` `Elasticsearch` `Redis` `Docker`
