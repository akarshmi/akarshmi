<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:0f0c29,50:2d1b69,100:0f0c29&height=240&section=header&text=AKARSH%20MISHRA&fontSize=60&fontColor=e2c97e&fontAlignY=42&desc=Backend%20Engineer%20%C2%B7%20Security%20%C2%B7%20Distributed%20Systems%20%C2%B7%20AI%20Integration&descAlignY=64&descSize=15&descColor=c4b8e8" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&duration=3200&pause=900&color=E2C97E&center=true&vCenter=true&width=720&lines=Designing+secure+authentication+systems;Spring+Boot+%C2%B7+PostgreSQL+%C2%B7+Redis+%C2%B7+pgvector;Payments%2C+webhooks+and+event-driven+pipelines;Top+10+%2F+200%2B+teams+%E2%80%94+Smart+India+Hackathon+2025)](https://git.io/typing-svg)

<br/>

[![Portfolio](https://img.shields.io/badge/PORTFOLIO-akarshmi.dev-e2c97e?style=for-the-badge&labelColor=0f0c29)](https://akarshmi.dev)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-akarshmi-7c6fe0?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0f0c29)](https://www.linkedin.com/in/akarshmi/)
[![Email](https://img.shields.io/badge/EMAIL-Contact-c4b8e8?style=for-the-badge&logo=gmail&logoColor=c4b8e8&labelColor=0f0c29)](mailto:akarshmi.am@gmail.com)
[![HackerRank](https://img.shields.io/badge/HACKERRANK-akarshmi-2EC866?style=for-the-badge&logo=hackerrank&logoColor=white&labelColor=0f0c29)](https://www.hackerrank.com/akarshmi)

</div>

<br/>

## `// about`

<table>
<tr>
<td width="62%" valign="top">

I'm a backend engineer in the making, currently pursuing my **MCA at Lovely Professional University** (graduating 2027). I like the part of software that users never see but always feel: the login that stays secure, the payment that never double-charges, the search that actually finds the right thing.

**What I work on**
- **Security first:** JWT with revocation, OAuth2, RBAC, hashed OTPs and HttpOnly cookie sessions
- **Reliable money flows:** webhook-verified payments, idempotent processing, optimistic locking
- **AI in the backend:** embeddings, vector similarity search and event-driven matching
- **Clean architecture:** layered services, interface-driven design, secure defaults

**How I work**
I build complete products, not just endpoints: backend, deployment, docs and a client on top. I've led a 5-person team to a **Top 10 finish out of 200+ teams** at Smart India Hackathon 2025, and I enjoy turning rough ideas into running systems.

**Right now**
Building **UniTrace**, an AI-powered campus Lost & Found, and **Jobescape**, a self-hostable job aggregator. Looking for backend and software engineering opportunities where I can ship real systems and keep learning.

</td>
<td width="38%" valign="top">

```yaml
name      : Akarsh Mishra
role      : Backend Engineer
stack     : Java · Spring Boot
studying  : MCA, LPU (2027)
location  : Uttar Pradesh, India
focus     :
  - Authentication & security
  - Payment systems
  - Vector search & AI
  - API design
building  :
  - UniTrace
  - Jobescape
open_to   : Backend roles & internships
```

</td>
</tr>
</table>

<br/>

## `// skills`

<div align="center">

**Languages**

[![Languages](https://skillicons.dev/icons?i=java&theme=dark)](https://skillicons.dev)

**Backend & Security**

[![Backend](https://skillicons.dev/icons?i=spring,hibernate&theme=dark)](https://skillicons.dev)

**Frontend**

[![Frontend](https://skillicons.dev/icons?i=react,nextjs,tailwind&theme=dark)](https://skillicons.dev)

**Databases**

[![Databases](https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,sqlite,supabase,firebase&theme=dark)](https://skillicons.dev)

**Cloud & DevOps**

[![DevOps](https://skillicons.dev/icons?i=aws,docker,vercel,digitalocean,maven,git,github&theme=dark)](https://skillicons.dev)

<sub>Security & concepts: OAuth2 · JWT (RS256) · RBAC · Argon2 / BCrypt · HMAC · REST API design · Vector search · Microservices</sub>

</div>

<br/>

## `// flagship project`

<table>
<tr>
<td>

### UniTrace &nbsp;·&nbsp; AI-Powered University Lost & Found
*Campus-scale platform that matches lost and found items with text and image embeddings, with moderated handover at the Security Office.*

```mermaid
flowchart LR
    A[Student reports item] --> B[Image to Cloudinary]
    B --> C[Async embedding job<br/>MiniLM text + CLIP image]
    C --> D[(PostgreSQL + pgvector)]
    D --> E[Weighted match scoring<br/>text · image · time]
    E --> F{Moderator review}
    F -->|Approve| G[Student notified]
    G --> H[One-time handover key<br/>Security Office desk]
    F -->|Reject| I[Match discarded]
```

| | |
|---|---|
| **Matching** | Text + image embeddings, pgvector similarity search, weighted score with event time-window factor |
| **Pipeline** | Event-driven: matching fires once an item's embeddings are generated |
| **Privacy** | No contact details shared; moderator approval and one-time handover key for every claim |
| **Auth** | Email-OTP signup (HMAC-hashed OTPs in Redis, atomic Lua verify), Argon2 passwords, JWT access tokens with JTI-based refresh tokens in HttpOnly cookies |
| **Roles** | Student · Moderator · Admin |

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring AI](https://img.shields.io/badge/Spring_AI-6DB33F?style=flat-square&logo=spring&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-7c6fe0?style=flat-square)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=flat-square&logo=cloudinary&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-eeeeee?style=flat-square&logo=nextdotjs&logoColor=0f0c29)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)

</td>
</tr>
</table>

<br/>

## `// selected work`

<table>
<tr>
<td valign="top" width="50%">

#### Unitrix &nbsp;`Event Ticketing`
Booking backend where tickets are generated only after webhook-confirmed payment.

- Razorpay with HMAC-SHA256 verification on raw request bodies
- Optimistic locking (`@Version`) on inventory; scheduler expires stale orders
- OTP-verified registration, password reset, organizer approval workflow
- Companion **UniTickets** frontend in Next.js and shadcn/ui

`Spring Boot` `PostgreSQL` `Razorpay` `JWT`

</td>
<td valign="top" width="50%">

#### AuthPlus &nbsp;`Auth Framework`
Reusable authentication backbone built to drop into microservices.

- JWT (RS256), OAuth2 login, RBAC across 15+ endpoints
- BCrypt hashing, HTTP-only cookie sessions
- Zero-downtime deploys on Render
- Cut integration time by ~40%

`Spring Security` `Next.js` `Redis` `Docker`

</td>
</tr>
<tr>
<td valign="top" width="50%">

#### Jobescape &nbsp;`Job Aggregator`
Multi-platform job scraper with resume upload that pre-fills search filters. Self-hostable via Docker Compose.

- FastAPI with async scrape jobs and status / results / download endpoints
- Excel export with application-tracking columns

[`Repository`](https://github.com/akarshmi/jobescape) &nbsp; `Python` `FastAPI` `Next.js`

</td>
<td valign="top" width="50%">

#### Jobify &nbsp;`Ingestion Service`
Pluggable job-ingestion backend with run tracking and deduplication.

- `JobSource` abstraction keeps the service independent of any provider
- Per-run created / updated / skipped counts, failure tracking

`Java` `Spring Boot` `Hibernate` `PostgreSQL`

</td>
</tr>
<tr>
<td valign="top" width="50%">

#### QuiLink &nbsp;`URL Shortener`
Live on a custom domain with click analytics.

- Snowflake IDs with Base62 codes, TTL indexes
- Atomic click counting in MongoDB Atlas
- Dockerized deploy on Render

`Spring Boot` `MongoDB` `Next.js`

</td>
<td valign="top" width="50%">

#### StayLedger &nbsp;`Desktop App`
Offline-first Windows app for PG and hostel management.

- Occupancy-based rent, deposit ledger with refunds
- Automatic late fees and overdue reports
- Encrypted manual backup to Google Drive

`JavaFX` `SQLite` `Java 21`

</td>
</tr>
<tr>
<td valign="top" colspan="2">

#### Scholar Forge &nbsp;`Academic Marketplace`
Students publish, discover and peer-review academic projects. Multi-provider OAuth2, JWT dual-token rotation, microservices backend. **35% faster queries**, 50+ reviewers supported. &nbsp; `Next.js` `Spring Boot` `PostgreSQL`

</td>
</tr>
</table>

<br/>

## `// achievements`

<table>
<tr>
<td width="72%" valign="top">

**Team Lead & Backend Developer · Smart India Hackathon 2025**

Led a 5-person cross-functional team (data science, UI/UX, cloud) through a 36-hour national hackathon. Designed the REST API, ran agile sprints, shipped an MVP with React, n8n and Node.js, and presented architecture and business model to the judging panel.

</td>
<td width="28%" align="center" valign="middle">

![Rank](https://img.shields.io/badge/TOP_10-of_200%2B_teams-e2c97e?style=for-the-badge&labelColor=0f0c29)
![Problems](https://img.shields.io/badge/500%2B-problems_solved-7c6fe0?style=for-the-badge&labelColor=0f0c29)

</td>
</tr>
</table>

<br/>

## `// certifications`

| Certification | Issuer | Year |
|:--|:--|:-:|
| Software Engineering Virtual Program | Goldman Sachs (Forage) | 2025 |
| Solutions Architecture | Amazon Web Services | 2024 |
| Software Engineer Intern | HackerRank | 2024 |

<br/>

## `// github`

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=akarshmi&show_icons=true&count_private=true&theme=transparent&hide_border=true&title_color=e2c97e&icon_color=7c6fe0&text_color=c4b8e8&bg_color=0f0c29" />
<img width="49%" src="https://github-readme-streak-stats.herokuapp.com?user=akarshmi&theme=transparent&hide_border=true&background=0f0c29&stroke=e2c97e&ring=7c6fe0&fire=e2c97e&currStreakLabel=c4b8e8&sideLabels=c4b8e8&dates=c4b8e8&currStreakNum=e2c97e&sideNums=e2c97e" />

<img width="45%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=akarshmi&layout=compact&theme=transparent&hide_border=true&title_color=e2c97e&text_color=c4b8e8&bg_color=0f0c29&langs_count=6&hide=html,css" />

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=akarshmi&theme=tokyo-night&hide_border=true&bg_color=0f0c29&color=e2c97e&line=7c6fe0&point=e2c97e&area=true&area_color=2d1b69)](https://github.com/akarshmi)

</div>

<br/>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:2d1b69,100:0f0c29&height=110&section=footer" width="100%"/>

*Build things that matter. Write code that lasts.*

</div>
