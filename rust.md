# Rust Portfolio — Antonio Quental

> GitHub: [github.com/aquental](https://github.com/aquental)

---

## 1. Fundamentals & Learning

| Project | Description | Key Topics |
|---------|-------------|------------|
| [100-exercises-to-learn-rust](https://github.com/aquental/100-exercises-to-learn-rust) | Mainmatter's self-paced Rust course | Ownership, borrowing, lifetimes, traits, error handling |
| [ultimate_rust_crash_course](https://github.com/aquental/ultimate_rust_crash_course) | Rust fundamentals course | Syntax, structs, enums, pattern matching |
| [ultimate_rust2](https://github.com/aquental/ultimate_rust2) | Intermediate Rust course | Closures, iterators, generics, smart pointers |
| [LearnRust](https://github.com/aquental/LearnRust) | Rust learning resources | Reference material |
| [rustStudyGroup](https://github.com/aquental/rustStudyGroup) | Collaborative study group | Community learning |
| [exercism](https://github.com/aquental/exercism) | Exercism practice exercises | Algorithms, idiomatic Rust |

---

## 2. Web & Backend

| Project | Description | Key Topics |
|---------|-------------|------------|
| [actix-web-demo](https://github.com/aquental/actix-web-demo) | Actix Web framework demo | HTTP servers, routing, middleware |
| [rust-web](https://github.com/aquental/rust-web) | Sample Rust web frameworks | Framework comparison |
| [rust-leptos](https://github.com/aquental/rust-leptos) | Leptos web app | Full-stack Rust, SSR, reactive UI |
| [rust-tokio](https://github.com/aquental/rust-tokio) | Tokio async runtime | Async/await, futures, concurrency |
| [protohackers](https://github.com/aquental/protohackers) | Protocol challenge solutions | TCP/UDP networking, protocol parsing |

---

## 3. Frontend & WebAssembly

| Project | Description | Key Topics |
|---------|-------------|------------|
| [front-yew](https://github.com/aquental/front-yew) | Frontend with Yew + Wasm | Component model, Wasm compilation |
| [rust-front-end](https://github.com/aquental/rust-front-end) | Yew frontend | Client-side Rust |
| [dioxus-one](https://github.com/aquental/dioxus-one) | Dioxus cross-platform samples | Cross-platform UI |
| [dioxus-sample](https://github.com/aquental/dioxus-sample) | Dioxus cross-platform samples | Mobile/desktop/web targets |
| [rust-wasm-1](https://github.com/aquental/rust-wasm-1) | Rust + WebAssembly | wasm-bindgen, wasm-pack |

---

## 4. Blockchain & Cryptography

| Project | Description | Key Topics |
|---------|-------------|------------|
| [rust-state-machine](https://github.com/aquental/rust-state-machine) | Basic blockchain in Rust | State machines, hashing, consensus |
| [rusty-wallet](https://github.com/aquental/rusty-wallet) | Wallet implementation | Key management, signing, cryptography |
| [zkRust](https://github.com/aquental/zkRust) | Zero Knowledge in Rust | ZK proofs, circuits |
| [rust_arith](https://github.com/aquental/rust_arith) | Arithmetic circuit compiler | Compiler design, finite fields |
| [frameless_template](https://github.com/aquental/frameless_template) | Polkadot frameless Substrate | Runtime development, FRAME-less |
| [rust-rag](https://github.com/aquental/rust-rag) | RAG implementation in Rust | Embeddings, vector search, LLM integration |

---

## 5. AI & Integrations

| Project | Description | Key Topics |
|---------|-------------|------------|
| [rust_rig_study](https://github.com/aquental/rust_rig_study) | RIG (Rust AI lib) projects | AI agents, LLM orchestration |
| [deepseek-rust-tutor](https://github.com/aquental/deepseek-rust-tutor) | Tutor using Deepseek | API integration, prompt engineering |
| [ai-rust-examples](https://github.com/aquental/ai-rust-examples) | Fermyon serverless AI apps | Serverless, Spin framework, inference |
| [rustJS](https://github.com/aquental/rustJS) | JS runtime inside Rust | FFI, embedding runtimes |

---

## 6. Systems & Utilities

| Project | Description | Key Topics |
|---------|-------------|------------|
| [rust-file](https://github.com/aquental/rust-file) | File manipulation | std::fs, I/O, error handling |
| [rust-plugin-extism](https://github.com/aquental/rust-plugin-extism) | Extism plugin system | Plugin architecture, Wasm host |
| [CodeCrafters-git](https://github.com/aquental/CodeCrafters-git) | Build your own Git | Binary formats, SHA hashing, trees |

---

## 7. Topic Coverage & Gap Analysis

### ✅ Well Covered

| Topic | Evidence |
|-------|----------|
| **Async / Concurrency** | rust-tokio, protohackers, actix-web-demo |
| **WebAssembly** | front-yew, rust-wasm-1, dioxus-*, rust-front-end |
| **Web Frameworks** | actix-web, leptos, rust-web |
| **Blockchain / Crypto** | 6+ projects across ZK, wallets, state machines |
| **AI / LLM Integration** | rust-rag, rig, deepseek-rust-tutor, ai-rust-examples |
| **Fundamentals** | 100-exercises, ultimate_rust 1 & 2, exercism |

### ⚠️ Gaps — Suggested Projects

| Gap | Why It Matters | Suggested Project |
|-----|---------------|-------------------|
| **CLI Tools** | Core Rust use case; shows `clap`, `serde`, `std::process` | Build a CLI data pipeline tool (e.g., CSV→JSON transformer with streaming) using `clap` + `serde` + `tokio::fs` |
| **Database / ORM** | Missing persistence layer experience | REST API with `sqlx` or `sea-orm` + PostgreSQL, including migrations and connection pooling |
| **Testing & CI** | No visible test-focused project | Add a project with `#[cfg(test)]`, property-based testing (`proptest`), integration tests, and a GitHub Actions CI pipeline |
| **Error Handling Patterns** | Implicit in courses but not showcased | Library crate using `thiserror` for library errors and `anyhow` for application errors, with custom error types |
| **FFI / C Interop** | Only rustJS touches interop | Rust wrapper around a C library (e.g., `libsodium` or `sqlite3`) using `bindgen` |
| **Embedded / no_std** | Completely absent | Blink LED or sensor reader on Raspberry Pi Pico using `embassy` or `rp2040-hal` |
| **gRPC / Microservices** | No service-to-service communication | Microservice pair using `tonic` (gRPC) with protobuf, health checks, and tracing |
| **Observability** | No tracing/logging/metrics project | Integrate `tracing` + `opentelemetry` + `metrics` into one of the existing web projects |
| **Packaging & Publishing** | No published crate | Extract a reusable module (e.g., from zkRust or rust-rag) and publish to crates.io |
| **Unsafe Rust & Macros** | Advanced topics not showcased | Custom derive macro crate, or a small data structure using `unsafe` with proper safety docs |

---

## 8. Recommended Priority (Top 5)

1. **CLI Tool** — Quick win, high visibility, demonstrates practical Rust
2. **Database-backed API** — Fills the biggest gap for backend credibility
3. **Testing + CI** — Can be added to existing projects; shows engineering maturity
4. **gRPC Microservice** — Differentiator for systems/infrastructure roles
5. **Published Crate** — Proves open-source contribution and API design skills

---

*Generated: March 2026*
