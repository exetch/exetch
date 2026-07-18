## Aleksey Belov — Senior Python Developer

Backend engineer with 5+ years of experience designing high-load systems and LLM/RAG platforms. I focus on service architecture (FastAPI, SQLAlchemy, PostgreSQL), asynchronous data processing, and integrating LLMs into production pipelines with a strong emphasis on reliability, quality control, and security.

### What I do

- Design and build backend services from the ground up — layered architecture, async I/O, clean domain boundaries (Router → Service → Repository → Unit of Work).
- Integrate LLMs into products the right way: RAG search, agentic pipelines with permission scoping and provenance, and deterministic calculations kept *outside* the model where correctness matters.
- Build authorization cores (RBAC, JWT, SSO) and secure real-time systems, including guardrails against prompt injection and secret leakage.
- Own streaming and data pipelines (Kafka, RabbitMQ, TimescaleDB) with guaranteed delivery via transactional outbox patterns.
- Ship with quality gates: 80%+ test coverage, mypy, ruff, pre-commit, and CI/CD.

### Selected work

- **Corporate AI document platform (RAG)** — reranking, vector store migration (Milvus → Qdrant) with benchmarking, OCR for scanned documents, and LLM-based extraction with deterministic `Decimal` calculations and per-cell provenance validated on a curated eval corpus.
- **Agentic LLM pipelines** — a controllable harness with permission scoping, call budgets, and step-level provenance that assembles documents from natural-language queries.
- **Farm monitoring backend** — telemetry ingest from edge modules (Jetson) into a PostgreSQL + TimescaleDB pipeline feeding an external ML forecasting service, with guaranteed metric delivery under unstable network conditions.

### Tech stack

**Languages:** Python, SQL
**Frameworks:** FastAPI, SQLAlchemy (async), Pydantic
**Data & storage:** PostgreSQL, TimescaleDB, Redis, Elasticsearch, Milvus, Qdrant
**Messaging & realtime:** Kafka, RabbitMQ, WebSocket, Celery
**AI / ML:** LLM integration, RAG, agentic pipelines
**Infra & DevOps:** Docker, Kubernetes, GitLab CI/CD, Alembic, Prometheus, Grafana, Sentry, Linux

### Contact

- Telegram: [@akslex](https://t.me/akslex)
