<div align="center">

# Building AI-native infrastructure for the BEAM ecosystem.

*If I solve a problem twice, it becomes open source.*

I design and build production-grade infrastructure for Elixir systems —
OTP orchestration, LLM runtimes, AI-assisted development tooling and distributed runtime utilities.

Most of what I build starts as a personal need inside real systems and ends up as open source libraries on Hex.

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/lorenzosanchez-fraile)
[![hex.pm](https://img.shields.io/badge/hex.pm-6B3FA0?style=flat-square&logo=erlang&logoColor=white)](https://hex.pm/users/lorenzo-sf)

</div>

<br/>

---

## What I focus on

```
⚡  OTP-first distributed systems       →  reliability, concurrency, supervision trees
🤖  AI-native runtime systems           →  LLM orchestration, MCP servers, tooling
🏗️  Developer infrastructure for BEAM  →  composable libraries, not monolithic frameworks
```

---

## Core projects

<table>
<tr>
<td width="50%" valign="top">

### 🕯️ [Candil](https://github.com/Lorenzo-SF/candil)
**LLM runtime for Elixir**

Unified runtime for local and cloud LLMs.
Supports llama.cpp, OpenAI, Anthropic and Ollama
through a single interface — streaming, context
management and OTP-native orchestration included.

![Elixir](https://img.shields.io/badge/Elixir-4B275F?style=flat-square&logo=elixir&logoColor=white)
![OTP](https://img.shields.io/badge/OTP-red?style=flat-square)
![LLM](https://img.shields.io/badge/LLM-8B5CF6?style=flat-square)

</td>
<td width="50%" valign="top">

### 🏛️ [Delfos](https://github.com/Lorenzo-SF/delfos)
**AI code intelligence server (MCP)**

MCP server for AI-assisted development tools
(Claude Desktop, Cursor, Zed). Hybrid search
(vector + BM25 + graph), 40+ languages via
Tree-sitter NIFs, real-time re-indexing.

![Elixir](https://img.shields.io/badge/Elixir-4B275F?style=flat-square&logo=elixir&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-0D9488?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-F59E0B?style=flat-square)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚡ [Arrea](https://github.com/Lorenzo-SF/arrea)
**OTP orchestration layer**

Reliable async process orchestration built on
OTP primitives — circuit breakers, retry policies,
telemetry integration and DynamicSupervisor
with independent registries per concern.

![Elixir](https://img.shields.io/badge/Elixir-4B275F?style=flat-square&logo=elixir&logoColor=white)
![OTP](https://img.shields.io/badge/OTP-red?style=flat-square)
![Telemetry](https://img.shields.io/badge/Telemetry-3B82F6?style=flat-square)

</td>
<td width="50%" valign="top">

### 🎨 [Alaja](https://github.com/Lorenzo-SF/alaja)
**CLI framework & terminal rendering kit**

Declarative CLI framework with DSL macros
(command, flag, argument). Full terminal rendering:
tables, boxes, progress bars, gradients and
images (Kitty/iTerm2/Sixel/ASCII).

![Elixir](https://img.shields.io/badge/Elixir-4B275F?style=flat-square&logo=elixir&logoColor=white)
![CLI](https://img.shields.io/badge/CLI-1E293B?style=flat-square)
![DSL](https://img.shields.io/badge/DSL-6366F1?style=flat-square)

</td>
</tr>
</table>

---

## Ecosystem

**10 libraries published on [hex.pm](https://hex.pm/users/lorenzo-sf)** — each solving one problem, built for real production constraints.

| Project | What it does |
|---------|-------------|
| 🚢 [**Flotilla**](https://github.com/Lorenzo-SF/flotilla) | LiveView architecture layer — Elm Architecture (model / update / view) |
| 🚦 [**Válvula**](https://github.com/Lorenzo-SF/valvula) | Zero-dependency token bucket rate limiter on OTP/ETS |
| 🧰 [**Apero**](https://github.com/Lorenzo-SF/apero) | Developer utilities — file ops, Git, Docker, crypto, HTTP, retry, cache |
| 🎨 [**Pote**](https://github.com/Lorenzo-SF/pote) | Color manipulation — parsing, conversion, palettes, xterm256 |
| 🏥 [**Botica**](https://github.com/Lorenzo-SF/botica) | Parallel system health checks and environment diagnostics |
| 📦 [**Batamanta**](https://github.com/Lorenzo-SF/batamanta) | Package Elixir apps as self-contained executables with embedded ERTS |

---

## Experience

**Core Team — [Truedat](https://www.truedat.io)** · Bluetab / IBM

Enterprise open source Data Governance platform — banking, insurance, telecom and retail.
**11 Elixir microservices** in production · REST + GraphQL · PostgreSQL · Elasticsearch · Redis · React.js

---

<div align="center">

`Elixir` `OTP` `Phoenix` `Ecto` `PostgreSQL` `Redis` `Elasticsearch` `Docker`

</div>
