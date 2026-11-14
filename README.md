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

- **What I do** — I build systems end to end, backend to frontend, whatever the business problem needs — lately with the help of agentic AI. Deep expertise in document management and document intelligence: ingestion, extraction, dual-engine full-text search.

- **How I work** — requirements come from the people doing the work, not a spec sheet. I own the full path: I sit with users, choose the hardware, design the architecture, then deploy and run the result in production.

- **Where it runs** — most of my work is fully air-gapped, on-prem environments with local LLM/VLM inference, so I design for zero external dependencies by default.

- **Cloud side** — I also run production client web apps in the cloud, hardened end-to-end: Cloudflare WAF in front, and a DigitalOcean cloud firewall that only accepts traffic from Cloudflare. Security is a design constraint from day one, not a patch at the end.

- **Where I started** — I joined a company that had no servers, no code, and no infrastructure. I built all of it, and I later led its small engineering team.

<br>

---

<br>

## 🛠️ What I build with

<br>

<img src="https://skillicons.dev/icons?i=python,django,vue,go,postgres,rabbitmq,docker,debian,linux,opencv,git,gitlab,bash&theme=light" width="100%" alt="Tech stack" />

<br>

- **Languages & frameworks** — Python (strict typing), Go, Django (MVT, custom middleware, HTMX), Django Ninja + Pydantic, Vue.js, Celery
- **Data & messaging** — PostgreSQL (per-VM tuning), Meilisearch, Valkey (caching, locks, sessions), RabbitMQ
- **AI & document processing** — llama.cpp + Qwen3.5-9B (VLM extraction), OpenCV (AVX-512), Tesseract OCR, in-house-trained orientation CNN that I integrated
- **Infrastructure** — Docker Compose, Podman, Debian, Proxmox VE + ZFS RAID-1, SeaweedFS, Caddy, pfSense
- **Security** — Samba AD + GPO, Cloudflare WAF, UFW, CrowdSec, OSV-Scanner, Bandit
- **Quality** — Pytest, Ruff, basedpyright, Locust, uv

<br>

---

<br>

## 📌 Featured projects

<br>

| Project | What it does | Stack |
|---|---|---|
| **[Mirrorling](https://github.com/andrew-anter/Mirrorling)** | AirPlay 2 screen-mirroring sender for Linux → Samsung Tizen TVs: SRP-6a pairing, Wayland/X11 capture, GStreamer encoding — CLI + Wails control panel + tray in a single-file release, with a hardware-free regression suite | ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) |
| **[TaskMaster](https://github.com/andrew-anter/TaskMaster)** | Django 5 task manager with an HTMX single-page feel: labels, notifications, reminders, REST API, Tailwind + daisyUI light/dark | ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) ![HTMX](https://img.shields.io/badge/HTMX-3D72D7?style=flat-square) |
| **[td](https://github.com/andrew-anter/td)** | Terminal task manager in Go: bidirectional sync with self-hosted GitLab (conflict-resolved), atomic JSON persistence with file locking, Bubble Tea TUI + scriptable CLI parity, per-command tests | ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) |
| **[content-searcher](https://github.com/andrew-anter/content-searcher)** | Offline desktop search (Wails v2): indexes PDF/Word documents with SQLite FTS5 — Arabic/English normalization so diacritics and spelling variants still match | ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![Vue](https://img.shields.io/badge/Vue_3-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) |
| **[pages_counter](https://github.com/andrew-anter/pages_counter)** | Streams page counts from `.tar.zst` archives and loose PDFs — never fully loaded into RAM; parallel workers, CLI and GUI | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |

<br>

---

<br>

## 🔀 Open-source contributions

<br>

| Project | Contribution | Status |
|---|---|---|
| **[ReGreet](https://github.com/rharish101/ReGreet)** — greetd greeter (Rust/GTK4) | [#173: friendly message on authentication failure](https://github.com/rharish101/ReGreet/pull/173) — raw PAM `AUTH_ERR` → "Authentication failed", deliberately generic because `pam_faillock` lockouts share the error; raw detail kept in the log | **Merged** (2026-10-29) |
| **[avante.nvim](https://github.com/avante-corp/avante.nvim)** — AI coding assistant for Neovim | [#3310: replace os.remove with recursive libuv deletion in llm_tools](https://github.com/avante-corp/avante.nvim/pull/3310) | Open |