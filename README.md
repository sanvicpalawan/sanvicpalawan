<p align="center">
  <img src="profile-banner.png" alt="Palawan Collective" width="620" />
</p>

<p align="center">
  <b>Digital agency building web apps, AI agents, and digital infrastructure.</b><br />
  <sub>Based in Palawan, Philippines · <a href="https://merqato.digital">merqato.digital</a></sub>
</p>

---

## Palawan Collective

We are a digital agency. We design, build, and run software for clients and partners — from the interface down to the infrastructure that keeps it online.

| | |
| :--- | :--- |
| **Web apps** | Production applications with a consistent interface across every device — design systems, frontend, backend, and hosting. |
| **AI agents** | LLM agents and agentic workflows, built on open models with the tooling and guardrails to run unattended. |
| **Digital infrastructure** | Deployment pipelines, databases, and the operational plumbing underneath. |
| **Hospitality & tourism** | Booking engines, property management, and digital platforms for Palawan resorts and operators. |

## Tech stack

| Layer | What we build with |
| :--- | :--- |
| **Frontend** | React 19 · Next.js · Vite · TypeScript 5 · Tailwind CSS v4 |
| **Backend** | Node.js · NestJS · Next.js Route Handlers · Python services |
| **Data** | PostgreSQL · Drizzle ORM · Supabase · Redis · MongoDB |
| **AI** | OpenRouter · OpenAI-compatible APIs · MCP (Model Context Protocol) · LibreChat · Ollama (local models) |
| **Infrastructure** | Docker · Coolify · Vercel · Cloudflare · Linux VPS |
| **Integrations** | WhatsApp Cloud API · webhooks · scheduled jobs · REST & JSON APIs |

## How we structure a build

```
app/
├── src/
│   ├── app/                 # Next.js App Router
│   │   ├── (public)/        # marketing site, blog, service pages
│   │   ├── admin/           # authenticated backoffice
│   │   └── api/             # route handlers — leads, webhooks, cron
│   ├── components/          # UI, split public/ vs admin/
│   ├── db/                  # schema + pooled database client
│   └── lib/                 # domain logic — auth, automation, agents, pricing
├── drizzle.config.ts
├── vercel.json              # scheduled jobs
└── .env.example             # every variable documented, no secrets committed
```

Four rules we keep on every build: **no secrets in client bundles**, **parameterised SQL only**, **the backoffice is its own authenticated boundary**, and **long-running work runs outside the request cycle**.

## Languages

Measured across our 12 most active repositories:

```
TypeScript  ████████████████████████████  85.4%
Python      ██                             6.6%
CSS         █                              1.9%
Swift       █                              1.7%
Kotlin      █                              1.3%
JavaScript  █                              1.0%
Other       █                              2.1%   PL/pgSQL · Shell · HTML · Go · Dockerfile
```

## merQato.Digital

Our product brand — AI workspace tooling built for agencies and the partners they serve.

## Collaborations

| Repository | Description |
| :--- | :--- |
| **[cloned-coyo-coco-combined](https://github.com/sanvicpalawan/cloned-coyo-coco-combined)** | Palawan Collective · MerQato Digital · Coyo Coco — resort website and digital platform. |

## Selected work

| Repository | Description |
| :--- | :--- |
| **[cayo-cocoisland](https://github.com/sanvicpalawan/cayo-cocoisland)** | Coyo Coco resort website — Vite + React + TypeScript. |
| **[sanvicph](https://github.com/sanvicpalawan/sanvicph)** | SANVIC — interactive destination map for San Vicente, Palawan. |
| **[kapwa-hospitality-os](https://github.com/sanvicpalawan/kapwa-hospitality-os)** | Open-source, AI-powered resort operations platform for boutique properties. |
| **[palawan-collective](https://github.com/sanvicpalawan/palawan-collective)** | White-label AI agents platform — client portals and messaging channels, self-hosted. |
| **[palawancollective-chat](https://github.com/sanvicpalawan/palawancollective-chat)** | Self-hosted AI assistant for the agency, built on LibreChat. |

## Working with us

Reach out via [merqato.digital](https://merqato.digital).
