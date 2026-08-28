<h1 align="center">Saker Hajji</h1>

<p align="center">
  <strong>Full-Stack Software Engineer</strong><br>
  I design, build and run production web systems — API to database to deployed server.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Based_in-Tunis,_Tunisia-1f2328?style=flat-square" alt="Tunis, Tunisia">
  <img src="https://img.shields.io/badge/Open_to-Relocation_%26_Remote-1f2328?style=flat-square" alt="Open to relocation and remote">
  <img src="https://img.shields.io/badge/Focus-TypeScript_%C2%B7_Python-1f2328?style=flat-square" alt="Focus: TypeScript and Python">
</p>

---

### About

I build complete products rather than isolated features. Most of my recent work has been
taking a system from an empty repository to something a business actually runs on: schema
design, REST APIs, a real frontend, containerisation, a reverse proxy, TLS, CI/CD and the
ongoing maintenance that follows.

I work comfortably on both sides of the stack — **Next.js / React / TypeScript** on the
front, **NestJS / Node.js** and **Django / DRF** on the back — and I own the deployment
rather than handing it off.

Currently employed and open to international and remote opportunities.

### What I focus on

- **Product engineering end to end** — requirements, data model, API, UI, deployment.
- **Backend architecture** — REST API design, relational modelling, background jobs, caching, WebSocket and real-time layers.
- **Deployment and operations** — Docker Compose on Linux VPS, Nginx reverse proxying, Let's Encrypt TLS renewal, GitHub Actions pipelines.
- **Integrations** — WooCommerce synchronisation, payment providers, hardware bridges (ESC/POS thermal printers, serial customer displays), media and file-processing pipelines.

### Tech

**Frontend**  
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

**Backend**  
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/Django_REST-A30000?style=flat-square&logo=django&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

**Data**  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**Infrastructure**  
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

### Featured work

#### [LkSystem ERP](https://github.com/lk-cosmetics/LkSystemProd) · in production

ERP / POS / business-intelligence platform for the **therapybylk** cosmetics group —
multi-brand, multi-channel, with a real-time dashboard, an integrated point of sale and a
WooCommerce synchronisation pipeline. Sole developer, from the first commit to the running
production system I still maintain.

`Django 5` `Django REST Framework` `Channels (ASGI)` `Celery` `PostgreSQL 15` `Redis 7` `React 19` `Vite` `TailwindCSS` `Docker Compose` `Nginx` `GitHub Actions`

Two details worth calling out: the POS talks to physical hardware through small FastAPI
bridge services (ESC/POS thermal printer, serial customer display), and the whole stack
deploys through GitHub Actions onto a VPS behind Nginx with automated Let's Encrypt renewal.

→ Live: [lksystem.therapybylk.com](https://lksystem.therapybylk.com)

#### ORALIGN Platform · in production · private repository

Case-management and production-tracking platform for a clear-aligner manufacturer —
patient files, treatment orders, clinical workflow and the manufacturing pipeline behind
them. Sole developer.

`NestJS` `Prisma` `PostgreSQL` `Next.js (App Router)` `TypeScript` `Docker` `Nginx` `GitHub Actions`

The repository is private because it is a commercial product. Happy to walk through the
architecture in an interview.

#### [E-Learning Platform API](https://github.com/sakerhajji/elearning-platform-api)

Backend for an online course platform: catalogue and lessons, video upload and transcoding
with per-user progress tracking, quizzes, PDF certificates with QR verification, a
discussion forum, and an order flow paying through both Stripe and PayPal. Around 30 route
modules over 20 data models.

`Node.js` `Express` `MongoDB` `Mongoose` `Socket.IO` `JWT + OAuth 2.0` `Stripe` `PayPal` `Cloudinary` `ffmpeg` `Docker`

#### [LatexLocal](https://github.com/sakerhajji/LatexLocal)

Reproducible Docker deployment of a self-hosted Overleaf Community Edition instance,
including a MongoDB replica set, Redis, and a LaTeX toolchain preconfigured with the
packages and fonts real reports need. Built because the hosted options did not fit the
constraints; packaged so it comes up with one command.

`Docker` `Docker Compose` `MongoDB 8` `Redis 6.2` `LaTeX` `GitHub Actions`

#### [Health Tracker](https://github.com/sakerhajji/laravelProject5Twin3)

Health and wellness tracking platform for students and educators — habit tracking,
progress reporting and a symptom-based guidance tool. Team project; I worked on the
backend and the Docker/CI setup.

`Laravel` `PHP` `MySQL` `Docker` `Vite`

---

### Contact

I'm open to full-stack engineering roles — on-site abroad, hybrid or remote — and to
freelance work on production systems.

- **GitHub** — [@sakerhajji](https://github.com/sakerhajji)
