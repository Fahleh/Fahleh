# Uduak Ukpong

Full-Stack Developer working across React, Next.js, NestJS, and PostgreSQL. I build production-ready web applications end to end, from schema and API design through to shipped, tested UI.

## Atlas
[Live](https://atlas-murex-nine.vercel.app) · [Repo](https://github.com/Fahleh/Atlas)

A project management dashboard built solo on Next.js 16 and Supabase (Postgres, Auth, Storage), using a propose-then-review workflow: every change, including AI-assisted implementation, is proposed, reviewed, and verified before it lands.

- A self-initiated security audit found a real cross-project data leak: a Postgres view was bypassing row-level security because of a `security_invoker` gap that passed every automated linter and only surfaced under a deliberate two-user adversarial test.
- CI gates every PR to `main` and `develop` on the full test suite (361/361 passing), device-split Lighthouse performance budgets, and a live authenticated CSP check.
- Nine tagged releases (v1.0.0 through v1.3.0), with every non-obvious decision documented in `docs/decisions.md`.

## Core stack

**Frontend:** React, Next.js, TypeScript, Redux Toolkit, TanStack Query, Tailwind CSS
**Backend / Data:** NestJS, PostgreSQL, Supabase, Redis
**Tooling:** Docker, Jest, Playwright, GitHub Actions

## Currently building

A small set of backend-focused modules (auth, checkout and payments) built from scratch to the same standard as Atlas, covering the transaction-safety and security work that NDA'd client projects don't let me show directly.

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/ukpong-uduak/) · [Portfolio](https://uduakukpong.com/)
