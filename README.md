# main-projects

All my main projects I have worked on along the years

**Status legend:** `Empty` · `Boilerplate` · `Stuck` · `Looking good` · `Production ready`

_Last audited: 2026-08-03 (from local clones in `C:\dev` and `C:\dev\didi-tech`)_

---

### [Megan-Israel](https://github.com/didinewlander/Megan-Israel) — `Stuck`
Military Advanced Geolocation and Emergency Navigation
Vite + React, ~4.5k LOC, real map functionality. Last commit **2024-07-15**, 30 uncommitted files across 15 branches. Abandoned mid-feature.

### [superducation](https://github.com/didinewlander/superducation) — `Stuck`
SaaS platform for tutors to teach and sell their teaching sessions
Next.js, ~7.6k LOC, 40 pages + 19 API routes — the most complete of the old ones. Last commit **2024-05-30**, 11 uncommitted files.

### [lanisayon-co-il](https://github.com/DiDiTech-IL/lanisayon-co-il) — `Stuck`
An all-in-one platform for leveling up your developer skills
Next.js + Prisma + Lucia auth, ~7.3k LOC, 11 pages. Last commit **2024-10-27**, 47 uncommitted files. README has an open Hebrew TODO list.

### [hamal-service-text](https://github.com/DiDiTech-IL/hamal-service-text) — `Boilerplate`
SMS notification system for fast updates to field forces
~390 LOC, 1 commit (**2024-12-31**), default `create-next-app` README. Twilio + QStash + Prisma wired in, one API route. Never got past setup.

### [SmartOC](https://github.com/DiDiTech-IL/SmartOC) — `Looking good`
SOC management platform
~11k LOC, 22 pages + 5 API routes, docker-compose (ClickHouse + Redis), Protobuf/gRPC schemas, mTLS cert scripts. C++ agent is still a skeleton. Last commit **2026-01-15**. Has `IMPLEMENTATION_STATUS.md` tracking what's done.

### [qampaign](https://github.com/DiDiTech-IL/qampaign) — `Boilerplate`
Turn your QRs into profitable data
Landing page only: 1 page, 3 marketing components (hero/campaign/CTA) on top of 37 shadcn components. No backend, no QR logic. Last commit **2025-03-25**, clean tree.

### [s4](https://github.com/DiDiTech-IL/s4) — `Looking good` + [uploadarmor](https://github.com/DiDiTech-IL/uploadarmor) — `Boilerplate`
Safe storage upload service for SaaS products + Development SDK
- **s4** — ~21k LOC, 9 pages, Clerk + Prisma + Upstash rate limiting + Svix. Last commit `stable version` (**2025-04-22**), 32 uncommitted files.
- **uploadarmor** — Turborepo skeleton: `core`, `sdk`, `shared`, `api-worker` (Cloudflare). Only ~330 LOC total — the structure exists, the implementation mostly doesn't. Last commit **2025-04-23**.

### [backflow](https://github.com/DiDiTech-IL/backflow) — `Looking good`
Design real backend environments in a flow based UI
~9k LOC, 17 pages, Drizzle + Neon, `@xyflow/react` canvas, CodeMirror, AI SDK (OpenAI/Groq/DeepSeek). Last commit `stable version, from here it's only going up` (**2025-05-06**), 41 uncommitted files.

### [shilamti-app](https://github.com/DiDiTech-IL/shilamti-app) — `Boilerplate`
Keep your friends close to you, and your money closer
~2.3k LOC, 6 pages (dashboard/upload/ai), Convex + UploadThing. 1 commit (**2025-09-14**), default README. Scaffold with a couple of features stubbed.

### [mitnadvim-app](https://github.com/DiDiTech-IL/mitnadvim-app) — `Production ready`
Volunteering management system for organizations and non-profit
_(local folder: `C:\dev\dukas`)_ — **The most complete product here.** ~82k LOC, 79 pages, 22 API routes, multi-tenant with subdomains, Clerk auth, Prisma, PWA + web-push, PDF/Excel export, 18 test files, `vercel.json` deploy config. Last commit **2026-07-01**. Extensive implementation docs incl. `PRODUCTION_READY_SUMMARY.md`.

