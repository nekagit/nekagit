<div align="center">

# Hi 👋 I'm Nenad Kalicanin

### Senior Full-Stack Engineer · AI Architect · Technical Mentor

I build production-ready web, mobile, cloud, and AI systems — from system architecture and APIs to polished interfaces, CI/CD, and deployment.

<p>
  <a href="https://nenadkalicanin.com"><img src="https://img.shields.io/badge/Portfolio-nenadkalicanin.com-0A66C2?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio" /></a>
  <a href="https://karaweiss.org"><img src="https://img.shields.io/badge/Company-Kara%20%26%20Wei%C3%9F-111827?style=for-the-badge&logo=link&logoColor=white" alt="Kara & Weiß" /></a>
  <a href="mailto:contact@nenadkalicanin.com"><img src="https://img.shields.io/badge/Contact-Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/nenad-kalicanin-23924119a/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>

Germany 🇩🇪 · Šabac, Serbia 🇷🇸 · German · English · Serbian · Spanish · Turkish

</div>

---

## About me

- Full-stack engineer and AI architect with 8+ years in IT consulting
- B.Sc. in Computer Science from TU Dortmund
- 400+ developers mentored through software engineering, Python, Git, web technologies, and architecture
- Experienced across frontend, backend, mobile, cloud infrastructure, security, and autonomous AI workflows
- Currently building with Kara & Weiß
- Open to senior engineering roles, AI consulting, and high-impact architecture collaborations

## What I build

| Area | Focus |
| --- | --- |
| AI & autonomous systems | Local LLMs, RAG pipelines, vector search, agent tooling, and multi-LLM workflows |
| Full-stack products | Scalable web applications, SaaS platforms, APIs, dashboards, and e-commerce |
| Mobile & cloud | Cross-platform Flutter applications, containerized services, CI/CD, AWS, and Azure |
| Engineering quality | Clean architecture, testing, code review, accessibility, security, and maintainable delivery |
| Teaching & mentoring | Practical software engineering, algorithms, Python, Git, React, Flutter, and technical communication |

## Selected work

I design and ship complete product systems: user-facing applications, AI workflows, APIs, data layers, security boundaries, and production operations. The projects below represent the strongest combination of product thinking, full-stack engineering, AI integration, and real deployment work.

### Bordai — AI-native workspace and automation canvas

