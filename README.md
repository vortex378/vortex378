# Arkel Lahi

Full-stack developer in Tirana, Albania (CET). I build business software (approvals, scheduling, booking, payments) and add AI to it where it saves real time.

**Stack:** Next.js · React · TypeScript · Node.js · C#/.NET · Go · PostgreSQL · Supabase · Kafka

**AI:** LLM features, ticket triage, prompt evaluation

**Open to:** freelance projects and full-time remote roles

🌐 [arkellahi.com](https://arkellahi.com) · [LinkedIn](https://linkedin.com/in/arkel-lahi) · arkellahi82@gmail.com

## What I can help with

| You need | Proof |
| --- | --- |
| Business apps with roles, approvals and audit trails | [WorkforceOS](https://github.com/vortex378/workforceos), [Dispatchly](https://github.com/vortex378/dispatchly) |
| An AI-built app made production-ready: auth, payments, tests, security | [AFA BANK](https://github.com/vortex378/afa-bank), [WorkforceOS](https://github.com/vortex378/workforceos) |
| AI features added to an existing product | [TableGo](https://github.com/vortex378/tablego-ai-assessment) |
| A multilingual business site with booking | [Albanian Tours Hub](https://github.com/vortex378/albania-travel-agency) |

## Start here

| Project | What it shows | Try it |
| --- | --- | --- |
| [WorkforceOS](https://github.com/vortex378/workforceos) | A deployed full-stack product with approvals, transactional decisions, and an audit trail | [Live app](https://workforceos-sigma.vercel.app) |
| [Dispatchly](https://github.com/vortex378/dispatchly) | .NET 10, EF Core, scheduling rules, tests, and CI | [Interactive preview](https://vortex378.github.io/dispatchly/) |
| [RoutePulse](https://github.com/vortex378/routepulse) | Go, Kafka, PostgreSQL, and event-processing safeguards | [Interactive preview](https://vortex378.github.io/routepulse/) |
| [Albanian Tours Hub](https://github.com/vortex378/albania-travel-agency) | A live multilingual website for a real client | [Live site](https://albaniatours-hub.com/en) |
| [AFA BANK](https://github.com/vortex378/afa-bank) | A cybersecurity training platform with an atomic ledger, hardened auth, and role-based game flow | [Live app](https://afa-bank-next.cobra-public-community.workers.dev) |
| [RentSpace](https://github.com/vortex378/rentspace) | A white-label booking SaaS monorepo with database-enforced booking rules and a shared design system | Run locally |

## Engineering details

### [WorkforceOS](https://github.com/vortex378/workforceos) · Timesheets and approvals

A full-stack workforce workflow built with **Next.js, TypeScript, PostgreSQL, and Vercel**. Employees create and submit time entries; managers approve or reject them. Server-side role checks, transactional state changes, database constraints, an audit trail, unit tests, and CI support the flow.

**[Try the live product](https://workforceos-sigma.vercel.app)** · [Explore the architecture and code](https://github.com/vortex378/workforceos)

The live demo uses a separate private workspace for each visitor and synthetic records. The role switcher lets reviewers explore both sides of the workflow.

### [Dispatchly](https://github.com/vortex378/dispatchly) · Field service operations

A scheduling and dispatch dashboard built with **.NET 10, ASP.NET Core, EF Core, React, and TypeScript**. It includes job creation, technician assignment, overlap checks, status workflows, automated tests, and CI.

**[Try the live preview](https://vortex378.github.io/dispatchly/)** · [Explore the code](https://github.com/vortex378/dispatchly)

The live preview runs in browser demo mode. The repository includes a database-backed .NET API that can be run locally.

### [RoutePulse](https://github.com/vortex378/routepulse) · Event-driven shipment tracking

A shipment operations dashboard with a **Go API, Apache Kafka, PostgreSQL, React, and TypeScript**. Its local pipeline uses a transactional outbox, Kafka consumer, event IDs, and sequence numbers to handle retries, duplicates, and out-of-order scans. Go tests and GitHub Actions check the backend and frontend.

**[Try the interactive preview](https://vortex378.github.io/routepulse/)** · [Explore the code](https://github.com/vortex378/routepulse)

The public preview simulates events in the browser. The Go/Kafka/PostgreSQL pipeline is configured for local Docker Compose use; it is not hosted behind the preview.

### [Albanian Tours Hub](https://github.com/vortex378/albania-travel-agency) · Multilingual travel website

A live **Next.js and TypeScript** tour website with English, Albanian, German, and French pages, nine detailed tour itineraries, travel guides, responsive design, and localized search metadata. Visitors can plan a booking through WhatsApp.

**[Visit the live site](https://albaniatours-hub.com/en)** · [Explore the code](https://github.com/vortex378/albania-travel-agency)

### [AFA BANK](https://github.com/vortex378/afa-bank) · Cybersecurity training platform

A multiplayer classroom platform where Red and Blue teams work inside a virtual bank, investigate an incident, and submit evidence-backed reports. Built with **React, TypeScript, Three.js, Cloudflare Workers, and D1**. Money is stored as integer minor units; debits and credits run in one atomic batch with idempotency keys. Sessions are hashed and short-lived, passwords use salted PBKDF2, and mutations are rate limited and origin checked. Browser regressions run against an isolated local database.

**[Open the live app](https://afa-bank-next.cobra-public-community.workers.dev)** · [Explore the code](https://github.com/vortex378/afa-bank)

No real money or bank integration is involved; the platform is for education only.

### [RentSpace](https://github.com/vortex378/rentspace) · White-label booking SaaS

A **pnpm monorepo** that joins a booking backend with a reusable design system. Double bookings are prevented by a **PostgreSQL `EXCLUDE` constraint**, with a test that races concurrent bookings against it. Auth.js, Zod validation, and rate limiting protect the API. The frontend is re-skinned per business vertical through design tokens, and Playwright checks accessibility and visual regressions across three themes, with Lighthouse budgets in CI. Architecture decisions are recorded as ADRs.

[Explore the code](https://github.com/vortex378/rentspace) · Built from [SlotRent](https://github.com/vortex378/rental-booking) (booking backend) and [Vitrina](https://github.com/vortex378/vitrina) (design system)

## More work

| Project | Summary | Stack |
| --- | --- | --- |
| [TableGo](https://github.com/vortex378/tablego-ai-assessment) | Concurrency-safe booking, LLM ticket triage, and a reproducible prompt evaluation | Python, pytest, llama.cpp |
| [SlotRent](https://github.com/vortex378/rental-booking) | Time-slot booking with database-enforced availability and row-level security | Next.js, PostgreSQL, Drizzle |
| [Vitrina](https://github.com/vortex378/vitrina) | Token-based component system for local-business websites, with Storybook | Next.js, Tailwind CSS, GSAP |
| [PERX](https://github.com/vortex378/perx-benefits-marketplace) | Employee benefits marketplace with employer analytics · [live](https://perx-saas-marketplace.vercel.app) | Next.js, Supabase |
| [Portali i Studentëve](https://github.com/vortex378/portali-studenteve) | Student portal with admin and student roles · [live](https://portali-studenteve.vercel.app) | Next.js, Supabase |

### Client websites

[Lujon Flowers](https://joniz.vercel.app) ([code](https://github.com/vortex378/joniz-flower-shop)) · [BlueGrid Studio](https://github.com/vortex378/bluegrid-studio) · [Developer portfolio](https://gesi.vercel.app) ([code](https://github.com/vortex378/gesi))
