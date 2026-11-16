<div align="center">

# Brandon

**Computer Science @ Western (UWO)** · Backend & Distributed Systems · LLM Application Engineering

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/brandonjchong/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:brandonjchong@gmail.com)

</div>

---

## Live

**[Gauntlet](https://bandonc.github.io/Gauntlet/)** - Tournaments between LLM players across six turn-based games, every move logged, priced and replayable. Matches are event-sourced and resumable on a Postgres job queue with lease fencing; 2,000 matches survived 53 worker kills and 15 Postgres freezes with every invariant intact. Findings ship with confidence intervals.

**[Hookline](https://hookline.bandonc.com)** - Webhook delivery service on Cloudflare Workers. At-least-once with an explicit dead-letter path; the scheduler is built in-house on Durable Object alarms rather than a managed queue.

**[CourseCal](https://coursecal.bandonc.com)** - Syllabi to calendar. The parser is a standalone library with an eval harness, a regex baseline for lift, and honest accuracy numbers.

**[TrackWise](https://chromewebstore.google.com/detail/trackwise/ljmiflnipemagmaihpfnmpmbdbjehenm)** - Job tracker, shipped on the Chrome Web Store. Embeddings cluster your applications so response-rate patterns surface without any manual tagging, and every posting gets a resume-fit score with a one-line reason, live on LinkedIn and Indeed.

---

## Stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Frameworks**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Hono](https://img.shields.io/badge/Hono-E36002?style=for-the-badge&logo=hono&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle-C5F74F?style=for-the-badge&logo=drizzle&logoColor=black)

**Data & Cloud**

![Postgres](https://img.shields.io/badge/Postgres-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=for-the-badge&logo=cloudflareworkers&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

**Testing & Ops**

![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![fast-check](https://img.shields.io/badge/fast--check-3178C6?style=for-the-badge)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=for-the-badge&logo=opentelemetry&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)

---

## Depth

| Area | What |
| :--- | :--- |
| **LLM application engineering** | Structured tool use · versioned prompts · eval harnesses with regex baselines · fallback chains · per-token cost accounting and budget caps |
| **LLM evaluation** | Pre-registered experiments · Wilson intervals · Fisher exact tests · Weng-Lin / Elo / Glicko-2 / Bradley-Terry ratings · solver and bot baselines |
| **Distributed delivery** | At-least-once semantics · HMAC signing · circuit breakers · decorrelated-jitter backoff · per-tenant fair scheduling |
| **Durable job processing** | Postgres queues (`SKIP LOCKED`) · lease fencing · event-sourced resumable state · shared rate limiting · chaos testing |
| **Vector search** | pgvector · embeddings · K-means clustering · cross-encoder rerank |
| **Azure** | Cosmos DB · AI Search · OpenAI · Entra ID · Container Apps · DevOps pipelines |

---

## Experience

### Software Developer to Product Owner

**Ontario Public Service** - Enterprise Architecture Office · *May 2025 - April 2026*

Built the **AI Intake Tool**, a governance platform that moves ministry AI use cases through a stage-based lifecycle of assessment, review, and approval (React · Flask · Azure Cosmos DB · AI Search · Azure OpenAI · Entra ID · Blob Storage). Started as a developer; finished as Product Owner/lead developer leading a team of 6, owning the backlog and translating business needs into technical deliverables.
