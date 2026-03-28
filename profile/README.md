<div align="center">

<br/>

```
 ███╗   ██╗ █████╗ ██╗   ██╗███╗   ██╗███████╗██╗  ██╗
 ████╗  ██║██╔══██╗╚██╗ ██╔╝████╗  ██║██╔════╝╚██╗██╔╝
 ██╔██╗ ██║███████║ ╚████╔╝ ██╔██╗ ██║█████╗   ╚███╔╝ 
 ██║╚██╗██║██╔══██║  ╚██╔╝  ██║╚██╗██║██╔══╝   ██╔██╗ 
 ██║ ╚████║██║  ██║   ██║   ██║ ╚████║███████╗██╔╝ ██╗
 ╚═╝  ╚═══╝╚═╝  ╚═╝   ╚═╝   ╚═╝  ╚═══╝╚══════╝╚═╝  ╚═╝
```

**Local-first. Architecture-grade.**


[![Status](https://img.shields.io/badge/status-active-22d3ee?style=flat-square)](https://github.com/naynex)
[![Focus](https://img.shields.io/badge/focus-fullstack%20%7C%20infra%20%7C%20AI-3b82f6?style=flat-square)](https://github.com/naynex)
[![Stack](https://img.shields.io/badge/stack-Go%20%7C%20Java%20%7C%20Python%20%7C%20TS%20%7C%20Kotlin-0a0f1e?style=flat-square&labelColor=1e293b)](https://github.com/naynex)

<br/>

> 🌐 [README en Español](./README.es.md)

</div>

---

## What is Naynex?

Naynex is a software development studio that builds complete, production-grade systems — from the interface users touch to the infrastructure that never sleeps. We work with schools, institutes, and commerce businesses that are serious about technology: not just digitizing existing chaos, but redesigning it with modern principles.

We cover the full product surface — frontend, backend, cloud, and mobile — with a deliberate specialization in what runs underneath: **concurrent systems, event-driven architecture, and AI as infrastructure**.

> *"Most software studios build features. We build the system that makes features possible."*

---

## Core Principles

```
  architecture-first    →   decisions before code, contracts before implementation
  async by nature       →   non-blocking I/O, event-driven from the ground up
  concurrent by design  →   goroutines, thread pools, worker queues — not an afterthought
  performance as intent →   latency and throughput are requirements, not benchmarks
  AI as a layer         →   embedded intelligence, not bolted-on demos
  local-first           →   your infrastructure, your data, your control
```

---

## What We Build

**Frontend** — interfaces that communicate clearly and perform consistently. Component-driven, accessible, and built to evolve without accumulating debt.

**Backend** — the part we care most deeply about. APIs, workers, event processors, and domain logic designed with explicit architecture, observable behavior, and concurrency as a first-class concern. Not scaffolded — architected.

**Cloud & Infra** — containerized workloads, CI/CD pipelines, message brokers, and infrastructure as code. Systems that are reproducible, auditable, and boring in the best possible way.

**Mobile** — native Android applications for clients who need a first-class mobile presence alongside their web systems.

---

## Technology Stack

| Layer | Technologies |
|---|---|
| **Frontend** | React · Next.js · Angular · TypeScript |
| **Backend** | Go · Java / Spring Boot · Python / FastAPI |
| **Concurrency & Events** | goroutines · asyncio · Kafka · reactive streams |
| **Cloud & Serverless** | Python · TypeScript · Docker · CI/CD |
| **Mobile** | Kotlin / Android |
| **Data** | PostgreSQL · Redis · vector stores |
| **Observability** | structured logging · distributed tracing · metrics |

> **Where we go deepest:** concurrent systems, event-driven design, and performance-critical backends. Go for throughput-sensitive services, Java for domain-complex systems, Python for AI-integrated pipelines.

---

## Engineering Standards

These are deliberate decisions, not stylistic preferences.

**On architecture**
- Domain logic is always isolated from the transport layer. Routes are not business logic.
- Async-first on I/O-bound workloads. Sync where the tradeoff is justified and explicit.
- Explicit over implicit. Configuration as code. No magic, no hidden behavior.

**On concurrency & performance**
- Shared state is identified at design time, not discovered in production.
- Every queue has a bounded capacity. Backpressure is not optional.
- Goroutines and async workers are cheap — design for many small units of work, not a few large ones.
- Latency budgets are defined before writing a line of code.

**On events & messaging**
- Commands and events are different things. Model them differently.
- Event schemas are contracts. Version them like APIs.
- Consumers must be idempotent. The broker will retry.

**On AI integration**
- LLMs are non-deterministic I/O — treat them like external services, with timeouts, retries, and fallbacks.
- Prompt engineering is engineering. Prompts are versioned, tested, and reviewed.
- Embeddings and vector search are infrastructure decisions, not model decisions.

---

## How We Work

```
Discovery  →  understand the real problem, not the stated one
Design     →  architecture docs and ADRs before implementation starts
Build      →  iterative, tested, and observable from day one
Operate    →  structured logs, runbooks, and metrics — not tribal knowledge
```

Small teams. Direct communication. No account managers between client and engineer.

---
<div align="center">

*Built in Peru. Engineered for anywhere.*


<sub>© Naynex · All systems running.</sub>

</div>