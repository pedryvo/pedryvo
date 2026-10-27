# Hi, I'm Pedro Ivo 👋

[![LinkedIn](https://img.shields.io/badge/LinkedIn-pedroyvo-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/pedroyvo)
[![GitHub](https://img.shields.io/badge/GitHub-pedryvo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/pedryvo)
[![Rust](https://img.shields.io/badge/Rust-Systems_%26_Backends-b7410e?style=flat-square&logo=rust&logoColor=white)](https://www.rust-lang.org/)
[![Ruby on Rails](https://img.shields.io/badge/Ruby_on_Rails-Full--Stack-CC0000?style=flat-square&logo=rubyonrails&logoColor=white)](https://rubyonrails.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-Next.js_%26_Node-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)

**Software Engineer · Systems & Backend Architecture · Rust, Ruby on Rails & TypeScript**  
📍 Vitória da Conquista, Bahia, Brazil · 🗣️ Portuguese (native) · English (full professional) · Spanish (limited working)

I build high-reliability backends, payment infrastructure, full-stack products, and clean-room systems reimplementations. My recent work spans **mission-critical fintech & SaaS backends in Rust**, **Node.js-to-Rust platform migrations**, **binary reverse engineering & deterministic simulation engines**, and **production web applications in Ruby on Rails and Next.js**.

I'm a hands-on, results-driven engineer with **4+ years of professional Ruby on Rails experience** — from B2B fintech MVPs to real-estate search platforms — and a background in Linux infrastructure going back to 2009. I care about clear communication, transparency with stakeholders, and shipping high-quality software.

---

## 💼 Experience

**Founder & Software Engineer (AI & Automation)** · *Ai-vo Labs* · Aug 2025 – Feb 2026  
Founded and led a consultancy for software development and AI solutions: web apps and APIs in Ruby on Rails, Node.js and Next.js; LLM-powered chatbots and agents (OpenAI, etc.); n8n automations and API orchestration; AWS/Vercel deployments with CI/CD; rapid MVPs and technical consulting on architecture, stack and product strategy.

**Ruby on Rails Developer** · *Órulo* · Apr 2024 – Jul 2025  
- Designed and built advanced real-estate search filters with **Elasticsearch**, improving query performance and UX;
- Built data-change request workflows with approval flows, reducing manual operations;
- Developed and optimized integrations with external **CRMs** for reliable property and lead sync;
- Fixed performance bottlenecks in APIs and background jobs; refactored legacy code and drove code reviews and testing.

**Ruby on Rails Developer** · *Nexoos* · Nov 2021 – Oct 2023  
- Took a **B2B financial product from MVP to production** (receivables anticipation), building scalable backend services and REST APIs;
- Migrated service logic to **AWS Lambda**, increasing scalability and reducing infrastructure costs;
- Kept high **RSpec** coverage for reliability in financial operations; applied SOLID principles in an agile team.

**Ruby on Rails Developer** · *Envixo* · Feb 2020 – Jun 2020  
Legacy Rails maintenance, data import automation with Roo, and **Magento / Shopify** API integrations.

<details>
<summary><b>Earlier experience (2009 – 2019)</b></summary>

- **IT Technician** · *Câmara Municipal de Vitória da Conquista* · Jan 2015 – Feb 2019  
  Ubuntu Linux servers and workstations, legislative government systems support; designed a **system-image cloning server that cut maintenance time from a full day to ~15 minutes**.
- **Intern** · *Receita Federal do Brasil* · Jun 2012 – Jun 2014  
  Intranet frontend customization on Python Zope/Plone, Noosfero-based internal social network, and **COBOL database to Excel conversion with AWK scripts**.
- **Intern** · *Faculdade Juvêncio Terra* · Jun 2009 – Feb 2011  
  Hardware assembly and maintenance, computer lab supervision, AV equipment setup.

</details>

---

## 🔬 Featured Open-Source & Reverse Engineering Projects

- **[`rrt2-decomp`](https://github.com/pedryvo/rrt2-decomp)** *(Rust · wgpu · Ghidra · Unicorn x86)*  
  Clean-room reverse engineering and modern cross-platform Rust reimplementation of *Railroad Tycoon II Platinum* (1998). Features a custom `wgpu` isometric renderer (native 1080p/4K), a differential x86 emulator test harness (Unicorn), a deterministic simulation core verified field-by-field against the original executable across 131 savegame scenarios, lockstep TCP multiplayer, map/scenario editor, and 6-language localization.

---

## 🏦 Production Systems & Architecture Highlights

- **Payment Orchestration & Anti-Fraud Core (Rust)**  
  Architected and hardened a high-assurance payment gateway and ledger system in Rust:
  - Per-provider and per-operation **circuit breakers** with probe windows, CloudWatch EMF telemetry, and automated alerting;
  - Pre-provider **card velocity anti-fraud buckets** (`429 VELOCITY_LIMIT_EXCEEDED` with `Retry-After`) and per-customer/currency billing limits;
  - End-to-end **chargeback & dispute state machines** integrated with payment providers, transactional outbox/Kafka events, and outbound webhooks;
  - Hardened operator console (TOTP 2FA with replay protection, account lockout, RBAC, CSRF, SSE live streams) backed by PostgreSQL, OpenAPI specs, ADRs, and **mutation testing** in CI.

- **Node.js-to-Rust Backend Migration (Rust / TypeScript)**  
  Led a high-throughput backend migration from Node.js/TypeScript to Rust with strict commit-by-commit parity auditing across co-production revenue splits, affiliate attribution, recurring subscriptions, LGPD/GDPR privacy exports, and load testing, alongside Cloudflare/AWS infrastructure for the platform's API, creator dashboard, and student portal.

- **Ruby on Rails & Full-Stack Product Engineering**  
  - **Rails 8 & Hotwire**: High-throughput APIs, background batch processing (`carts`, `clipefacil`, `vikapp`), and RSpec test suite optimization (`vcanews-mobile` — reduced full test suite runtime from **3m45s to 1.18s**).
  - **Next.js & TypeScript**: Full-stack applications with Prisma, PostgreSQL, Docker Compose SSR networking, and AI-driven workflows (`pharmarket`, `alugarcacamba`, `DestinyMatrix`, `vcanews-nextjs`, `aivohomepage`).

---

## 🛠️ Core Stack & Practices

| Domain | Technologies & Practices |
|---|---|
| **Languages** | Rust (2024 edition), Ruby, TypeScript / JavaScript, SQL, Bash, x86 Assembly (reading/RE) |
| **Backend & Systems** | Axum / Tokio, Ruby on Rails 8, Sinatra, Node.js, Next.js, REST & OpenAPI, Transactional Outbox, Kafka, SSE, Sidekiq |
| **Frontend** | Hotwire, Vue.js, Next.js / React, HTML / CSS |
| **Data & Storage** | PostgreSQL, MySQL, Redis, Elasticsearch, Prisma, SQLx, dBase/Clipper binary formats, S3 / ActiveStorage |
| **AI & Automation** | LLM integrations (OpenAI), chatbots & agents, n8n workflows, API orchestration |
| **Reliability & Testing** | Mutation Testing, Differential Emulation (Unicorn), RSpec / Capybara, TDD, Wiremock, Property & Load Testing |
| **Reverse Engineering** | Ghidra, REA MCP, PE32 / .NET CLI metadata analysis, binary protocol & file format reconstruction |
| **DevOps & Cloud** | AWS (Lambda, CloudWatch), Vercel, Cloudflare, Docker & Docker Compose, GitHub Actions (multi-OS release pipelines: `.AppImage`, `.dmg`, Inno Setup `.exe`), Linux |

---

## 🎓 Education & Certifications

- **Associate Degree (CST) in Systems Analysis and Development** — *UNINTER Centro Universitário Internacional* (2016 – 2018)
- TDD com Ruby on Rails, RSpec e Capybara
- Ruby on Rails: Active Record — Interações com Banco de Dados
- Essentials in JavaScript ES6 — A Fun and Clear Introduction
- Introdução ao jQuery

---

## 📫 Let's Connect

- 💼 **LinkedIn**: [linkedin.com/in/pedroyvo](https://linkedin.com/in/pedroyvo)
- 📩 **Email**: [pedryvo@gmail.com](mailto:pedryvo@gmail.com)
