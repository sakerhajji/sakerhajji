<div align="center">

# Saker Hajji

### Full-Stack Software Engineer · Production Systems · Backend Architecture · DevOps

<img
src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=700&lines=Full-Stack+Software+Engineer;Building+Production-Grade+Web+Systems;Next.js+%E2%80%A2+NestJS+%E2%80%A2+Django+%E2%80%A2+Spring+Boot;PostgreSQL+%E2%80%A2+Redis+%E2%80%A2+Docker+%E2%80%A2+CI%2FCD;From+Database+to+Production+Deployment"
alt="Full-Stack Software Engineer building production-grade web systems"
/>

<br/>

<a href="https://www.linkedin.com/in/sakerhajji/">
  <img src="https://img.shields.io/badge/LinkedIn-Saker_Hajji-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="mailto:saker.hajji13@gmail.com">
  <img src="https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>
<a href="https://github.com/sakerhajji">
  <img src="https://img.shields.io/badge/GitHub-sakerhajji-181717?style=for-the-badge&logo=github" alt="GitHub"/>
</a>

</div>

---

## About

I design, build and operate complete production systems. Not isolated features, the whole lifecycle:

**Requirements → Architecture → Database → API → Frontend → Infrastructure → Deployment → Maintenance**

Two of the systems below run in daily production and I still maintain them. My recent work covers ERP and POS
platforms, e-commerce integrations, real-time dashboards, manufacturing workflows and payment flows.

Day to day I work with **Next.js, React and TypeScript** on the front, **NestJS, Django REST Framework and
Spring Boot** on the back, **PostgreSQL and Redis** for data, and **Docker, Nginx and GitHub Actions** to ship it.

> I enjoy owning a product from the first database table to the production server.

**Based in Tunisia. Open to relocation, remote and hybrid roles, and to freelance work on production systems.**

---

## Tech Stack

**Languages**

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,python,java,php,cs,cpp&theme=dark" alt="TypeScript, JavaScript, Python, Java, PHP, C#, C++"/>
</p>

**Frontend**

<p align="center">
  <img src="https://skillicons.dev/icons?i=react,nextjs,angular,tailwind,vite,html,css&theme=dark" alt="React, Next.js, Angular, Tailwind CSS, Vite, HTML, CSS"/>
</p>

**Backend**

<p align="center">
  <img src="https://skillicons.dev/icons?i=nodejs,nestjs,django,spring,laravel,symfony,dotnet,fastapi,express&theme=dark" alt="Node.js, NestJS, Django, Spring Boot, Laravel, Symfony, .NET, FastAPI, Express"/>
</p>

**Databases and Data**

<p align="center">
  <img src="https://skillicons.dev/icons?i=postgres,mysql,redis,mongodb,prisma&theme=dark" alt="PostgreSQL, MySQL, Redis, MongoDB, Prisma"/>
</p>

**DevOps and Infrastructure**

<p align="center">
  <img src="https://skillicons.dev/icons?i=docker,nginx,linux,githubactions,git,github&theme=dark" alt="Docker, Nginx, Linux, GitHub Actions, Git, GitHub"/>
</p>

---

## How I Build

```text
Frontend              Backend                Data
──────────────        ──────────────         ──────────────
Next.js               NestJS                 PostgreSQL
React                 Django / DRF           MySQL
Angular               Spring Boot            Redis
TypeScript            Laravel / Symfony      MongoDB
Tailwind CSS          Node.js · FastAPI      Prisma
Vite                  Celery

                         │
                         ▼
                  Infrastructure
              ─────────────────────
               Docker · Nginx · Linux
            GitHub Actions · Let's Encrypt
                        VPS
                         │
                         ▼
                     Production
```

---

## Featured Projects

### LkSystem ERP

**Production ERP · POS · Business Intelligence**

