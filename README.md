<h1 align="center">Abhinav Ashok M</h1>

<p align="center">
  Python Full-Stack Developer · Backend-focused
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/abhinav-ashok-m/">LinkedIn</a> ·
  <a href="mailto:abhinavashokm@gmail.com">Email</a> ·
</p>

---

## About

I am a Python-focused full-stack developer based in India, with a focus on backend engineering. I build multi-tenant systems, real-time features, and asynchronous pipelines, and I care about clean service boundaries, correctness, and testability.

I am currently seeking **backend / full-stack developer roles**. I completed professional software training at Brototype and have built several projects end to end.

---

## Featured Projects

### [Teeming](https://github.com/YOUR-USERNAME/teeming)
A multi-tenant SaaS platform that turns team ideas into measured outcomes: goals → ideas → upvotes → admin approval → planned board → progress tracking → outcome metrics.

- Tenant-aware service-layer architecture with JWT authentication, RBAC, and tenant isolation
- Real-time collaboration over WebSockets (Django Channels), including presence and discussions
- Stripe subscription management with webhook handling and plan versioning
- AI assistant behind a provider abstraction layer (Google Gemini)
- Async email via Celery and Redis; S3 media storage with presigned URLs

`Django` `DRF` `PostgreSQL` `Redis` `Celery` `React` `Tailwind` `React Query`

### [Faultline](https://github.com/YOUR-USERNAME/faultline) · *In development*
A Sentry-style error tracking and incident response platform, built as a six-service microservice system.

- Event ingestion that acknowledges only after Kafka accepts, with idempotent persistence and a DLQ with replay
- Issue grouping by fingerprint, regression detection, alerting, and human-approved rollback
- Service-owned databases, gRPC between services, and JWT verification via JWKS
- Designed around at-least-once delivery, failure recovery, and measurable load and failure testing

`FastAPI` `Kafka` `Redis` `PostgreSQL` `SQLAlchemy` `Alembic` `gRPC` `Docker` `GitHub Actions`

---

## Technical Skills

| Area | Technologies |
| :--- | :--- |
| **Core Language** | **Python** |
| **Backend** | Django, Django REST Framework, FastAPI, Celery |
| **Frontend** | React, Next.js, JavaScript, Tailwind CSS |
| **Data & Messaging** | PostgreSQL, Redis, Apache Kafka, SQLAlchemy |
| **Infrastructure** | Docker, Kubernetes, GitHub Actions, Linux, pytest, CI/CD |
| **Practices** | Microservices, multi-tenancy, Service-layer architecture, RBAC, WebSockets, REST and gRPC APIs, testing |

---

## Engineering Approach

- **Clear boundaries:** separate domain services from integrations and transport layers.
- **Designed for failure:** idempotency, retries, backoff, and graceful degradation.
- **Security by design:** tenant isolation, role-based access, and verified tokens.
- **Honest scope:** document what is built versus what is planned.

---

## Contact

I am happy to discuss opportunities, collaborations, or my projects.

**Email:** abhinavashokm@gmail.com · **LinkedIn:** [YOUR-LINKEDIN](https://www.linkedin.com/in/abhinav-ashok-m/)
