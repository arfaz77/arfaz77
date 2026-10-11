<p align="center">
  <img src="./assets/header.svg" alt="Amjath Ali — Full-Stack Engineer. I design systems that don't drop events." width="100%">
</p>

<p align="center">
  <b>Full-stack engineer · 3+ years · TypeScript, PostgreSQL, event-driven systems</b><br>
  I build ERP/CRM platforms and workflow engines that don't lose data.
</p>

<p align="center">
  <a href="https://linkedin.com/in/amjad-ali-6350a3248"><img src="https://img.shields.io/badge/LinkedIn-0F151D?style=for-the-badge&logo=linkedin&logoColor=F5A524" alt="LinkedIn"></a>
  <a href="mailto:amjadalipaduppu@gmail.com"><img src="https://img.shields.io/badge/Email-0F151D?style=for-the-badge&logo=gmail&logoColor=F5A524" alt="Email"></a>
  <img src="https://komarev.com/ghpvc/?username=arfaz77&color=F5A524&style=for-the-badge&label=PROFILE+VIEWS" alt="Profile views">
</p>

<img src="./assets/metrics.svg" alt="3+ years in production · 9.4 Meta CAPI event match quality · 1.8× faster responsiveness · 60% less dev time" width="100%">

<br>

### How I build

<img src="./assets/architecture.svg" alt="Animated architecture: API → Postgres transaction (lead + outbox) → SKIP LOCKED job queue → workers (CRM workflow, Meta CAPI, n8n) → dashboards. A failed event retries and still lands. Events lost: 0." width="100%">

Every write and its event commit together in one Postgres transaction. Workers pull jobs with `SKIP LOCKED` and retry until acknowledged, so nothing gets lost between systems.

### Experience

| When | Where | What I did |
|---|---|---|
| 2025 → now | **Indian Edu Hub** · Full-Stack Developer | Built the company's ERP/CRM from scratch: workflow engine, permission system, live dashboards, Meta CAPI (9.4 match quality) |
| 2023 → 2025 | **Autobse** · Full-Stack Developer | Next.js platform and admin panel, REST → GraphQL, 1.8× faster app |
| 2023 | **Technewings** · Intern | NFC digital business-card app in React |

### Building now

- **ScaleStack** — multi-tenant project management with live team chat · `Hono` `PostgreSQL` `Drizzle` `TanStack Start`
- **Business OS** — modular ERP framework, 21 modules, configurable fields and permissions · `RBAC/PBAC` `JSONB`
- **AI agent layer** — one chat that routes to the right tools, with every write approved by a human

### Tech

<p>
  <img src="https://skillicons.dev/icons?i=ts,nextjs,react,tailwind,bun,nodejs,express,graphql,postgres,mongodb,redis,docker,nginx,aws,vercel,githubactions,linux&perline=9&theme=dark" alt="TypeScript, Next.js, React, Tailwind, Bun, Node.js, Express, GraphQL, PostgreSQL, MongoDB, Redis, Docker, Nginx, AWS, Vercel, GitHub Actions, Linux">
</p>

Also: Hono · ElysiaJS · Drizzle · TanStack Start · Better Auth · n8n · LLM/RAG

### Contributions

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./profile-3d-contrib/profile-night-rainbow.svg">
  <source media="(prefers-color-scheme: light)" srcset="./profile-3d-contrib/profile-green-animate.svg">
  <img alt="My contribution graph rendered as a 3D city" src="./profile-3d-contrib/profile-night-rainbow.svg" width="100%">
</picture>

<details>
<summary><b>❯ git log --oneline</b> &nbsp;<sub>(click me)</sub></summary>

```console
a1c3e7f  refactor: swapped load-bearing walls for load-balanced services
5b9d201  feat: speaks English, Malayalam, Hindi and fluent EXPLAIN ANALYZE
e04f88a  fix: rescued a dead server at 2am, lost 0 rows
9f2a6c4  chore: open to interesting backend + platform problems
```
</details>
