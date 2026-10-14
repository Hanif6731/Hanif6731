# 👋 Hi, I'm Md. Hanif
### Senior Software Engineer · .NET / F# · Full-Stack · LLM Systems

<p align="left">
  <a href="https://linkedin.com/in/imhanif" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:iam.mdhanif@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://xchanze.com" target="_blank"><img src="https://img.shields.io/badge/xChanze-000000?style=for-the-badge&logo=about.me&logoColor=white" alt="xChanze"></a>
</p>

---

### 🚀 About Me
Senior Software Engineer with 5+ years at **Chaldal (YC S15)**, Bangladesh's largest online grocery, building high-throughput backend and full-stack systems in .NET/F# and React. I own systems end to end — architecture, delivery, operations, mentoring — and I like problems where correctness and scale both matter: supply-chain logistics, customer-success tooling, geocoding, and LLM pipelines in production.

- 🔭 Currently tech lead and sole maintainer of **Premium Care**, the service behind Chaldal's concierge sales programme (~300 agents); also sole author of the Gemini batch LLM pipeline (**~70k requests/day**)
- 🛠️ Building on the side: **xRetail** (POS for small shops) and a real-estate platform for **Purple Holdings**
- 💬 Ask me about F#, event-driven architecture, state machines, and running LLM workloads cheaply
- 🌏 Open to senior backend / full-stack / LLM engineering roles — remote or relocation
- 📫 iam.mdhanif@gmail.com

---

### 🛠️ Tech Stack

<details open>
  <summary><b>Languages</b></summary>
  <p align="left">
    <img src="https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white" alt="C#">
    <img src="https://img.shields.io/badge/F%23-378BBA?style=flat-square&logo=fsharp&logoColor=white" alt="F#">
    <img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
    <img src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white" alt="Dart">
    <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL">
    <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  </p>
</details>

<details open>
  <summary><b>Backend & Frontend</b></summary>
  <p align="left">
    <img src="https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt=".NET">
    <img src="https://img.shields.io/badge/Giraffe-378BBA?style=flat-square&logo=fsharp&logoColor=white" alt="Giraffe">
    <img src="https://img.shields.io/badge/EF%20Core-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt="EF Core">
    <img src="https://img.shields.io/badge/Hangfire-2A3F54?style=flat-square" alt="Hangfire">
    <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React">
    <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js">
    <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js">
    <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" alt="Flutter">
  </p>
</details>

<details open>
  <summary><b>Data, AI & Infrastructure</b></summary>
  <p align="left">
    <img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square" alt="SQL Server">
    <img src="https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
    <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis">
    <img src="https://img.shields.io/badge/Gemini%20%2F%20Vertex%20AI-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="Gemini / Vertex AI">
    <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white" alt="RabbitMQ">
    <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" alt="Grafana">
    <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
    <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes">
    <img src="https://img.shields.io/badge/Azure%20DevOps-0078D7?style=flat-square" alt="Azure DevOps">
    <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions">
    <img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare">
  </p>
</details>

---

### 🏆 Highlights @ Chaldal
- **Premium Care (tech lead, sole maintainer)** — **321 merged PRs** into the F#/Giraffe + MSSQL service behind the concierge sales programme. Built the agent work-queue engine (system-versioned audit tables, optimistic concurrency, due-time indexing) that replaced hand-built daily call lists for ~300 agents, plus state machines for a 20-state customer lifecycle.
- **LLM batch pipeline (sole author)** — durable Gemini request queue that batches by model and prompt version, submits Vertex AI batch jobs and resumes callers via serialized continuations; **~70k requests/day** at roughly half the cost of real-time calls, with token quotas, usage accounting and an operator console.
- **AI call-consent compliance** — an LLM detects do-not-call requests in call transcripts, a reviewer confirms, and the number is blocked and synced two-way with the dialer, with a full audit trail.
- **Mapping & geocoding (tech lead)** — in-house mapping service resolving **1.5k–3k addresses/day**; OpenStreetMap importer with nightly delta sync; LLM-assisted matching raised accuracy **+40%** and took address resolution off paid geocoding.
- **Vegetable Network (primary owner)** — 228 of 516 merged PRs on an F#/Giraffe perishable-goods supply-chain platform; sole author of vendor bidding; sorting, packaging and loading-bay distribution algorithms that opened a B2B channel.
- **Accounting automation** — double-entry ledger event model on Hangfire jobs with entity locks, deadlock handling and an idempotent pending-event queue that retries without double-posting.
- **Leadership** — mentored 2–3 junior engineers, performed PR reviews and ran technical planning sessions.

---

### 🧪 Side Projects

**[xRetail: Shop & POS Manager](https://play.google.com/store/apps/details?id=com.xchanze.shopmanager)** — Flutter, ASP.NET Core 10, PostgreSQL, Redis, RabbitMQ, K3s
- Architected a clean-architecture/CQRS backend with explicit domain state machines and a double-entry ledger; money and stock mutations guarded by Redis distributed locks, optimistic concurrency and idempotency keys.
- Ships to **100+ active users** via Shorebird OTA; self-hosted K3s behind Cloudflare Tunnel with RabbitMQ outbox consumers (push, email) and OpenTelemetry/Grafana observability.

**[Purple Holdings Ltd Website](https://purpleholdingltd.com)** — Next.js, Node.js (Hono), PostgreSQL, Cloudflare
- Built a three-service monorepo (public site, admin portal, Hono API) with Zod contracts validated at the network boundary; public pages fully pre-rendered at build time for SEO — enforced by a JS-disabled e2e test.
- Price-gated lead capture (WhatsApp/Messenger/email) turns every price request into a CRM lead; **~2k visitors/day**.

---

### 🎓 Education
- **B.Sc. in Computer Science & Engineering** — American International University-Bangladesh (AIUB), Feb 2017 – Dec 2020
- CGPA **3.88 / 4.00** · Dean's List · 5th, Intra-AIUB Programming Contest 2018

---

### 📜 Certifications
- **HackerRank:** Software Engineer · SQL (Advanced) · REST API · Problem Solving · JavaScript
- **Coursera:** Neural Networks & Deep Learning · Front-End Web Development with React · Machine Learning for All · Introduction to Data Science in Python

---

<p align="center">
  <i>Build it to scale, keep it boring enough to run at 3am.</i>
</p>
