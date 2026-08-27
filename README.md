# Hi, I'm Kerem Oğur

I build software that stays close to the work: developer tools that inspect real projects, focused desktop utilities, and full-stack applications with clear API and data boundaries.

## About Me

I enjoy working across the line between systems code and product interfaces. My projects have taken me from native Windows behavior and process orchestration to backend services, relational data, and React frontends.

I care about local control, observable behavior, and being precise about what software can actually prove.

## What I Build

- Developer tooling for repository analysis, automation, and software verification
- Native desktop utilities with compact, purpose-built interfaces
- Frontend/backend applications with tested APIs and relational data models
- Local-first workflows with explicit security and trust boundaries

## Featured Project — Checker

**Checker** is a local deterministic software verification tool built to answer a practical question: what can this repository actually prove right now? It combines a framework-independent Go core, a Wails and React desktop interface, and local SQLite evidence storage.

Its verification system includes:

- **Project-owned authority discovery** that finds explicit CI commands, recognized task scripts, manifests, and tool configuration, then preserves precedence and provenance instead of guessing a replacement command.
- **Composable language profiles and Fast, Standard, and Full modes** for building an evidence-dependent verification portfolio across mixed-language workspaces.
- **Real tool execution** for supported build, test, lint, type-check, format, audit, and security authorities through bounded executable-and-argument processes rather than an implicit shell.
- **Static and semantic analysis over a shared source snapshot**, including supported API/route, event, dependency-injection, configuration, data, and schema connectivity.
- **Framework-aware Python semantics** for explicit, version-bounded Flask, Django, and FastAPI routes, composition, dependencies, and model relationships, while dynamic behavior remains unverified.
- **Checker-owned isolated Python environments** with explicit preparation, exact interpreter and dependency binding, and reusable sealed evidence outside project source.
- **Source protection for write-capable checks**, with declared output boundaries and rejection when protected source or authority files change unexpectedly.
- **Evidence-backed, fail-closed outcomes** that keep project failures, unavailable prerequisites, unsupported behavior, tool failures, stale evidence, and incomplete proof distinct.
- **Local security analysis** with bounded scanning and secret masking before findings, logs, events, or persisted evidence leave the analysis boundary.

Checker is deliberately not an AI coding assistant. It is the deterministic verification layer that evaluates project state using current repository evidence and real tools.

## Tech I Work With

- **Languages:** Go, TypeScript, JavaScript, Rust, C#, SQL, CSS
- **Desktop:** Wails, Tauri, Windows APIs, WebView2
- **Web:** React, Vite, Fastify, Node.js, Tailwind CSS, TanStack Query, Zod
- **Data:** SQLite, PostgreSQL, Prisma
- **Tooling and delivery:** Vitest, Playwright, ESLint, pnpm, Turborepo, Docker Compose, GitHub Actions

## Interests

- Developer tooling and deterministic verification
- Local-first software and explicit trust boundaries
- Static and semantic analysis with honest limits
- Native desktop behavior and frontend/backend integration
- Data integrity, testing, and reproducible automation
