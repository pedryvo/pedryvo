# Hi, I'm Pedro Ivo 👋

[![LinkedIn](https://img.shields.io/badge/LinkedIn-pedroyvo-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/pedroyvo)
[![GitHub](https://img.shields.io/badge/GitHub-pedryvo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/pedryvo)
[![Rust](https://img.shields.io/badge/Rust-Systems_%26_Backends-b7410e?style=flat-square&logo=rust&logoColor=white)](https://www.rust-lang.org/)
[![Ruby on Rails](https://img.shields.io/badge/Ruby_on_Rails-Full--Stack-CC0000?style=flat-square&logo=rubyonrails&logoColor=white)](https://rubyonrails.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-Next.js_%26_Node-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)

**Software Engineer · Systems & Backend Architecture · Rust, Ruby on Rails & TypeScript**

I build high-reliability backends, payment infrastructure, full-stack products, and clean-room systems reimplementations. My recent work spans **mission-critical fintech & SaaS backends in Rust**, **Node.js-to-Rust platform migrations**, **binary reverse engineering & deterministic simulation engines**, and **production web applications in Ruby on Rails and Next.js**.

---

## 🔬 Featured Open-Source & Reverse Engineering Projects

- **[`rrt2-decomp`](https://github.com/pedryvo/rrt2-decomp)** *(Rust · wgpu · Ghidra · Unicorn x86)*  
  Clean-room reverse engineering and modern cross-platform Rust reimplementation of *Railroad Tycoon II Platinum* (1998). Features a custom `wgpu` isometric renderer (native 1080p/4K), a differential x86 emulator test harness (Unicorn), a deterministic simulation core verified field-by-field against the original executable across 131 savegame scenarios, lockstep TCP multiplayer, map/scenario editor, and 6-language localization.

- **[`playlist-decomp`](https://github.com/pedryvo/playlist-decomp)** *(Rust · Audio Engine · Cross-Platform)*  
  Clean-room reverse engineering and native cross-platform Rust reimplementation of the *Playlist Digital 5* radio broadcast automation suite for Windows, Linux, and macOS. Implements bit-accurate parsers for legacy dBase III+ (`.DBF`/`.DBT`) databases, Clipper `.NTX` B-tree indices, `.pkinfo` waveform peak envelopes, 24-hour broadcast schedule grids, dual-deck crossfading playout, `HTU300` weather telemetry, satellite DTMF switching (`Ligacao`), RDS generation, and 5-language localization.

---

## 🏦 Production Systems & Architecture Highlights

- **Payment Orchestration & Anti-Fraud Core (`corepay` — Rust)**  
  Architected and hardened a high-assurance payment gateway and ledger system in Rust:
  - Per-provider and per-operation **circuit breakers** with probe windows, CloudWatch EMF telemetry, and automated alerting;
  - Pre-provider **card velocity anti-fraud buckets** (`429 VELOCITY_LIMIT_EXCEEDED` with `Retry-After`) and per-customer/currency billing limits;
  - End-to-end **chargeback & dispute state machines** integrated with payment providers (Asaas), transactional outbox/Kafka events, and outbound webhooks;
  - Hardened operator console (TOTP 2FA with replay protection, account lockout, RBAC, CSRF, SSE live streams) backed by PostgreSQL, OpenAPI specs, ADRs, and **mutation testing** in CI.

- **Node.js-to-Rust Backend Migration (`backend-rust-mindflow` & `*jspay` — Rust / TypeScript)**  
  Led a high-throughput backend migration from Node.js/TypeScript to Rust with strict commit-by-commit parity auditing across co-production revenue splits, affiliate attribution, recurring subscriptions, LGPD/GDPR privacy exports, and load testing, alongside Cloudflare/AWS infrastructure for the platform's API, creator dashboard, and student portal.

- **Ruby on Rails & Full-Stack Product Engineering**  
  - **Rails 8 & Hotwire**: High-throughput APIs, background batch processing (`carts`, `clipefacil`, `vikapp`), and RSpec test suite optimization (`vcanews-mobile` — reduced full test suite runtime from **3m45s to 1.18s**).
  - **Next.js & TypeScript**: Full-stack applications with Prisma, PostgreSQL, Docker Compose SSR networking, and AI-driven workflows (`pharmarket`, `alugarcacamba`, `DestinyMatrix`, `vcanews-nextjs`, `aivohomepage`).

---

## 🛠️ Core Stack & Practices

| Domain | Technologies & Practices |
|---|---|
| **Languages** | Rust (2024 edition), Ruby, TypeScript / JavaScript, SQL, Bash, x86 Assembly (reading/RE) |
| **Backend & Systems** | Axum / Tokio, Ruby on Rails 8, Node.js, Next.js, REST & OpenAPI, Transactional Outbox, Kafka, SSE |
| **Data & Storage** | PostgreSQL, MySQL, Redis, Prisma, SQLx, dBase/Clipper binary formats, S3 / ActiveStorage |
| **Reliability & Testing** | Mutation Testing, Differential Emulation (Unicorn), RSpec / Capybara, Wiremock, Property & Load Testing |
| **Reverse Engineering** | Ghidra, REA MCP, PE32 / .NET CLI metadata analysis, binary protocol & file format reconstruction |
| **DevOps & Cloud** | AWS, Cloudflare, Docker & Docker Compose, GitHub Actions (multi-OS release pipelines: `.AppImage`, `.dmg`, Inno Setup `.exe`), Linux |

---

## 📫 Let's Connect

- 💼 **LinkedIn**: [linkedin.com/in/pedroyvo](https://linkedin.com/in/pedroyvo)
- 📩 **Email**: [pedryvo@gmail.com](mailto:pedryvo@gmail.com)
