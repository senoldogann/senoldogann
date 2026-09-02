# Senol Dogan

<p align="left">
  <b>Senior Full Stack & Systems Engineer</b> based in <b>Oulu, Finland</b> 🇫🇮<br>
  7+ years architecting enterprise web apps, distributed backends, mobile clients, and developer tooling.
</p>

<p align="left">
  <a href="https://www.senoldogan.dev"><img src="https://img.shields.io/badge/Portfolio-senoldogan.dev-0969da?style=flat-square&logo=google-chrome&logoColor=white" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/senoldogann"><img src="https://img.shields.io/badge/LinkedIn-senoldogann-0a66c2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://www.npmjs.com/package/@senoldogann/context-manager"><img src="https://img.shields.io/badge/NPM-@senoldogann/context--manager-cb3837?style=flat-square&logo=npm&logoColor=white" alt="NPM" /></a>
  <a href="https://apps.apple.com/us/app/code-companion-mobile/id6763614196"><img src="https://img.shields.io/badge/App_Store-iOS_Apps-000000?style=flat-square&logo=apple&logoColor=white" alt="App Store" /></a>
  <a href="mailto:contact@senoldogan.dev"><img src="https://img.shields.io/badge/Email-contact%40senoldogan.dev-d9381e?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

### 📌 Engineering Profile

I design and ship end-to-end software systems across the entire product lifecycle — from cloud infrastructure and database schemas to reactive frontends, mobile clients, and system-level developer utilities.

- **Frontend & Web Systems:** Modern React (18/19), Next.js (App Router, SSR, RSC), TypeScript, Tailwind CSS, Vite.
- **Backend & Cloud Architecture:** Node.js, Express, Go, Python (FastAPI), Azure Cloud (Serverless Functions, Bicep IaC, Entra ID, Storage Queues/Blobs), Docker.
- **Data, BaaS & State:** PostgreSQL, Supabase, Redis, Elasticsearch, LanceDB (Embedded Vector DB), SQLite.
- **Testing & Quality Assurance:** Test-Driven Development (TDD) with Vitest, Playwright (E2E), Jest, Pytest, and Rust Cargo integration test suites.
- **Observability & Resilience:** Production monitoring with Sentry, Azure Application Insights, structured logging (`tracing`, `pino`), and graceful degradation.
- **Systems & Native:** High-performance tooling and mobile clients written in **Rust**, **Go**, **Swift**, and **React Native**.

---

### 🛠 Technical Arsenal

| Category | Core Stack & Tools |
| :--- | :--- |
| **Languages** | TypeScript, JavaScript, Rust, Go, Python, Swift, SQL |
| **Frontend Frameworks** | React, Next.js, Tailwind CSS, Vite, Redux Toolkit, Zustand, deck.gl |
| **Backend & Microservices** | Node.js, Express.js, Go (`net/http`, Gin), FastAPI, REST, GraphQL, MQTT (`rumqttc`) |
| **Databases & BaaS** | PostgreSQL, Supabase, Redis, Elasticsearch, LanceDB, SQLite, MongoDB |
| **Testing & Automation** | Vitest (`@vitest/coverage-v8`), Playwright, Jest, Pytest (`pytest-asyncio`, `pytest-cov`), Rust `tests/` |
| **Cloud & DevOps** | Microsoft Azure (Functions, SWA, Entra ID, Queues, Blobs), Docker, Kubernetes, Bicep IaC, GitHub Actions CI/CD |
| **Observability & Security** | Sentry, Azure Application Insights, Structured Tracing (`tracing-subscriber`), MSAL / Entra ID, OAuth2 |
| **Mobile & Desktop** | React Native (Expo), Flutter, Swift (macOS & iOS), Tauri |

---

### 🚀 Production Products & Engineering Highlights

#### Enterprise SaaS & Live Web Platforms

