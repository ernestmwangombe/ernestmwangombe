# Ernest Mlati Mwang'ombe

### IT Consultant | Backend & AI Systems Engineer

> *"I build secure backend APIs and data pipelines that turn unstructured business documents into structured records, with a focus on reducing manual data entry and protecting database integrity."*

I am an IT Consultant based in Nairobi, Kenya (UTC+3), applying a background in network security, server administration, and Linux systems to backend API development, database systems, and automated document processing.

---

## 🎯 Technical Capabilities & Stack Readiness

| Domain               | Proven Capabilities (Supported by Code Evidence)                                                                                    | Active Engineering Roadmap                                        |
| :------------------- | :---------------------------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------- |
| **Backend & APIs**   | Express 5.2.1 REST APIs, Modular Routing, Middleware Gates, Interactive Swagger UI (`/docs`), OpenAPI 3.0 Specs                     | Strict TypeScript API Architecture, Zod Runtime Schema Validation |
| **Security & Auth**  | Supabase Auth Integration (`@supabase/supabase-js`), JWT Bearer Token Verification, Parameterized SQL (`$1`, `$2`, `?`)             | Role-Based Access Control (RBAC), Rate-Limiting Perimeter Defense |
| **Databases**        | PostgreSQL 16 Alpine, `pg.Pool` Connection Pooling, SQLite Write-Ahead Logging (WAL) Mode (`better-sqlite3`), Database Transactions | Relational Database Migrations, Multi-Tenant Schema Isolation     |
| **Infrastructure**   | Docker, Docker Compose, Internal Bridge Networks (`db:5432`), Mounted Volume Persistence (`taskdata`), Netlify Hosting              | Automated CI/CD Pipelines, Production Server Hardening            |
| **Workflow Systems** | Application State Engines (`applyfolio`), Controller Logic Separation, Structured Application Workflows                             | LLM API Document Ingestion, Structured JSON Extraction Pipelines  |

---

## 📂 Featured Repositories & Live Projects

### 🔒 [Auth-Login-protect](https://github.com/ernestmwangombe/Auth-Login-protect)

**Backend Authentication & Supabase Auth API Gateway**

* **Problem Solved:** Protects selected backend resources through authenticated access and verified session tokens.
* **Architecture:** Node.js, Express 5.2.1, Supabase Auth (`@supabase/supabase-js`), Custom JWT Bearer Middleware, OpenAPI 3.0, Swagger UI (`swagger-ui-express`).
* **Key Implementation Details:**

  * Custom `requireAuth` middleware verifies Supabase JWT bearer tokens before granting access to protected routes.
  * Authentication endpoints (`/auth/signup`, `/auth/login`, `/auth/logout`) manage authentication flows.
  * Interactive Swagger UI documentation is available through `/docs` with `BearerAuth` testing.
  * Environment secrets are isolated through `.env` configuration, with data-handling controls implemented within the application.

### 🔹 [task-management-api](https://github.com/ernestmwangombe/task-management-api)

**Containerized REST API & Dual-Database Persistence Engine**

* **Problem Solved:** Provides persistent transactional record management across containerized environments using PostgreSQL and SQLite.
* **Architecture:** Express 5.2.1, Node 18 Alpine (`node:18-alpine`), PostgreSQL 16 (Alpine), SQLite 3 (WAL Mode), Docker Compose, OpenAPI 3.0.
* **Key Implementation Details:**

  * `pg.Pool` provides PostgreSQL connection pooling through `db.js`.
  * `better-sqlite3` uses Write-Ahead Logging (`PRAGMA journal_mode = WAL`) and database transactions.
  * Parameterized SQL queries (`$1`, `$2`, `$3`) separate query parameters from SQL statements.
  * Docker Compose provides an isolated bridge network (`db:5432`) with mounted volume storage (`taskdata`).
  * An interactive OpenAPI 3.0 specification is served through `/docs`.

### 💼 [applyfolio](https://github.com/ernestmwangombe/applyfolio)

**Application Tracking & Business Process Engine**

* **Problem Solved:** Coordinates multi-stage application processing workflows and status tracking through defined state transitions.
* **Architecture:** Node.js, Express, JavaScript (ES6+), Modular Routing.
* **Key Implementation Details:** Controller-service separation, defined lifecycle state transitions, and structured payload handling.

### 🩺 [Nurse-Lilian-M-KE-Site](https://github.com/ernestmwangombe/Nurse-Lilian-M-KE-Site)

**Live Healthcare Consultancy Platform**

* **Purpose:** Website developed and deployed for a private healthcare consultancy in Kenya.
* **Stack:** HTML5, CSS3, JavaScript, Client Intake Portal, Cloud Hosting.

### 🌐 [Live Portfolio Gateway](https://ernestmwangombe.netlify.app/)

**Consulting Portal & Public Ingress**

* **Purpose:** Public website showcasing backend engineering projects, service offerings, and technical contact options.
* **Stack:** Netlify Hosting, SSL/TLS, Custom Domain Routing.

---

## 🚀 Active Engineering Roadmap

### 📄 `ai-document-pipeline`

**Target Showcase — AI Document Extraction Backend**

* **Objective:** Developing a backend API that ingests PDF invoices and receipts, extracts structured JSON payloads through OpenAI/Gemini LLM APIs, validates schemas using Zod, and persists verified records into PostgreSQL.
* **Current Phase:** Active repository development focused on building evidence for AI-powered document extraction and document-to-database workflows.

---

## 🛡️ Core Engineering Principles

1. **Defensive Input Parameterization:** Use parameterized database queries to separate client-supplied values from SQL statements.
2. **Explicit Authentication Boundaries:** Use JWT Bearer middleware to verify authenticated requests before allowing access to protected routes.
3. **Contract-First Documentation:** Maintain interactive OpenAPI 3.0 Swagger UI documentation for API endpoints.
4. **Environment Isolation:** Containerize development stacks with Docker Compose and keep application secrets in environment configuration.

---

## 💬 Technical Audits & Consulting

I help professional service firms and SMEs identify manual data-entry bottlenecks, improve backend API security, and design practical workflow automation systems.

### Consulting Engagement Framework

1. **Technical Audit:** Review manual file-processing workflows, backend architecture, and API security controls.
2. **Architecture & Strategy:** Design backend APIs, database systems, and document automation workflows around the client's operational requirements.
3. **Implementation:** Build documented backend services using technologies such as Express, PostgreSQL, Docker, and API integrations.
4. **Deployment & Handover:** Package and document the resulting systems for deployment and continued maintenance.

**Portfolio Gateway:** [ernestmwangombe.netlify.app](https://ernestmwangombe.netlify.app/)

**GitHub Profile:** [github.com/ernestmwangombe](https://github.com/ernestmwangombe)

**Location & Availability:** Nairobi, Kenya (UTC+3) | Open for global remote contracts & technical consulting
