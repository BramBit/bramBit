![Profile](https://github.com/user-attachments/assets/7bcff0ec-8a99-487c-a69d-013b10c39078)

# Brayan Mercado Sanmartín

Full Stack Developer specialized in the TypeScript ecosystem, with production experience across SaaS, IoT, e-learning, and marketplace platforms.

[Portfolio](https://brayanmercado.com/) · [LinkedIn](https://www.linkedin.com/in/brayan-mercado-sanmartin/) · [GitHub](https://github.com/BramBit)

## About

I work end-to-end, from domain modeling on the backend to its consumption on the frontend, aiming for clean, testable, and maintainable architectures. Most of my recent work centers on Domain-Driven Design and Hexagonal Architecture, with a growing focus on applied AI engineering: RAG pipelines, hybrid search, and LLM orchestration without coupling AI infrastructure to core business logic.

I enjoy building complete products, solving real-world problems, and making deliberate engineering decisions around reliability, observability, and maintainability.

Open to backend, full-stack, or backend/AI engineering roles, remote or based in Medellín, Colombia.

## Experience

**Alaska Tech** — Co-Founder & Full Stack Developer · Jan. 2023–present

Co-founded a software venture focused on building digital products. Designed and built the backend for VeciApp, a multi-role marketplace serving nearly 300 small merchants, implementing JWT authentication, geolocation with PostGIS, and Wompi payment integration. Also developed React admin modules for merchants, products, customers, and financial indicators.

**Belvi Digital** — Backend Developer (Full Stack scope) · Dec. 2023–May 2026

Worked across Zeus, an IoT platform for medical aesthetic devices, and PLEI, an e-learning and marketing platform.

- Built a custom RAG system for Zeus, including document ingestion, embeddings, vector retrieval, and contextual question answering.
- Implemented provider-agnostic LLM integration using the Strategy Pattern, with OpenAI and Ollama fallback handling.
- Developed predictive maintenance analytics combining deterministic statistical calculations with LLM-generated insights.
- Built PLEI's hybrid search engine, replacing Algolia with vector search, PostgreSQL full-text search, title matching, and Reciprocal Rank Fusion.
- Implemented AI-assisted support workflows, Sentry error analysis, and Microsoft Teams notifications.
- Delivered financial reporting, digital wallet interfaces, account statements with PDF/Excel exports, and frontend modules for production IoT workflows.

## Featured Projects

### Pliegos — Public Procurement Intelligence

A backend platform that helps Colombian contractors discover and prioritize public procurement opportunities published on SECOP II. It synchronizes opportunities incrementally, filters out ineligible processes, generates explainable recommendations based on contractor profiles, handles incomplete source data transparently, and tracks material changes through alerts.

**Engineering highlights**
- Hybrid retrieval combining semantic search with PostgreSQL full-text search and Reciprocal Rank Fusion.
- Explainable recommendation scoring using semantic similarity, UNSPSC category, budget, and location.
- Local embeddings and LLM summaries through Ollama, with asynchronous processing via BullMQ.
- Explicit SQL over PostgreSQL and pgvector, without an ORM.
- Incremental synchronization, idempotent processing, automated tests, and ranking evaluation metrics.

**Stack:** TypeScript, NestJS, PostgreSQL, pgvector, Ollama, BullMQ, Redis, Docker.

[Repository](https://github.com/BramBit/Pliegos)

### Product Checkout Platform

A full-stack checkout application built around a complete credit-card payment flow, including product availability, customer and delivery information, payment processing through a sandbox gateway, and inventory updates.

**Engineering highlights**
- Hexagonal Architecture with explicit domain, application, and infrastructure boundaries.
- Railway-Oriented Programming using typed `Result<T, E>` values for expected business errors.
- PostgreSQL with the native `pg` driver and versioned migrations, without an ORM.
- Asynchronous payment status polling with recovery after page reloads.
- Automated testing across backend and frontend, with more than 99% coverage as reported for the project.

**Stack:** TypeScript, NestJS, React, Redux Toolkit, PostgreSQL, Jest, Vitest.

[Repository](https://github.com/BramBit/product-checkout-platform) · [Live Demo](https://product-checkout-platform-web.vercel.app) · [API Documentation](https://product-checkout-platform.onrender.com/docs)

## Technical Stack

**Backend** — TypeScript, Node.js, Express, NestJS, PHP, Laravel, Python, FastAPI

**Frontend** — React, Next.js, Astro, Redux Toolkit, Redux Saga, Vite, Material UI, Sass

**Data & Search** — PostgreSQL, MySQL, pgvector, PostGIS, Redis, vector search, full-text search

**Architecture** — Domain-Driven Design, Hexagonal Architecture, CQRS, Event-Driven Architecture, Strategy Pattern, Railway-Oriented Programming

**AI / LLM** — RAG pipelines, embeddings, hybrid search, LLM orchestration, prompt engineering, Ollama, OpenAI-compatible APIs

**Testing** — Jest, Vitest, Playwright, Cucumber, PHPUnit

**Infrastructure & Tools** — Docker, AWS S3, AWS ECS, Nginx, Azure DevOps, Git, GitHub, Jira, Render, Vercel

## Education & Certifications

- Tecnología en Desarrollo de Software — Corporación Universitaria Remington *(in progress, expected 2028)*
- Ingeniería de Alimentos — Professional degree
- Frontend con React — Platzi
- Software Development Foundations — Microsoft Learn
- Fundamentos de Análisis de Datos — Correlation One / MinTIC

## Contact

- **Website:** [brayanmercado.com](https://brayanmercado.com/)
- **Email:** brayan.msanmartin@gmail.com
- **LinkedIn:** [linkedin.com/in/brayan-mercado-sanmartin](https://www.linkedin.com/in/brayan-mercado-sanmartin/)
- **GitHub:** [github.com/BramBit](https://github.com/BramBit)

---

*Building maintainable software, integrating applied AI, and solving real business problems through engineering.*
