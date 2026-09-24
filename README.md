# Ernest Mlati Mwang'ombe
### IT Consultant | Backend & AI Systems Engineer

> *"I build secure backend software that automatically extracts structured data from messy business files (like PDF invoices, orders, and receipts) and saves them directly to databases with zero manual typing."*

I am an IT Consultant based in Nairobi, Kenya (UTC+3), applying a background in network security, server administration, and infrastructure to building secure REST APIs, database systems, and document processing automation pipelines.

---

## 🎯 Technical Capabilities & Stack Readiness

| Domain | Proven Capabilities (Supported by Code Evidence) | Active Engineering Roadmap |
| :--- | :--- | :--- |
| **Backend & APIs** | Express 5.2.1 REST APIs, Modular Routing, Custom Middleware Gates, Interactive Swagger UI (`/docs`), OpenAPI 3.0 Specs | Strict TypeScript API Architecture, Zod Schema Runtime Validation |
| **Security & Auth** | Supabase Auth Integration (`@supabase/supabase-js`), Cryptographic JWT Bearer Token Verification, Parameterized SQL Queries (`$1`, `$2`, `?`) | Multi-Role Access Control (RBAC), Rate-Limiting Perimeter Defense |
| **Databases** | PostgreSQL 16 Alpine, `pg.Pool` Pre-Warmed Connection Sockets, SQLite Write-Ahead Logging (WAL) Mode (`better-sqlite3`), Atomic Transactions | Relational Database Migrations, Multi-Tenant Schema Design |
| **Infrastructure** | Docker, Docker Compose, Internal Bridge Networks (`db:5432`), Netlify Production Cloud Ingress | Automated CI/CD Pipelines, Production Server Hardening |
| **Workflow Systems** | Application State Engines (`applyfolio`), Business Logic Separation, Data Minimization Controls | LLM API Ingestion, Structured JSON Document Extraction |

---

## 📂 Featured Repositories & Live Web Projects

### 🔒 [Auth-Login-protect](https://github.com/ernestmwangombe/Auth-Login-protect)
**Backend Identity Verification & Supabase Auth API Gateway**
* **Problem Solved:** Enforces cryptographic access control on private backend resources and protects SME operational data behind verified session tokens.
* **Architecture:** Node.js, Express 5.2.1, Supabase Auth (`@supabase/supabase-js`), JWT Bearer Token Middleware, OpenAPI 3.0, Swagger UI (`swagger-ui-express`).
* **Key Features:**
  * Custom `requireAuth` middleware gating protected endpoints (`/protected/profile`, `/protected/dashboard`).
  * Authentication endpoints (`/auth/signup`, `/auth/login`, `/auth/logout`) issuing signed JWT access tokens.
  * Live Swagger UI documentation hosted on `/docs` with interactive `BearerAuth` testing.
  * Data privacy controls aligned with Kenya Data Protection Act (ODPC) Section 25.

### 🔹 [task-management-api](https://github.com/ernestmwangombe/task-management-api)
**Containerized REST API & Dual-Database Persistence Engine**
* **Problem Solved:** Provides persistent transactional record management across containerized Docker environments with high-concurrency crash safety.
* **Architecture:** Node.js, Express 5.2.1, PostgreSQL 16 (Alpine), SQLite 3 (WAL Mode), Docker Compose, OpenAPI 3.0, Swagger UI.
* **Key Features:**
  * `pg.Pool` connection management reducing TCP handshake latency overhead.
  * `better-sqlite3` Write-Ahead Logging (WAL) with atomic database transactions (`db.transaction()`).
  * SQL parameterization (`$1`, `$2`, `?`) isolating untrusted payload input from SQL execution vectors.
  * Isolated Docker bridge network (`db:5432`) with mounted volume persistence (`taskdata`).
  * Interactive OpenAPI 3.0 contract served at `/docs`.

### 💼 [applyfolio](https://github.com/ernestmwangombe/applyfolio)
**Application Tracking & Business Process Engine**
* **Problem Solved:** Coordinates multi-stage application processing workflows and document status tracking through defined backend state transitions.
* **Architecture:** Node.js, Express, JavaScript (ES6+), Controller Logic Separation.
* **Key Features:** Modular Express route handlers, defined workflow state rules, and structured application lifecycle tracking.

### 🩺 [Nurse-Lilian-M-KE-Site](https://github.com/ernestmwangombe/Nurse-Lilian-M-KE-Site)
**Live Healthcare Professional Platform**
* **Purpose:** Production website developed and deployed for a private healthcare consultancy in Kenya.
* **Stack:** HTML5, CSS3, JavaScript, Client Care Gateway, Production Cloud Hosting.

### 🌐 [Live Portfolio Ingress](https://ernestmwangombe.netlify.app/)
**Consulting Gateway & Ingress Portal**
* **Purpose:** Public web interface showcasing active projects, client service offerings, and technical consulting options.
* **Stack:** Netlify Hosting, SSL/TLS Encryption, Custom Domain Ingress Routing.

---

## 🚀 Active Project in Development

### 📄 `ai-document-pipeline` (Target Showcase)
* **Objective:** Building an automated backend API that ingests PDF invoices and receipts, extracts structured data via OpenAI / Gemini APIs, validates payloads using Zod schemas, and persists verified records into PostgreSQL.
* **Current Phase:** Active repository development to expand service offerings into automated AI document extraction.

---

## 🛡️ Engineering Principles

1. **Defensive Input Parameterization:** Parameterize every SQL query (`$1`, `$2`, `?`) to strictly separate client payloads from database control logic.
2. **Explicit Security Perimeters:** Intercept unauthenticated incoming traffic using dedicated JWT Bearer token middleware before granting endpoint access.
3. **Layered Code Separation:** Maintain clear boundaries between HTTP routing, business controllers, OpenAPI contracts, and database connection pools.
4. **Environment Isolation:** Containerize development and production stacks with Docker Compose and keep credentials isolated in `.env` files.

---

## 💬 Consultation & Ingress

* **Need a technical audit or workflow automation for your firm?** I assist SMEs in automating manual file workflows and securing backend APIs.
* **Portfolio Gateway:** [ernestmwangombe.netlify.app](https://ernestmwangombe.netlify.app/)
* **GitHub Profile:** [github.com/ernestmwangombe](https://github.com/ernestmwangombe)
* **Location & Availability:** Nairobi, Kenya (UTC+3) | Available for global remote contracts and technical consulting
