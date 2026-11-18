![Profile](https://github.com/user-attachments/assets/7bcff0ec-8a99-487c-a69d-013b10c39078)

# Brayan Mercado Sanmartín

**Full Stack Software Engineer | Backend Development · Software Architecture · Applied AI**

Software developer with 3+ years of production experience, specializing in TypeScript, Node.js, and React. I've worked on IoT, e-learning, and marketplace platforms, building backend services, APIs, frontend applications, and AI-assisted systems.

[Portfolio](https://brayanmercado.com/) · [LinkedIn](https://www.linkedin.com/in/brayan-mercado-sanmartin/) · [Email](mailto:brayan.msanmartin@gmail.com)

## About

I work across the software development lifecycle, from domain modeling and API design to frontend integration, automated testing, and deployment.

My strongest focus is backend engineering with TypeScript and Node.js, applying Domain-Driven Design, Hexagonal Architecture, and pragmatic engineering practices to build maintainable systems.

My professional experience also includes applied AI: document ingestion, RAG pipelines, semantic and hybrid search, LLM provider abstractions, and asynchronous processing integrated into existing business applications.

I value clear architectural boundaries, explicit trade-offs, testable business logic, and solutions grounded in real requirements.

**Open to Backend, Full Stack, and Backend/AI engineering opportunities**, remotely or in the Medellín metropolitan area, Colombia.

## Professional Experience

### Belvi Digital
**Backend Developer — Full Stack Scope | Dec. 2023 – May 2026**

Worked on Zeus and PLEI, two production platforms supporting medical aesthetic device operations, training, and digital resources.

**Zeus — IoT Platform for Medical Devices**

- Built a document-based RAG system with SHA-256 duplicate detection, text extraction, chunking, embeddings, and semantic retrieval using PostgreSQL and pgvector.
- Implemented an LLM provider abstraction using the Strategy Pattern, integrating OpenAI and Ollama with availability checks and fallback handling.
- Developed predictive maintenance analytics combining deterministic calculations, linear regression, and structurally validated LLM-generated insights.
- Implemented financial reporting and JWT-based report access, developed wallet and account statement interfaces, and extended existing wallet backend functionality.
- Built device geolocation and administrative interfaces using Next.js, and implemented HTTP integration between Zeus and PLEI.

**PLEI — E-Learning Platform**

- Developed most of a custom hybrid search engine that replaced Algolia, combining vector retrieval, PostgreSQL full-text search, title matching, and weighted Reciprocal Rank Fusion.
- Implemented asynchronous embedding generation using Laravel model events, queued jobs, and PostgreSQL/pgvector.
- Built multimedia optimization workflows using WebP and FFmpeg, along with tools for archiving unreferenced assets in AWS S3 Glacier Instant Retrieval.
- Developed AI-assisted support workflows, including Sentry webhook validation, LLM-based error analysis, and Microsoft Teams notifications.
- Contributed to React frontend restructuring, administrative features, Vitest unit tests, and Playwright E2E tests.

**Core technologies:** TypeScript, Node.js, Express, PHP, Laravel, PostgreSQL, MySQL, pgvector, Redis, React, Next.js, RabbitMQ, and AWS S3.

### Alaska Tech
**Co-Founder & Full Stack Developer | Jan. 2023 – Present**

Co-founded a software development venture focused on digital products and custom applications.

**VeciApp — Local Marketplace**

- Developed backend features and REST APIs using Node.js, Express, and TypeORM.
- Implemented JWT authentication, role-based access control, and relational and geospatial data operations with PostgreSQL/PostGIS.
- Worked on Wompi payment integration, React administrative interfaces, and deployment using Render.

**Fundación Maleua — Institutional Website**

- Developed an institutional website using Astro.
- Separated structured content from presentation components.
- Worked on static site generation and deployment through Vercel.

## Featured Projects

### Pliegos — Public Procurement Intelligence

**Backend implemented · Full product MVP in development**

A public procurement intelligence product designed to help Colombian contractors discover, evaluate, and monitor opportunities published through SECOP II.

**Engineering highlights**

- Incremental synchronization and normalization of public procurement data.
- Hybrid retrieval combining semantic search and PostgreSQL full-text search through Reciprocal Rank Fusion.
- Explainable recommendation scoring based on semantic similarity, UNSPSC categories, budget, and location.
- Asynchronous processing with BullMQ, Redis, and locally hosted Ollama models.
- Explicit PostgreSQL SQL and pgvector integration without an ORM.
- Automated tests, architecture checks, and ranking evaluation using precision@10 and nDCG@10.

**Stack:** TypeScript, NestJS, PostgreSQL, pgvector, Redis, BullMQ, Ollama, Docker.

[Explore repository](https://github.com/BramBit/Pliegos)

### Product Checkout Platform

**Full Stack Project · Sandbox Demo Available**

A full-stack checkout application implementing product selection, customer and delivery information, credit-card tokenization, and payment processing through a sandbox gateway.

**Engineering highlights**

- Hexagonal Architecture with domain, application, and infrastructure boundaries.
- Railway-Oriented Programming using typed `Result<T, E>` values for expected business errors.
- PostgreSQL persistence through the native `pg` driver and versioned migrations, without an ORM.
- Asynchronous payment status polling with transaction context preserved across page reloads.
- Automated unit and component testing across backend and frontend.

**Documented statement coverage:** 99.80% backend and 96.15% frontend, according to the project's coverage reports.

**Stack:** TypeScript, NestJS, React, Redux Toolkit, PostgreSQL, Jest, Vitest.

[Repository](https://github.com/BramBit/product-checkout-platform) · [Live Sandbox Demo](https://product-checkout-platform-web.vercel.app) · [API Documentation](https://product-checkout-platform.onrender.com/docs)

## Technical Stack

**Backend**  
TypeScript · JavaScript · Node.js · NestJS · Express · PHP · Laravel

**Frontend**  
React · Next.js · Astro · Vite · Redux Toolkit · Redux Saga · Material UI

**Data & Search**  
PostgreSQL · MySQL · pgvector · PostGIS · Redis · TypeORM · Full-Text Search · Vector Search

**Architecture & Integration**  
Domain-Driven Design · Hexagonal Architecture · REST APIs · Event-Driven Systems · Strategy Pattern · Railway-Oriented Programming · Webhooks

**Applied AI**  
RAG · Embeddings · Hybrid Search · LLM Provider Integration · OpenAI · Ollama

**Testing & Quality**  
Jest · Vitest · Playwright · Cucumber · Automated Testing · GitHub Actions

**Infrastructure & Tools**  
Docker · RabbitMQ · BullMQ · AWS S3 · Sentry · Git · Render · Vercel

## Education

**Software Development Technology**  
Corporación Universitaria Remington — In progress

**Food Engineering**  
Professional degree

### Additional Training

- Frontend with React — Platzi
- Software Development Foundations — Microsoft Learn
- Data Analysis Fundamentals — Correlation One / MinTIC

## Contact

- **Portfolio:** [brayanmercado.com](https://brayanmercado.com/)
- **Email:** [brayan.msanmartin@gmail.com](mailto:brayan.msanmartin@gmail.com)
- **LinkedIn:** [brayan-mercado-sanmartin](https://www.linkedin.com/in/brayan-mercado-sanmartin/)
- **GitHub:** [BramBit](https://github.com/BramBit)

---

*Building maintainable software, applying AI to real problems, and making engineering decisions that stand up to scrutiny.*