### [acdemap](https://github.com/DiDiTech-IL/acdemap) — `Looking good`
Build and design a roadmap to knowledge
_(local folder: `didi-tech\acdemiline`)_ — ~52k LOC, 33 pages, 13 API routes, Clerk + Prisma + xyflow prerequisite graph. Proper developer README (architecture, data model, SEO, deployment). Last commit **2025-10-10**, but 102 uncommitted files sitting there.

### [pay-tachles](https://github.com/DiDiTech-IL/pay-tachles) — `Looking good`
Wrap your payments with a status tracker so you know exactly what's going on with your money
~12.4k LOC, 9 pages, Effect-based type-safe core, Prisma + Upstash, Cloudflare Worker deploy scripts. Strong product README (self-hostable, provider-agnostic). Last commit `ready for launch` (**2025-12-03**) — but 118 files never committed since.

### [anipo](https://github.com/DiDiTech-IL/anipo) — `Looking good`
Attendance tracking application
**Best-engineered repo by far.** pnpm Turborepo: `api` / `console` / `mobile` / `workers` apps + 12 shared packages (contracts, permissions, db, i18n, queue, observability…). ~123k LOC, 617 code files, **109 test files**, 3 GitHub Actions workflows (`ci`, `deploy-staging`, `deploy-production`), Vercel linked. 89 commits in the last week — actively mid build-out, prod pipeline already in place.

### [choiry](https://github.com/tachles-dev/choiry) — `Looking good`
SQL queries generator
~22k LOC, publishable npm package (`@tachles/choiry`) with `prepublishOnly`, 9 test files, ts-morph codegen, Prisma + Postgres schema parsing, watch/validate modes. README self-describes as MVP. Last commit **2026-01-13**, clean tree.

### [whatsapp-service](https://github.com/tachles-dev/whatsapp-service) — `Production ready`
Manage your whatsapp services and agents with ease
~9k LOC, 58 commits, Fastify + Baileys + BullMQ + Redis, multi-tenant control plane. Dockerfile + docker-compose + Caddy reverse proxy + **Hetzner deploy keys** — this one is actually running somewhere. 8 test files, full integration-guide README, clean tree. Last commit **2026-03-21**.

### [tachles-vms](https://github.com/tachles-dev/tachles-vms) — `Looking good`
VMS platform for security solutions
~40k LOC monorepo (server / client / portal / edge), 77 UI components, docker-compose, 2 CI workflows, stress-test suite. Landed as a single initial commit on **2025-12-16** and untouched since — no tests, 17 uncommitted files.

### [forms](https://github.com/DiDiTech-IL/forms) — `Looking good`
Not another Google Forms alternative
~9.8k LOC, 16 pages, clean feature-folder architecture (auth / forms / responses / integrations / analytics), full builder with conditional logic, live preview, templates, public `f/[slug]` rendering. **Runs entirely on `mock/data.ts`** — no database or API routes yet. Last commit **today (2026-08-03)**, `inbetween status`.

### [share](https://github.com/DiDiTech-IL/share) — `Looking good`
A tool for sharing your products online
~9.2k LOC, canvas editor (layers, viewport, property panel, export to image/GIF) with Convex backend (projects, assets, templates, feature flags, subscription events) and Clerk webhooks. 1 commit (**2026-01-14**), 24 uncommitted files.

---

## Summary

| Status | Count | Projects |
|---|---|---|
| Empty | 0 | — |
| Boilerplate | 4 | hamal-service-text, qampaign, uploadarmor, shilamti-app |
| Stuck | 3 | Megan-Israel, superducation, lanisayon-co-il |
| Looking good | 10 | SmartOC, s4, backflow, acdemap, pay-tachles, anipo, choiry, tachles-vms, forms, share |
| Production ready | 2 | mitnadvim-app, whatsapp-service |

**Worth knowing:** 8 of these repos have significant uncommitted work sitting on disk — `acdemap` (102 files), `pay-tachles` (118), `lanisayon-co-il` (47), `backflow` (41), `s4` (32), `Megan-Israel` (30), `share` (24), `tachles-vms` (17). Some of that is probably the difference between "stuck" and "looking good".
