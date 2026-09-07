![Profile](https://github.com/user-attachments/assets/79567bf4-72dc-4825-882d-f12d7e5fe76b)

# Brayan Mercado Sanmartín

Backend developer specialized in TypeScript, with production experience across IoT platforms, e-learning systems, and AI-powered search.

## About

I work end-to-end, from domain modeling to deployment, trying to keep architecture clean, testable, and safe to change. Most of my recent work centers on Domain-Driven Design and Hexagonal Architecture, with a growing focus on integrating AI components — RAG pipelines, hybrid search, LLM orchestration — without letting them leak into core business logic.

Open to backend, full-stack, or backend/AI roles, remote or based in Medellín, Colombia.

## Experience

**Alaska Tech** — Co-founder & Full Stack Developer · 2023–present
Designed and built the backend for VeciApp, a multi-role marketplace for small merchants in Santa Marta (~300 registered businesses): JWT authentication, geolocation with PostGIS, Wompi payment integration, and an admin panel in React.

**Belvi Digital** — Backend Developer · 2023–2026
Worked on Zeus (IoT platform) and Plei (e-learning). Designed a production RAG system from scratch — chunking, embeddings, pgvector — and a hybrid search engine combining vector similarity, full-text search, and trigram matching, fused with Reciprocal Rank Fusion. Built a provider-agnostic LLM abstraction layer using the Strategy pattern.

## Featured projects

**Product Checkout Platform**
Full checkout flow built under a 3-day technical assessment. Hexagonal architecture with no ORM, Railway-Oriented Programming for expected business errors, resilient async payment polling with state recovery on page reload, and 99%+ test coverage.
[Repo](https://github.com/BramBit/product-checkout-platform) · [Live demo](https://product-checkout-platform-web.vercel.app) · [API docs](https://product-checkout-platform.onrender.com/docs)

**Plei — Hybrid Search & RAG**
Semantic, lexical, and trigram search over course content combined with Reciprocal Rank Fusion, plus a RAG pipeline for contextual Q&A.

**VeciApp**
Multi-role marketplace backend: authentication, geolocation, payments, and an admin dashboard consuming the same APIs it exposes.

**Avatar Interview**
Real-time conversational avatar: WebSocket → speech-to-text → LLM → text-to-speech, orchestrated across five microservices with FastAPI, with mirrored state machines on client and server.

## Stack

**Backend** — TypeScript, Node.js, Express, NestJS, Laravel, Python (FastAPI)
**Frontend** — React, Next.js, Redux Toolkit
**Data** — PostgreSQL, pgvector, Redis, MySQL
**Architecture** — Domain-Driven Design, Hexagonal Architecture, CQRS, event-driven systems (RabbitMQ)
**AI / LLM** — RAG pipelines, embeddings, hybrid search, provider-agnostic LLM integration (Ollama, OpenAI-compatible APIs)
**Infra & testing** — Docker, AWS ECS, Azure DevOps, Nginx, Jest, Vitest, Playwright

## Contact

- Email: brayan.msanmartin@gmail.com
- LinkedIn: [linkedin.com/in/brayan-mercado-sanmartin](https://www.linkedin.com/in/brayan-mercado-sanmartin/)
- GitHub: [github.com/BramBit](https://github.com/BramBit)
