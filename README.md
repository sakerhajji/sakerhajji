<h1 align="center">Saker Hajji</h1>

<p align="center">
  <strong>Full-Stack Software Engineer</strong><br>
  I design, build and run production web systems, from the database up to the deployed server.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Based_in-Tunis,_Tunisia-1f2328?style=flat-square" alt="Tunis, Tunisia">
  <img src="https://img.shields.io/badge/Open_to-Relocation_%26_Remote-1f2328?style=flat-square" alt="Open to relocation and remote">
  <img src="https://img.shields.io/badge/Focus-TypeScript_%C2%B7_Python-1f2328?style=flat-square" alt="Focus: TypeScript and Python">
</p>

---

### About

I build complete products rather than isolated features. Most of my recent work has been taking a
system from an empty repository to something a business actually runs on: schema design, REST APIs,
a real frontend, containerisation, a reverse proxy, TLS, CI/CD and the maintenance that follows.

I work on both sides of the stack, **Next.js / React / TypeScript** on the front and
**NestJS / Node.js** or **Django / DRF** on the back, and I own the deployment rather than handing
it off. Two of the systems below are in daily production use and I still maintain them.

Currently employed, open to international and remote roles.

### What I focus on

- **Product engineering end to end.** Requirements, data model, API, UI, deployment.
- **Backend architecture.** REST API design, relational modelling, background jobs, caching, WebSocket and real-time layers.
- **Deployment and operations.** Docker Compose on Linux VPS, Nginx reverse proxying, Let's Encrypt TLS renewal, GitHub Actions pipelines.
- **Integrations.** WooCommerce synchronisation, payment providers, hardware bridges such as ESC/POS thermal printers and serial customer displays, media and file-processing pipelines.

### Tech

**Frontend** — TypeScript, React, Next.js, Tailwind CSS, Vite
**Backend** — NestJS, Node.js, Django, Django REST Framework, Python, Celery
**Data** — PostgreSQL, Redis, Prisma, MongoDB
**Infrastructure** — Docker, Nginx, Linux, GitHub Actions

---

## Featured work

### [LkSystem ERP](https://github.com/lk-cosmetics/LkSystemProd)
`in production` · `sole developer`

ERP, POS and business-intelligence platform for the **therapybylk** cosmetics group. Multi-brand and
multi-channel, with a real-time dashboard, an integrated point of sale and a WooCommerce
synchronisation pipeline. First commit to running production system, and I still maintain it.

Two details worth calling out. The POS talks to physical hardware through small FastAPI bridge
services, an ESC/POS thermal printer and a serial customer display. The whole stack ships through
GitHub Actions onto a VPS behind Nginx, with automated Let's Encrypt renewal.

`Django 5` `Django REST Framework` `Channels (ASGI)` `Celery` `PostgreSQL 15` `Redis 7` `React 19` `Vite` `Tailwind CSS` `Docker Compose` `Nginx` `GitHub Actions`

### ORALIGN Platform
`in production` · `sole developer` · `private repository`

Case-management and production-tracking platform for a clear-aligner manufacturer. Patient files,
treatment orders, clinical workflow and the manufacturing pipeline behind them.

Private because it is a commercial product. Happy to walk through the architecture in an interview.

`NestJS` `Prisma` `PostgreSQL` `Next.js (App Router)` `TypeScript` `Docker` `Nginx` `GitHub Actions`

### [E-Learning Platform API](https://github.com/sakerhajji/elearning-platform-api)

Backend for an online course platform. Catalogue and lessons, video upload and transcoding with
per-user progress tracking, quizzes, PDF certificates with QR verification, a discussion forum, and
an order flow paying through both Stripe and PayPal. Around 30 route modules over 20 data models.

`Node.js` `Express` `MongoDB` `Mongoose` `Socket.IO` `JWT + OAuth 2.0` `Stripe` `PayPal` `Cloudinary` `ffmpeg` `Docker`

### [LatexLocal](https://github.com/sakerhajji/LatexLocal)

Reproducible Docker deployment of a self-hosted Overleaf Community Edition instance, including a
MongoDB replica set, Redis and a LaTeX toolchain preconfigured with the packages and fonts real
reports need. Built because the hosted options did not fit the constraints, and packaged so it comes
up with one command.

`Docker` `Docker Compose` `MongoDB 8` `Redis 6.2` `LaTeX` `GitHub Actions`

---

### Experience

**Full-Stack Software Engineer** — LK Cosmetics / Therapy by LK · Sep 2024 – Aug 2026
**Full-Stack Software Engineer, freelance** — Aura Aligners, Dr Bloom, Ania Naturals · Sep 2024 – Jun 2025
**Full-Stack Software Engineer** — Société Dessin Technique Divers · Oct 2022 – Sep 2024

Java and Spring Boot, .NET, Angular and C++ alongside the stack above. Full history on
[LinkedIn](https://www.linkedin.com/in/sakerhajji/).

---

### Contact

Open to full-stack engineering roles, on-site abroad, hybrid or remote, and to freelance work on
production systems.

**Email** [saker.hajji13@gmail.com](mailto:saker.hajji13@gmail.com) · **LinkedIn** [sakerhajji](https://www.linkedin.com/in/sakerhajji/) · **GitHub** [@sakerhajji](https://github.com/sakerhajji)
