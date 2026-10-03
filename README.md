# Giang (gdq2k2)

**Infrastructure & Systems Engineer | Indie Homelab Enthusiast**  
Co-founder & Core Infrastructure Lead at [@529-studio](https://github.com/529-studio) (2-person indie engineering studio) • Ho Chi Minh City, Vietnam.

[![529 Studio](https://img.shields.io/badge/529_Studio-529studio.site-111111?style=flat-square&logo=cloudflare&logoColor=F38020)](https://529studio.site)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-dqgiang1123-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/dqgiang1123)
[![TOEIC](https://img.shields.io/badge/TOEIC-825%20%2F%20990-008080?style=flat-square)](mailto:giangdq.01012003@gmail.com)
[![Email](https://img.shields.io/badge/Email-giangdq.01012003%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:giangdq.01012003@gmail.com)

---

### ◆ What I Do

I build resilient backend services, automate CI/CD workflows, and operate hardened Linux edge infrastructure. Passionate about self-hosting, operating system internals, and pragmatic solutions with zero fluff.

* **Infrastructure & Edge Ops:** Co-managing self-hosted production services across Linux VPS clusters protected by Cloudflare Zero Trust, WireGuard tunnels, and Caddy reverse proxy with automated SSL.
* **Continuous Delivery & Automation:** Designing multi-arch Docker build pipelines via GitHub Actions, GHCR registries, zero-downtime webhook deployments on Dokploy/Portainer, and automated alert gateways via n8n.
* **Systems & Backend Engineering:** Crafting high-concurrency Go microservices (Gin, pgx, goroutines) and low-level macOS system utilities in pure Swift interfacing directly with Mach Kernel C-APIs.

---

### ◆ Featured Systems & Projects

#### ▸ Production & Low-Level Systems
* **[Vmarble MES](https://github.com/529-studio/Vmarble-Warehouse-Management-Service)** — *Production Manufacturing Execution System*  
  End-to-end MES backend & warehouse client actively serving an export stone and wood factory. Built with **Go 1.24**, **PostgreSQL 17** (row-level locking for concurrent slab cutting), **Next.js 15**, and **Dokploy** zero-downtime CD with automated off-site backups to **Cloudflare R2**.
* **[MeMo (Menu Monitor)](https://github.com/giangdq202/memo)** — *Lightweight macOS System Monitor in Pure Swift*  
  A near-zero CPU footprint menu bar monitor built without Xcode bloat (`swiftc -Osize -dead_strip`). Calls low-level **Mach Kernel C-APIs**, **BSD Sockets**, and dynamically probes hardware temperature sensors via **IOKit SMC** with automated versioning releases via GitHub Actions.

#### ▸ Telemetry & Autonomous Platforms
* **[projectKV](https://github.com/529-studio/projectKV)** — *City-Scale Traffic & Flood Intelligence*  
  High-throughput HCMC traffic camera surveillance system. Converted to a static **Go** backend leveraging goroutines for real-time camera snapshot schedulers & Server-Sent Events (SSE). Redeploys via **Portainer API** guarded by **Cloudflare Access Service Tokens** with **n8n** alert gateways.
* **[F1 Virtual Engineer](https://github.com/529-studio/f1-virtual-engineer)** ([Live Demo](https://f1.529studio.site)) — *Agentic AI Race Strategy Assistant*  
  Real-time Formula 1 tactical simulation powered by **Python**, **LangGraph**, **FastAPI**, **Redis**, and **RabbitMQ** with automated container deployment.
* **[JCertPre](https://github.com/giangdq202/JCertPre-BE)** — *Japanese Certification Prep Platform*  
  FPT University Capstone Project (**Grade: 8.6 / 10**). Comprehensive backend architected with **C# .NET 8**, **PostgreSQL**, **Redis**, and **SignalR**.

---

### ◆ Self-Hosted Homelab & Infrastructure (`529studio.site`)

All services within the 529 Studio ecosystem are self-hosted and operated end-to-end:
* **Ingress & Security:** Cloudflare Zero Trust (Access Service Tokens, Tunnel), Caddy / Nginx reverse proxy, WireGuard private VPN mesh.
* **Orchestration & Deploy:** Dokploy webhook triggers, Portainer CE, Docker Compose, GitHub Container Registry (ghcr.io).
* **Observability & Alerting:** Uptime Kuma heartbeat monitoring, n8n Automated Alert Gateway for real-time critical failure webhooks.

---

### ◆ Technical Toolchain

| Domain | Technologies & Tools |
| :--- | :--- |
| **Operating Systems & Low-Level** | Linux (Ubuntu, Debian), macOS, Mach Kernel APIs, BSD Sockets, IOKit SMC, Bash |
| **Infrastructure & Networking** | Docker, Docker Compose, Caddy, Nginx, WireGuard VPN, Cloudflare Zero Trust, Portainer, Dokploy |
| **DevOps & CI/CD** | GitHub Actions (multi-arch buildx, caching, releases), GHCR, n8n Automation, Uptime Kuma |
| **Backend & Concurrency** | Go (Gin, pgx, Goroutines), Python (FastAPI), C# (.NET 8), Java (Spring Boot) |
| **Storage & Databases** | PostgreSQL 17, Redis, SQLite, Cloudflare R2 (S3-compatible) |
| **Frontend & Mobile** | TypeScript, Next.js, React, React Native, Tailwind CSS |

---

### ◆ Activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/giangdq202/giangdq202/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/giangdq202/giangdq202/output/github-snake.svg" />
  <img alt="github contribution snake animation" src="https://raw.githubusercontent.com/giangdq202/giangdq202/output/github-snake.svg" />
</picture>

---

<p align="center">
  <sub>"Pour la Patrie, les Sciences et la Gloire" • Crafted by gdq2k2</sub>
</p>