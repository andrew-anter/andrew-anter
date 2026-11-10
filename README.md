<div align="center" markdown="1">

# Andrew Anter

**End-to-End Product Engineer** · Cairo, Egypt

<a href="mailto:andrew.anter@gmail.com"><img src="https://img.shields.io/badge/andrew.anter@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://linkedin.com/in/andrew-anter"><img src="https://img.shields.io/badge/linkedin.com/in/andrew--anter-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>

</div>

---

<br>

## 👋 About me

I'm a product engineer: I take things from an idea to a running system, and I stay to operate what I built.

<br>

- **What I do** — I build systems end to end, backend to frontend, whatever the business problem needs — lately with the help of agentic AI. Deep expertise in document management and document intelligence: ingestion, extraction, search at scale.

- **How I work** — requirements come from the people doing the work, not a spec sheet. I own the full path: I sit with users, choose the hardware, design the architecture, then deploy and run the result in production.

- **Where it runs** — most of my work is fully air-gapped, on-prem environments with local LLM/VLM inference, so I design for zero external dependencies by default.

- **Cloud side** — I also run multiple production deployments on DigitalOcean, hardened end-to-end: Cloudflare WAF in front, and a DigitalOcean cloud firewall that only accepts traffic from Cloudflare. Security is a design constraint from day one, not a patch at the end.

- **Where I started** — I joined a company that had no servers, no code, and no infrastructure. I built all of it, and I later led its small engineering team.

<br>

---

<br>

## 🛠️ What I build with

<br>

<img src="https://skillicons.dev/icons?i=python,django,go,postgres,redis,rabbitmq,docker,debian,linux,opencv,git,gitlab,bash&theme=light" width="100%" alt="Tech stack" />

<br>

- **Languages & frameworks** — Python (strict typing), Go, Django (MVT, custom middleware, HTMX), Celery
- **Data & messaging** — PostgreSQL (per-VM tuning), Meilisearch, Redis/Valkey, MinIO, RabbitMQ
- **AI & document processing** — llama.cpp + Qwen3.5-9B (VLM extraction), OpenCV2 (AVX-512), Tesseract OSD
- **Infrastructure** — Docker, Podman, Debian, Proxmox VE + ZFS RAID-1, SeaweedFS, Caddy, pfSense
- **Security** — Samba AD + GPO, Cloudflare WAF, UFW, CrowdSec, OSV-Scanner, Bandit
- **Quality** — Pytest, Ruff, BasedPyright

<br>

---

<br>

## 📌 Featured projects

<br>

| Project | What it does | Stack |
|---|---|---|
| **[Logistics-Portal](https://github.com/andrew-anter/Logistics-Portal)** | Multi-tenant backend for a logistics SaaS platform: complete REST API, Celery async processing, Dockerized behind NGINX | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) ![DRF](https://img.shields.io/badge/REST_Framework-092E20?style=flat-square&logo=djangorestframework&logoColor=white) |
| **[TaskMaster](https://github.com/andrew-anter/TaskMaster)** | Django 5 task manager with an HTMX single-page feel: labels, notifications, reminders, REST API, Tailwind + daisyUI light/dark | ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) ![HTMX](https://img.shields.io/badge/HTMX-3D72D7?style=flat-square) |
| **[content-searcher](https://github.com/andrew-anter/content-searcher)** | Offline desktop search (Wails v2): indexes PDF/Word documents with SQLite FTS5 — Arabic/English normalization so diacritics and spelling variants still match | ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![Vue](https://img.shields.io/badge/Vue_3-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) |
| **[pages_counter](https://github.com/andrew-anter/pages_counter)** | Streams page counts from `.tar.zst` archives and loose PDFs — never fully loaded into RAM; parallel workers, CLI and GUI | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| **[todo-golang](https://github.com/andrew-anter/todo-golang)** | `td` — terminal todo app in Go: interactive Bubble Tea TUI plus scriptable pipe mode, projects as namespaces, layered config | ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) |

