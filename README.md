# Gabriel Dalmolin

### Production-minded backend and full-stack engineer

I'm a senior software engineer with **7+ years of experience** building APIs,
backend systems, internal tools, and operational automation. I focus on explicit
contracts, predictable failure handling, security, and long-term maintainability.

Through **[Kopf Studio](https://github.com/kopfstudio)**, I build reliable
integrations, internal tools, and automation for businesses with manual processes
or disconnected systems. The goal is practical: less repeated data entry,
clearer operational visibility, and workflows that can recover safely from failures.

## Selected Projects

### [GrantLedger](https://github.com/kopfstudio/grantledger)

Multi-tenant SaaS billing infrastructure with a completed platform baseline and a
guided self-hosted demo. Implements schema-first contracts, tenant isolation,
idempotent writes, replay-safe webhooks, asynchronous invoice processing, and
API and worker observability.

[CI](https://github.com/kopfstudio/grantledger/actions/workflows/ci.yml) ·
[Security checks](https://github.com/kopfstudio/grantledger/actions/workflows/security.yml) ·
[OpenAPI contract](https://github.com/kopfstudio/grantledger/blob/main/docs/openapi/openapi.json)

`TypeScript` `Node.js` `PostgreSQL` `Prometheus` `Grafana`

### [Authentication API](https://github.com/gabedalmolin/auth-api-node)

Production-oriented authentication service with session lifecycle management,
refresh-token rotation, replay detection, rate limiting, and observability.
Includes PostgreSQL and Redis integration tests, a Docker Compose setup, and
k6 performance validation. See the repository for local setup and API documentation.

[CI](https://github.com/gabedalmolin/auth-api-node/actions/workflows/ci.yml)

`TypeScript` `Express` `Prisma` `PostgreSQL` `Redis` `k6`

## Work in Progress

### [Marketplace Sync API](https://github.com/gabedalmolin/marketplace-sync-api)

An incremental FastAPI service being developed toward a commercial demo of
reliable order ingestion and external synchronization. The application and
PostgreSQL persistence foundations are implemented; webhook workflows, order
endpoints, and external synchronization are still planned.

`Python` `FastAPI` `SQLAlchemy` `PostgreSQL` `Alembic`

### [Abaris](https://github.com/kopfstudio/abaris)

Research and architectural foundations for reproducible vulnerability experiments
and patch-behavior validation. Intended to compare a supplied reproducer against
a known-vulnerable baseline and a candidate revision while preserving evidence.
There is no working CLI or supported execution backend yet.

## Areas of Expertise

- Backend architecture, API contracts, and system integrations
- Idempotency, retries, replay safety, and asynchronous workflows
- Authentication, authorization, billing, and multi-tenant systems
- Application security and secure-by-default design
- Testing, CI/CD, observability, and operational reliability
- Internal tools, full-stack applications, and business automation

## Engineering Principles

- Correctness before convenience.
- Explicit contracts over hidden behavior.
- Reliability beyond the happy path.
- Secure defaults and least privilege.
- Observable and reversible operations.
- Small, reviewable, and maintainable changes.

## Project Inquiries

For integration, internal tooling, or automation work, open a
[project inquiry at Kopf Studio](https://github.com/kopfstudio/.github/issues/new).
Share a brief description of the workflow and the systems involved; issues are public.