**Product surface:** [noticebook.karaweiss.org](https://noticebook.karaweiss.org) · internal product by [Kara & Weiß](https://karaweiss.org)

Bordai is an AI-powered workspace that combines an infinite whiteboard, knowledge base, project system, automation layer, and developer control plane in one product.

- **Product capabilities:** documents, tables, formulas, kanban boards, to-dos, tickets, schedules, websites, media, knowledge sources, analytics, agents, prompts, and deployment workflows as connected canvas nodes
- **AI capabilities:** board-native chat and tool calling, per-board knowledge/RAG, autonomous agent runs, AI-generated topic boards, local-first model routing, adaptive model selection, cost tracking, and the Piepmatz voice interface
- **Engineering focus:** safe-by-default writes, snapshots, additive scans, permission checks, authentication, provider boundaries, inspectable agent runs, and production-oriented testing
- **Stack:** Nuxt 3, Vue 3, TypeScript, Tailwind, Supabase/Postgres, authentication, Vitest, Playwright, ESLint, and CI
- **Status:** production platform undergoing an active migration and expansion

### KW Organizer — authenticated project and operations platform

**Product surfaces:** [organizer.karaweiss.org](https://organizer.karaweiss.org) · [okk.karaweiss.org](https://okk.karaweiss.org)

KW Organizer is a private workspace for project execution, calendar planning, documents, secrets, and operator-managed workflows.

- **Core architecture:** authenticated Next.js application with domain-driven design and test-driven development
- **Data layer:** Drizzle with SQLite in the personal deployment and a PostgreSQL-oriented organization deployment
- **Product value:** brings planning, execution, documentation, and operational context into one controlled workspace
- **Engineering focus:** ownership boundaries, protected workflows, migrations, deployment discipline, and maintainable internal tooling
- **Source:** private repository; the product is actively used inside the Kara & Weiß platform ecosystem

### AI App Store and agent product ecosystem

**Product surfaces:** [apps.karaweiss.org](https://apps.karaweiss.org) · [aistore.karaweiss.org](https://aistore.karaweiss.org) · [agentstore.karaweiss.org](https://agentstore.karaweiss.org)

The AI App Store is a curated marketplace and product layer for AI-powered applications, agents, and supporting services.

- **Product capabilities:** application discovery, curated product catalogues, marketing surfaces, app entry points, and integration with the broader Kara & Weiß platform
- **Engineering focus:** separate product surfaces, versioned application delivery, protected access, and a clear boundary between catalogue, runtime, and deployment concerns
- **Stack:** TypeScript and JavaScript with independently deployable web surfaces
- **Status:** own product in active development with partially live surfaces
- **Source:** private repositories; live domains document the product direction and user-facing surfaces

### AI CLI and local-first LLM infrastructure

**Product surfaces:** [aicli.karaweiss.org](https://aicli.karaweiss.org) · [aicli.nk-app.com](https://aicli.nk-app.com) · [llm.nk-app.com](https://llm.nk-app.com) · [agents.karaweiss.org](https://agents.karaweiss.org)

This platform connects a standalone developer CLI, agent runtime, model gateway, local inference, and owner-side observability.

- **AI CLI:** Go-based \`ai\` hub with interactive agent chat, read-only planning, session continuation, governed work units, module control, and repository-aware workflows
- **Runtime architecture:** separated model gateway and agent runtime, scoped daemon actions, permission modes, approval boundaries, cancellation, event streams, and per-application identities
- **Model operations:** local Ollama, OpenAI-compatible endpoints, LiteLLM routing, verified capability reports, model discovery, inference smoke tests, and explicit free-only execution paths
- **Developer tooling:** Graphify code indexing and query, repository context, bounded context attachment, agent telemetry, and safe execution contracts
- **Security posture:** no credentials in the browser, no silent provider fallbacks, no automatic paid retries, bounded evidence, owner-only dashboards, and protected Cloudflare surfaces
- **Stack:** Go, Python, JavaScript, local model runtimes, LiteLLM, Docker, Linux, systemd, Nginx, and Cloudflare Access
- **Source:** private infrastructure repositories and local platform services

### KW Design — AI-assisted visual development environment

**Product surfaces:** [design.karaweiss.org](https://design.karaweiss.org) · [design.nk-app.com](https://design.nk-app.com)

KW Design is an infinite board for designing Vue components, pages, and complete websites with live previews and an AI assistant.

- **Design workflow:** artboards, components, instances, pages, site layouts, design tokens, responsive previews, sharing, and Nuxt project export
- **AI workflow:** create and edit components, build pages from a brief, generate site structures, restyle designs, and refine imported sections
- **Web import:** capture a webpage, segment semantic sections, infer design tokens and accessibility signals, then rebuild components or compare them against pixel-diff references
- **Safety model:** sandboxed preview frames, SSRF protection, scoped asset proxying, and isolated execution for user- or AI-authored components
- **Stack:** Vue, Nuxt, TypeScript, CodeMirror, Playwright, Sharp, pixel comparison, and server-side rendering

### Music Playlist Studio — cache-first media organization

**Product surface:** [music.nk-app.com](https://music.nk-app.com)

Music Playlist Studio is a browser-based YouTube playlist organizer with a production API and a deliberate separation between cached library data and live mutations.

- **Product capabilities:** playlist galleries, search, sorting, duplicate discovery, bounded loading, track selection, private playlist creation, sync states, and light/dark themes
- **AI workflow:** reviewable plan previews for language- and content-targeted playlist changes; proposed mutations are shown before explicit execution
- **Reliability:** cache-first library loading, background jobs, request IDs, reload recovery, bounded upstream calls, and clear partial-result states
- **Security:** Cloudflare Access, server-side credentials, no personal library data in browser storage, and no automatic retry of interrupted mutations
- **Stack:** JavaScript, HTML/CSS, Node.js, YouTube API integration, Nginx, systemd, Playwright, and backend tests

### Casa Petrada — production e-commerce platform

**Product surface:** [casa-petrada.de](https://casa-petrada.de) · development surface: [dev.karaweiss.org](https://dev.karaweiss.org)

Casa Petrada is an e-commerce storefront for handmade Frida-Kahlo-themed products, with a modern storefront, administration tooling, and catalogue workflows.

- **Frontend:** Nuxt 4 SSR storefront replacing the earlier Vite and Express implementation
- **Operations:** read-only Next.js administration dashboard over Supabase/Postgres data
- **Commerce features:** product catalogue, web/PDF catalogue support, product management, and the “Mai” workspace for ideas, specifications, waves, and tickets
- **Engineering focus:** SSR performance, migration planning, database-backed administration, maintainable product workflows, and customer-facing delivery
- **Stack:** TypeScript, HTML/CSS, Nuxt 4, Next.js, Supabase, and PostgreSQL
- **Source:** private product repositories; the customer-facing domain is public

### Dev-Native Cybersecurity and SecureScan

**Public repository:** [dev-native-cybersecurity](https://github.com/nekagit/dev-native-cybersecurity)

A developer-native cybersecurity workspace combining practical security education, a SecureScan SaaS MVP, and a startup operating playbook.

- **Learn:** a Docusaurus course with approximately 95 chapters covering practical application security and developer workflows
- **SecureScan:** Next.js 15 security SaaS MVP with a product-oriented implementation path
- **Startup layer:** business playbooks, go-to-market thinking, pricing, and delivery principles
- **Stack:** TypeScript, Next.js, Docusaurus, Node.js, and security-focused product engineering
- **Collaboration:** co-founded with a DevSecOps partner in Dortmund, Germany

### Technical education and training systems

**Public repositories:** [masterschool-material](https://github.com/nekagit/masterschool-material) · [ProjectX](https://github.com/nekagit/ProjectX) · **Delivery surface:** [teaching.nk-app.com](https://teaching.nk-app.com)

My teaching work turns software engineering concepts into structured, testable learning experiences.

- **AI in Production:** material covering execution patterns, release manifests, structured output validation, environment separation, readiness checks, behaviour evaluations, and rollback decisions
- **Python fundamentals:** a 100-function exercise set covering strings, collections, loops, mathematics, edge cases, code quality, and collaborative Git workflows
- **Training delivery:** practical instruction in Python, object-oriented design, Git, web technologies, software architecture, testing, and clean code
- **Engineering principle:** production readiness is demonstrated through behaviour, validation, observability, and rollback—not merely by having a running process

### Music notation and algorithmic research

**Project family:** ZekiMusic / TransposerAI · private research and product repositories

This work explores music software, algorithmic transposition, and digital notation for Turkish classical music.

- Web-based notation editor and sheet-music tooling
- MusicXML parsing, transposition, and composition workflows
- Interactive rendering with VexFlow and audio interaction with Tone.js
- A domain where academic research, algorithms, frontend engineering, and creative software meet

### Public portfolio and engineering profile

- [nenadkalicanin.com](https://nenadkalicanin.com) — portfolio, projects, experience, and professional credentials
- [nekagit/nenadkalicanin.com](https://github.com/nekagit/nenadkalicanin.com) — public portfolio source
- [Kara & Weiß](https://karaweiss.org) — company website and engineering work
- [GitHub profile](https://github.com/nekagit) — public repositories, technical training material, and this profile README

## Experience

| Period | Company | Focus |
| --- | --- | --- |
| Current | [Kara & Weiß](https://karaweiss.org) | Co-founder & Full-Stack Developer |
| Previous | OrgaTech GmbH | IT consulting and software development |
| Previous | qmbase GmbH | Quality management and digital solutions |
| Previous | bytes Coding GmbH | Software development, consulting, and training |

## Tech stack

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" alt="Flutter" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="Azure" />
</p>

**Frontend:** React, Next.js, Vue, Nuxt, TypeScript, HTML, CSS, Sass, Tailwind CSS, Pinia, Zustand

**Backend & data:** Python, FastAPI, Node.js, Bun, Java, Spring, C#, ASP.NET Core, PHP, Laravel, PostgreSQL, MySQL, MongoDB, GraphQL, REST APIs

**AI & security:** Local LLMs, RAG, vector databases, autonomous agents, OpenAI APIs, OWASP, secure application design

**Cloud & DevOps:** AWS, Microsoft Azure, Docker, Kubernetes, Terraform, Azure DevOps, CI/CD, Linux

**Mobile & quality:** Flutter, React Native, Cypress, testing, accessibility, code review, clean architecture

## Education & credentials

- **B.Sc. Computer Science** — TU Dortmund
- **Microsoft Azure Fundamentals (AZ-900)**

## Let's connect

If you are hiring for a senior engineering role, need help designing an AI-enabled product, or want to discuss a technical collaboration:

- 📧 [nenad99@hotmail.de](mailto:nenad99@hotmail.de)
- 🌐 [nenadkalicanin.com](https://nenadkalicanin.com)
- 🏢 [Kara & Weiß](https://karaweiss.org)
- 💼 [LinkedIn](https://www.linkedin.com/in/nenad-kalicanin-23924119a/)
- 🐙 [GitHub](https://github.com/nekagit)

<sub>This is the profile README for <a href="https://github.com/nekagit">@nekagit</a>.</sub>
