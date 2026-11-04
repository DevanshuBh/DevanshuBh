# 🚀 Devanshu Bhargava

**Full Stack Software Engineer | Distributed Systems | Generative AI (RAG + Agents)**

📍 Noida, India | ☕ Turning complex systems into scalable reality

📱 **[Explore my portfolio — built like an iPhone](https://portfolio-website-pink-alpha.vercel.app)**

---

## 🧠 About Me

I build **scalable Java and Spring Boot microservices** and **event-driven systems** on Apache Kafka, Redis and PostgreSQL, engineered for fault tolerance with DLQs, circuit breakers, outbox and idempotency.

With 2+ years of experience, I pair strong backend engineering with hands-on **Generative AI**: hybrid RAG and GraphRAG pipelines, LangGraph multi-agent systems, retrieval evaluation and cost-aware LLM routing. I ship end to end with React/Next.js, Docker and AWS.

---

## 💼 Experience

### 🏢 Associate Software Engineer @ Infinite Computer Solutions
*Oct 2024 – Present · Noida*

| 50K+ | 15K+ | 12× | 80% |
|:---:|:---:|:---:|:---:|
| active drivers | GPS events / sec | Postgres write throughput | less triage & replay time |

* **High-Throughput Telemetry Platform:** Spring Boot services for an enterprise real-time **fleet tracking platform** serving **50K+ active drivers** and **15,000+ GPS events/sec**, in a 10+ engineer team
* **Reliable Event Streaming:** **Kafka consumers** with manual offset commits, graceful shutdown hooks and rebalance listeners, so **no GPS event is lost** across crashes and rebalances
* **Fault Isolation:** **batch-bisection recovery** and a **Dead Letter Queue** tagged by error class, cutting triage and replay time by **80%**
* **Throughput Optimization:** **12× PostgreSQL write throughput** with 1,000-record Kafka batches, **COPY**-based bulk loads and idempotent upserts
* **Real-Time Fan-Out:** **Redis Pub/Sub** with Lua-based stale-update guards and bounded-queue **WebSocket** gateways streaming live positions to dispatchers

---

## 🚀 Featured Projects

### 🛡️ SENTINEL — Event-Driven Fraud Detection Gateway
**Java, Spring Boot, Kafka, Redis, Python, FastAPI**

* Cut API latency from **2s+ to 50ms** by moving fraud analysis off the request path onto Kafka
* **Resilience4j circuit breaker**, **Transactional Outbox** and DLQ for reliable fraud-event delivery, with **idempotency keys** preventing duplicate checks
* Distributed **Redis token-bucket rate limiter** plus a **FastAPI ML inference service** for fraud scoring
* Patterns: Two-Tier Processing · Saga · Strangler Fig · Correlation ID · Chain of Responsibility

### 🧠 CORTEX — Multi-Tenant GraphRAG Research Platform
**Python, LangGraph, pgvector, Neo4j, Amazon Bedrock**

* **Hybrid retrieval:** Postgres full-text + pgvector HNSW, Reciprocal Rank Fusion, cross-encoder reranking and **Neo4j GraphRAG**; recall@k and MRR evaluated nightly in CI on a hand-labelled golden set
* **Multi-agent orchestration:** LangGraph supervisor over Researcher, Analyst and Coder agents with loop guard and token budgets; cost-aware Ollama/Bedrock routing; sandboxed code execution
* **Multi-tenant:** PostgreSQL Row-Level Security; SSE streaming from Celery workers to a Next.js UI with citations

### 🚚 NEXUS — Real-Time Fleet Tracking Platform
**Java 21, Kafka, TimescaleDB, Redis, Next.js, AWS**

* Hand-built ingestion: kafka-clients consumers commit offsets only after the DB commit; GPS events loaded into **TimescaleDB via COPY** with idempotent writes; load-tested with **k6 on a 50K-vehicle model**
* Fault tolerant by design: DLQ, bisection recovery and partition-pause backpressure, tested with **Testcontainers + Toxiproxy**
* **Next.js + MapLibre GL** live map fed by Redis Pub/Sub WebSocket fan-out; deployed on **AWS ECS via Terraform** with Grafana alerts

---

## ⚙️ Tech Stack

### 🧩 Languages
* Java 21, Python, TypeScript, JavaScript, SQL

### ⚡ Backend & Distributed Systems
* Spring Boot, FastAPI, gRPC, REST, Microservices
* Apache Kafka, Redis, Celery, Resilience4j

### 🧠 Generative AI & ML
* RAG, GraphRAG, LangGraph, LangChain
* Amazon Bedrock, Ollama, scikit-learn, MLflow

### 🗄️ Databases
* PostgreSQL, TimescaleDB, pgvector, Neo4j

### ☁️ Cloud & DevOps
* AWS (ECS, RDS, ElastiCache, S3, Cognito), Terraform
* Docker, Kubernetes, GitHub Actions

### 🧪 Frontend, Testing & Observability
* React, Next.js
* Testcontainers, JUnit 5, pytest, k6
* OpenTelemetry, Prometheus, Grafana

### 🏗️ Design Patterns
* Transactional Outbox, Saga, CQRS, Circuit Breaker, Dead Letter Queue
* Idempotency, Strangler Fig, Write-Through Cache, Fan-out, Backpressure

---

## 📊 What I Care About

* Building **resilient systems that don’t break under load**
* Designing **low-latency architectures**
* Making AI systems **production-ready, not just demos**

---

## 🏆 Certifications & Recognition

* Google Data Analytics Professional Certificate
* Google Advanced Data Analytics Professional Certificate
* Performer of the Month among 200+ employees — Infinite Computer Solutions

---

## 📫 Connect With Me

* 📱 Portfolio: https://portfolio-website-pink-alpha.vercel.app
* 📧 [bhargavadevanshu10@gmail.com](mailto:bhargavadevanshu10@gmail.com)
* 💼 LinkedIn: https://www.linkedin.com/in/devanshu-bhargava-68b594258/
* 💻 GitHub: https://github.com/DevanshuBh
* ✍️ Medium: https://medium.com/@bhargavadevanshu10

---

⚡ *“I don’t just build features — I build systems that survive production.”*