[![Repository](https://img.shields.io/badge/VIEW_REPOSITORY-181717?style=for-the-badge&logo=github)](https://github.com/lk-cosmetics/LkSystemProd)
![Production](https://img.shields.io/badge/STATUS-PRODUCTION-238636?style=for-the-badge)
![Role](https://img.shields.io/badge/ROLE-SOLE_DEVELOPER-8957E5?style=for-the-badge)

End-to-end ERP, POS and business intelligence platform for the **Therapy by LK** cosmetics group. Multi-brand and
multi-channel, covering order and inventory management, an integrated point of sale, WooCommerce synchronisation,
real-time dashboards over Django Channels, and background processing on Celery and Redis.

Two details worth calling out. The POS drives physical retail hardware through dedicated **FastAPI bridge
services**, an ESC/POS thermal receipt printer and a serial customer display. The whole stack deploys through
GitHub Actions onto a VPS behind Nginx with automated Let's Encrypt renewal.

**Result: average order processing dropped from 13.5 minutes to 2.25 minutes, an 83% reduction.**

`Django 5` · `Django REST Framework` · `Channels / ASGI` · `Celery` · `PostgreSQL 15` · `Redis 7` · `React 19` · `Vite` · `Tailwind CSS` · `Docker Compose` · `Nginx` · `GitHub Actions`

---

### ORALIGN Platform

**Clinical Case Management · Manufacturing Workflow**

![Production](https://img.shields.io/badge/STATUS-PRODUCTION-238636?style=for-the-badge)
![Private](https://img.shields.io/badge/REPOSITORY-PRIVATE-B62324?style=for-the-badge&logo=github)
![Role](https://img.shields.io/badge/ROLE-SOLE_DEVELOPER-8957E5?style=for-the-badge)

Production platform for a clear-aligner manufacturer, carrying a case from the patient file through clinical
processing to the manufacturing pipeline. Patient files, treatment orders, clinical workflow, production
tracking, role-based administration, invoicing and exports.

Private because it is a commercial product. Happy to walk through the architecture and the trade-offs in an interview.

`Next.js` · `TypeScript` · `NestJS` · `Prisma` · `PostgreSQL` · `Docker` · `Nginx` · `GitHub Actions`

---

### E-Learning Platform API

[![Repository](https://img.shields.io/badge/VIEW_REPOSITORY-181717?style=for-the-badge&logo=github)](https://github.com/sakerhajji/elearning-platform-api)

Backend for a complete online learning platform: course and lesson management, video upload and transcoding with
per-user progress tracking, quizzes, PDF certificates with QR verification, discussion forums, real-time
messaging, and an order flow paying through both Stripe and PayPal. Around 30 route modules over 20+ data models.

`Node.js` · `Express` · `MongoDB` · `Mongoose` · `Socket.IO` · `JWT` · `OAuth 2.0` · `Stripe` · `PayPal` · `Cloudinary` · `FFmpeg` · `Docker`

---

### LatexLocal

[![Repository](https://img.shields.io/badge/VIEW_REPOSITORY-181717?style=for-the-badge&logo=github)](https://github.com/sakerhajji/LatexLocal)

Reproducible Docker deployment of a self-hosted **Overleaf Community Edition** instance, with a MongoDB replica
set, Redis and a LaTeX toolchain preconfigured with the packages and fonts real reports need. Built because the
hosted options did not fit the constraints, and packaged so the whole environment comes up with one command.

```bash
docker compose up -d
```

`Docker` · `Docker Compose` · `MongoDB 8` · `Redis 6.2` · `LaTeX` · `GitHub Actions`

---

### Health Tracker

[![Repository](https://img.shields.io/badge/VIEW_REPOSITORY-181717?style=for-the-badge&logo=github)](https://github.com/sakerhajji/laravelProject5Twin3)

Health and wellness platform for students and educators, with habit tracking, progress reporting and a
symptom-based guidance tool. Team project, where I built the backend and the Docker and CI setup.

`Laravel` · `PHP` · `MySQL` · `Docker` · `Vite`

---

## Experience

### Full-Stack Software Engineer
**LK Cosmetics / Therapy by LK** · `Sep 2024 — Aug 2026`

Production engineering across ERP, POS, business intelligence, e-commerce synchronisation, hardware integration
and infrastructure. Django REST Framework, React, TypeScript, PostgreSQL, Celery, Redis, Docker, Nginx, CI/CD.

### Full-Stack Software Engineer · Freelance
**Aura Aligners · Dr Bloom Cosmetics · Ania Naturals** · `Sep 2024 — Jun 2025`

A B2B SaaS platform, e-commerce systems and production deployments. Next.js, NestJS, PostgreSQL, Redis,
WordPress and WooCommerce.

### Full-Stack Software Engineer
**Société Dessin Technique Divers** · `Oct 2022 — Sep 2024`

Four client applications delivered with an engineering team, from requirements to production release.
Java and Spring Boot services, .NET services, Angular front ends, REST APIs, relational schemas, C++ components,
Docker, Linux and CI/CD.

---

## Freelance

I take on freelance work on production systems, not throwaway prototypes. Typically:

- **Custom business platforms** — ERP, POS, order and inventory management, internal tools
- **B2B SaaS products** — from data model and API through to the dashboard people actually use
- **E-commerce** — custom storefronts, WooCommerce integration, payment flows, channel synchronisation
- **Infrastructure and deployment** — Dockerising an existing app, CI/CD pipelines, VPS setup, Nginx, TLS
- **Rescue work** — taking over an unmaintained codebase and getting it back into production shape

Tell me the problem rather than the ticket, and I will come back with an approach and a timeline.

---

## GitHub Analytics

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=sakerhajji&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&rank_icon=github" alt="GitHub stats"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sakerhajji&layout=compact&theme=github_dark&hide_border=true&langs_count=8&size_weight=0.5&count_weight=0.5" alt="Top languages"/>

<br/><br/>

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/sakerhajji/sakerhajji/output/github-contribution-grid-snake-dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/sakerhajji/sakerhajji/output/github-contribution-grid-snake.svg"
  />
  <img
    alt="GitHub contribution snake"
    src="https://raw.githubusercontent.com/sakerhajji/sakerhajji/output/github-contribution-grid-snake.svg"
  />
</picture>

</div>

---

## Let's Connect

I'm interested in engineering teams building serious production products, where I can contribute across
architecture, backend, frontend and infrastructure, and in freelance work on systems that need to stay up.

**International · Remote · Hybrid · On-site · Relocation · Freelance**

<div align="center">

<a href="mailto:saker.hajji13@gmail.com">
  <img src="https://img.shields.io/badge/Let's_Talk-Email_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email me"/>
</a>
<a href="https://www.linkedin.com/in/sakerhajji/">
  <img src="https://img.shields.io/badge/Connect-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn"/>
</a>

<br/><br/>

**Building software that runs in production, not just on localhost.**

</div>