- **[ComplyLane](https://app.complylane.com/)** — B2B compliance and obligation tracking workspace.
  - Replaces spreadsheet workflows with real-time obligation ownership, evidence audits, and client reporting.
  - **Stack:** React, TypeScript, Vite, Azure Static Web Apps, Azure Functions (Serverless), Microsoft Entra ID (MSAL), Azure Table/Blob/Queue Storage, OpenAI API, Bicep IaC.
  - **Quality & Observability:** Comprehensive automated test coverage via **Vitest** and **Playwright (E2E)**; monitored with **Application Insights**.

- **[JobFinder.fi](https://www.jobfinder.fi/)** — Finland-wide job discovery and aggregation engine.
  - Aggregates employment listings from 9+ Finnish portals in real-time with sub-100ms search latency.
  - **Stack:** Next.js, Go microservices, PostgreSQL, Redis cache layer, Elasticsearch fuzzy full-text search.

- **[OmaLeima](https://www.omaleima.fi/)** — Digital stamp passport and event loyalty platform used across Finland.
  - Digitizes physical student passports with offline-resilient QR verification between attendees and merchant devices.
  - **Stack:** React Native (Expo), TypeScript, Node.js backend.

- **[Code-Refactoring.com](https://www.code-refactoring.com/)** — AI-assisted static analysis and refactoring workspace.
  - Analyzes codebase maintainability and automates structural code transformations.
  - **Stack:** Next.js, Python, AST analysis engine.

#### Mobile & Native Desktop Applications

- **[Code Companion Mobile](https://apps.apple.com/us/app/code-companion-mobile/id6763614196)** *(Published on Apple App Store)*
  - Native iOS client allowing developers to interact with GitHub Copilot context and manage remote coding sessions on the go.
  - **Stack:** React Native (Expo), TypeScript, iOS Secure Keychain.

- **[Codex Switcher](https://github.com/senoldogann/codex-switcher)** *(macOS Menu Bar)*
  - Background menu bar utility that monitors OpenAI rate limits and rotates credentials with zero manual friction.
  - **Stack:** Swift, AppKit, macOS Keychain API.

- **[Lustra](https://github.com/senoldogann/Lustra-Macebook-Device-Cleaner)** *(macOS)*
  - System performance and cache maintenance tool engineered with native macOS design principles.
  - **Stack:** Swift, SwiftUI.

#### Open Source & Developer Infrastructure

- **[LLM-Context-Manager](https://github.com/senoldogann/LLM-Context-Manager)** ([NPM: `@senoldogann/context-manager`](https://www.npmjs.com/package/@senoldogann/context-manager))
  - Model Context Protocol (MCP) server that converts multi-language codebases into queryable Knowledge Graphs for AI assistants (Claude Code, Cursor, Windsurf).
  - **Engine:** Built with a high-speed Rust core (`ccm-core`), **Tree-sitter** AST parsers (TypeScript, Python, Rust, Go), **LanceDB** vector store, and **petgraph**. Includes automated golden integration tests.

- **[NordicPulse](https://github.com/senoldogann/NordicPulse)**
  - Distributed Energy Resource (DER) management and telemetry platform handling high-throughput sensor streams.
  - **Stack:** Rust telemetry ingestor (`rumqttc`, `tokio`, `sqlx`), PostgreSQL, Next.js 16 (React 19), deck.gl, and MapLibre GL.

- **[own-harness](https://github.com/senoldogann/own-harness)**
  - Local proxy and policy control plane for AI coding agents to reduce API costs and enforce team security rules.
  - **Stack:** TypeScript, pnpm monorepo, SQLite, full test coverage via **Vitest V8 Coverage**.

- **[Guardian IDE](https://www.guardianide.com/en)**
  - Code governance protocol enforcing architecture boundaries for small software engineering teams.
  - **Stack:** Rust, Tauri, React, TypeScript.

---

### 💼 Work Experience

- **Contract Full Stack Developer** — *Data Solutions Finland Oy* (Remote)
  - Developed an offline-capable mobile agent with Flutter, implementing client-side caching and resilient sync workflows.
  - Improved API response times and frontend-backend communication protocol efficiency.
- **Contract Full Stack Developer** — *Omapalsta Oy* (Remote)
  - Architected and integrated Azure cloud backends with Next.js frontend web applications.
  - Implemented reusable component design systems and standardized CI/CD pipelines.
- **Contract Full Stack Developer** — *Mstofix* (Remote)
  - Built scalable web applications with React, Node.js, and PostgreSQL.
  - Designed relational database schemas and optimized RESTful endpoints for enterprise workflows.
- **Independent Consultant & Full Stack Engineer** (Remote · Worldwide)
  - Delivered 10+ custom SaaS platforms, dashboards, and internal business tools for international clients.
  - Managed end-to-end delivery: architecture, testing (Vitest / Playwright / Pytest), deployment, and monitoring (Sentry / Azure).

---

### 📬 Connect with Me

- 🌐 **Portfolio & Case Studies:** [senoldogan.dev](https://www.senoldogan.dev)
- 💼 **LinkedIn:** [linkedin.com/in/senoldogann](https://www.linkedin.com/in/senoldogann)
- ✉️ **Email:** [contact@senoldogan.dev](mailto:contact@senoldogan.dev)
- 📍 **Location:** Oulu, Finland (Available for local roles in Finland and remote positions globally)
