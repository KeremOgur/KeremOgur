# Hi, I'm Kerem Oğur

I build software around explicit system boundaries, reproducible behavior, and evidence-backed correctness.

My work spans deterministic developer tooling, native desktop systems, full-stack workflow platforms, and optimization-backed applications. I am especially interested in software where correctness depends on more than a successful request: authorization scope, state transitions, data integrity, concurrency, reproducibility, and the ability to explain why a result should be trusted.

## About Me

I tend to work on systems where several boundaries meet at once: application logic, operating-system behavior, relational data, user-facing interfaces, background execution, and external tooling.

I care about making those boundaries explicit.

That has led me to projects involving deterministic repository verification, process orchestration, scoped authorization, transactional workflows, concurrent state protection, optimization pipelines, and reproducible system tests.

I prefer systems that can distinguish between what is known, what is inferred, what failed, and what remains unverified.

## What I Build

- Deterministic developer tooling for repository analysis, automation, and software verification
- Native desktop utilities with compact, purpose-built interfaces
- Full-stack systems with explicit API, authorization, data, and workflow boundaries
- Optimization-backed applications with isolated decision engines and transactional validation
- Local-first workflows with controlled trust boundaries and observable behavior
- Verification pipelines that test not only happy paths, but also concurrency, failure, recovery, and scope isolation

---

# Featured Project — Checker

**Checker** is a local deterministic software verification tool built to answer a practical question:

> What can this repository actually prove right now?

It combines a framework-independent Go core, a Wails and React desktop interface, and local SQLite evidence storage.

Its verification system includes:

- Project-owned authority discovery that finds explicit CI commands, recognized task scripts, manifests, and tool configuration, then preserves precedence and provenance instead of guessing replacement commands.
- Composable language profiles and Fast, Standard, and Full modes for building an evidence-dependent verification portfolio across mixed-language workspaces.
- Real tool execution for supported build, test, lint, type-check, format, audit, and security authorities through bounded executable-and-argument processes rather than an implicit shell.
- Static and semantic analysis over a shared source snapshot, including supported API/route, event, dependency-injection, configuration, data, and schema connectivity.
- Framework-aware Python semantics for explicit, version-bounded Flask, Django, and FastAPI routes, composition, dependencies, and model relationships, while dynamic behavior remains unverified.
- Checker-owned isolated Python environments with explicit preparation, exact interpreter and dependency binding, and reusable sealed evidence outside project source.
- Source protection for write-capable checks, with declared output boundaries and rejection when protected source or authority files change unexpectedly.
- Evidence-backed, fail-closed outcomes that keep project failures, unavailable prerequisites, unsupported behavior, tool failures, stale evidence, and incomplete proof distinct.
- Local security analysis with bounded scanning and secret masking before findings, logs, events, or persisted evidence leave the analysis boundary.

Checker is deliberately not an AI coding assistant.

It is the deterministic verification layer that evaluates project state using current repository evidence and real tools.

---

# Featured Project — 3+1 Vocational Practice Education Management System

[3+1 Vocational Practice Education Management System](https://github.com/KeremOgur/3plus1-Mesleki-Uygulama-Egitimi-Yonetim-Sistemi) is a workflow-heavy academic management system designed around explicit authorization scopes, transactional state transitions, relational integrity, and optimization-backed placement.

The system models the complete lifecycle of vocational workplace education while keeping institutional decisions, student visibility, company eligibility, and placement constraints separated at the application and database layers.

## Architectural Characteristics

- Program-scoped and institution-scoped authorization enforced server-side rather than only at the interface layer.
- Stateful workflows for applications, offers, preferences, placement, training, reporting, evaluation, publication, and appeals.
- PostgreSQL constraints used alongside application validation for invariants that must survive concurrent requests.
- Queue-backed placement execution with immutable input snapshots.
- Python and OR-Tools isolated from the transactional application database.
- Optimizer output treated as untrusted data and revalidated by Laravel before persistence.
- Preference and transportation scoring separated from GNO-based tie-breaking.
- Explicit handling of insufficient capacity, invalid placements, stale updates, duplicate requests, and concurrent assignment races.
- Private document storage, quarantine states, scoped downloads, retention metadata, and controlled failure behavior for unavailable integrations.
- OpenAPI-backed HTTP contracts with regression checks against implemented routes.
- Persistent demo data for validating program-level isolation between students and company offers.

## Core System Areas

- Student applications and eligibility workflows
- Program-scoped company and placement offers
- Ranked student preferences
- Role- and scope-based authorization
- Company, branch, trainer, protocol, and capacity management
- Queue-backed student–company matching
- Preference and transportation weighted placement scoring
- Weekly activity reports and attendance tracking
- Adviser and workplace trainer approval flows
- Digital portfolios and supporting evidence
- Occupational safety, insurance, risk, and incident records
- Rubric-based evaluation and final success calculation
- Appeals and placement change workflows
- Document quarantine and private file access controls
- Backup/restore, concurrency, API, and regression testing

## Matching Pipeline

The matching pipeline keeps optimization isolated from the application database:

**Laravel → Queue → Immutable Snapshot → Python / OR-Tools → JSON Result → Laravel Validation → PostgreSQL**

Python does not directly mutate application data.

The Laravel layer validates optimizer output against hard constraints before accepting placement results.

This separation keeps optimization logic powerful without giving the optimizer direct authority over transactional system state.

## Verification

The system is tested beyond controller-level happy paths.

Its verification suite covers:

- Cross-role authorization and IDOR boundaries
- Program-level offer isolation
- End-to-end student lifecycle transitions
- Concurrent capacity and placement races
- Optimizer determinism and hard-constraint validation
- Database schema integrity and migration behavior
- Real pg_dump / pg_restore recovery
- Queue interruption and recovery
- MFA and session boundaries
- Document quarantine and private storage behavior
- API/OpenAPI consistency
- Large-scale optimizer scenarios

The goal is not to claim universal correctness, but to make the system's verified boundaries explicit.

This repository represents a **local/demo academic system**, not an officially deployed university production service.

---

# Technical Focus

## Systems & Architecture

- Explicit authorization boundaries
- Transactional workflows
- Concurrency control
- Process orchestration
- Local-first architecture
- Failure and recovery behavior
- Reproducible execution

## Backend & Data

- Laravel
- PHP
- Node.js
- Fastify
- PostgreSQL
- SQLite
- REST APIs
- OpenAPI
- Prisma

## Optimization & Automation

- Python
- OR-Tools
- Background queues
- Scheduled jobs
- Deterministic pipelines
- Snapshot-based processing
- Reproducible test environments

## Desktop & Tooling

- Go
- Wails
- Tauri
- Windows APIs
- WebView2

## Frontend

- React
- TypeScript
- JavaScript
- Vite
- Blade
- Bootstrap
- TanStack Query
- Zod

## Verification

- PHPUnit
- Vitest
- Playwright
- Schema validation
- Integration testing
- Concurrency testing
- Backup/restore testing
- API contract verification
- GitHub Actions

---

# Interests

- Developer tooling and deterministic verification
- Full-stack system architecture
- Local-first software and explicit trust boundaries
- Static and semantic analysis with honest limits
- Optimization and workflow automation
- Authorization and scope isolation
- Native desktop behavior and frontend/backend integration
- Data integrity, testing, and reproducible automation
- Failure recovery and observable system behavior
