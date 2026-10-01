# Jash Rashne

Computer Engineering student focused on **backend engineering, distributed systems, and reliable infrastructure**.

I enjoy building systems where correctness matters — consensus, fault tolerance, concurrency, state management, recovery, and backend architecture.

Currently working primarily with **Go, C++, Python, PostgreSQL, Redis, and Docker**.

## Featured Engineering

### [FlowForge](https://github.com/JashRashne/FlowForge)

Fault-tolerant distributed workflow orchestration engine built in Go.

Implements DAG scheduling, horizontally scalable workers, lease-based task ownership, fencing tokens, PostgreSQL-backed durable state, Redis Streams, transactional outbox messaging, retries, and crash recovery.

### [Concord](https://github.com/JashRashne/Concord)

Distributed key-value store built from first principles in Go around the Raft consensus algorithm.

Includes leader election, replicated logs, quorum commits, automatic failover, persistent consensus state, WAL-based crash recovery, and multi-node Docker clustering.

### [IdeaLab](https://github.com/JashRashne/Idealab)

Real-time collaborative ideation platform with a FastAPI backend, asynchronous MongoDB persistence, server-authoritative WebSocket synchronization, layered backend architecture, and AI-assisted workflows.

## Open Source

Contributor to [OpenTelemetry Collector Contrib](https://github.com/open-telemetry/opentelemetry-collector-contrib), [px0](https://github.com/px0-ai/px0), and [Vorssaint](https://github.com/vorssaint/vorssaint-utils).

* **OpenTelemetry** — [PR #51231](https://github.com/open-telemetry/opentelemetry-collector-contrib/pull/51231) — fixed incorrect SQL Server receiver rate metrics by deriving rates from raw cumulative counters, with per-stream state tracking, counter-reset handling, stale-stream recovery, fractional-rate support, and regression tests.

* **px0** — [PR #156](https://github.com/px0-ai/px0/pull/156) — added Expand All / Collapse All controls to the file explorer with batched directory expansion, cancellation, stale-response handling, persisted folder state, accessibility support, and ignored-directory safeguards.

* **Vorssaint** — [PR #963](https://github.com/vorssaint/vorssaint-utils/pull/963) — added support for installing macOS applications into `~/Applications`, including persisted destination preferences, cross-directory collision handling, filesystem safety checks, regression coverage, and localization across 13 languages.

* **Vorssaint** — [PR #909](https://github.com/vorssaint/vorssaint-utils/pull/909) — improved Scratchpad default naming while preserving existing user data, custom names, and legacy migration behaviour.

All contributions above were merged upstream.

## Currently Exploring

* Distributed systems and reliability
* Systems programming with Go and C++
* Concurrency and performance
* Databases and storage systems
* Quantitative engineering and low-latency systems

## Languages & Tools

`Go` · `C++` · `Python` · `TypeScript` · `PostgreSQL` · `Redis` · `Docker` · `FastAPI` · `Django` · `React`

---

I like building things that force me to understand what happens when systems **fail**, not only when they work.
