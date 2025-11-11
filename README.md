<!-- Profile Header -->
<h1 align="center">Hi, I'm Nick — Python Backend/Systems Engineer</h1>
<p align="center">
  I build reliable backend services and data infrastructure: <b>FastAPI + asyncio</b>, typed APIs (OpenAPI/pydantic),
  observability (<b>Prometheus · Grafana · Thanos · ELK · Sentry</b>), and delivery with <b>Docker · GitLab CI</b>.
  System background in storage (ALUA, replication tech's, NVMe-oF), Linux networking, and HA/failover.
</p>

<p align="center">
  <a href="mailto:kusenov00@gmail.com">Email</a> ·
  <a href="https://t.me/ImStolas">Telegram</a> ·
  <a href="https://www.linkedin.com/in/nikita-kusenov-ba1185386/">LinkedIn</a>
</p>

---

### Snapshot (4y+ commercial)
- **Aerodisk — Backend/Systems (high-end Storage, HA):** server side for storage subsystems; SCSI/ALUA, iSCSI, NVMe-oF (TCP/FC/RDMA), NFS/SMB/S3, replication tech's, snapshots, CLI & API gateways (FastAPI/Flask), cluster observability (Prometheus+Thanos+Grafana), incident handling (SLO/SLI, runbooks).
- **ALONG — Backend for web & mobile:** auth (OTP/OAuth2/phone, JWT blacklist & rotation), subscriptions & payments, notifications; greenfield microservices, DB design & p95/p99 tuning, CI pipelines, customer-facing SDK/docs.
- **CIIR — EdTech/Robotics backend:** Django/DRF monolith + small Flask services for telemetry ingestion; Celery pipelines, OpenCV preprocessing, MinIO for artifacts, GitHub Actions, basic ELK/Grafana dashboards.

---

### Core stack
<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3.7→3.12-3776AB?logo=python&logoColor=white" />
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-asyncio/httpx-009688?logo=fastapi&logoColor=white" />
  <img alt="pydantic" src="https://img.shields.io/badge/pydantic-typed_models-E92063" />
  <img alt="SQLAlchemy" src="https://img.shields.io/badge/SQLAlchemy-2.x-9F2B2F" />
  <img alt="Django DRF" src="https://img.shields.io/badge/Django-DRF-092E20?logo=django&logoColor=white" />
  <img alt="gRPC" src="https://img.shields.io/badge/gRPC/REST-contracts-5E5E5E" />
  <img alt="OpenAPI" src="https://img.shields.io/badge/OpenAPI-contracts-6BA539?logo=openapiinitiative&logoColor=white" />
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-DB-4169E1?logo=postgresql&logoColor=white" />
  <img alt="MySQL" src="https://img.shields.io/badge/MySQL-DB-005C84?logo=mysql&logoColor=white" />
  <img alt="Redis" src="https://img.shields.io/badge/Redis-cache/queue-DC382D?logo=redis&logoColor=white" />
  <img alt="SQLite" src="https://img.shields.io/badge/SQLite-local-003B57?logo=sqlite&logoColor=white" />
  <img alt="Linux" src="https://img.shields.io/badge/Linux-networking/VMs-333?logo=linux&logoColor=white" />
  <img alt="Docker" src="https://img.shields.io/badge/Docker-containers-2496ED?logo=docker&logoColor=white" />
  <img alt="GitLab CI" src="https://img.shields.io/badge/GitLab-CI/CD-FC6D26?logo=gitlab&logoColor=white" />
  <img alt="Prometheus" src="https://img.shields.io/badge/Prometheus-metrics-E6522C?logo=prometheus&logoColor=white" />
  <img alt="Grafana" src="https://img.shields.io/badge/Grafana-dashboards-F46800?logo=grafana&logoColor=white" />
  <img alt="Thanos" src="https://img.shields.io/badge/Thanos-long_term-7F3FBF" />
  <img alt="ELK" src="https://img.shields.io/badge/ELK-central_logs-005571?logo=elastic&logoColor=white" />
  <img alt="Sentry" src="https://img.shields.io/badge/Sentry-errors-362D59?logo=sentry&logoColor=white" />
  <img alt="OpenStack" src="https://img.shields.io/badge/OpenStack-Cinder_driver-ED1944?logo=openstack&logoColor=white" />
</p>

**Data/DB:** schema design, indexes, safe step-by-step migrations, query profiling, p95/p99 latency reduction  
**Ops/Delivery:** Dockerized apps, GitLab CI pipelines, release checklists, runbooks, staging→prod promotion  
**Observability:** SLI/SLO, alert routing, post-mortems; Prom/Thanos retention & downsampling, Grafana dashboards  
**Security:** JWT rotation/blacklist, session & cookie policies, idempotent webhooks, rate limits  
**Storage domain:** BTRFS, SCSI/ALUA, iSCSI, NVMe-oF (TCP/FC/RDMA), NFS/SMB/S3, replication tech's, snapshots

---

### Highlights
- **ALUA throughput ×2** and **no failover pauses** on link flaps (pathing policy & health checks).  
- **NVMe-JBOF**: from prototype to production — namespace publishing, auto discover/reattach in cluster.  
- **Cluster observability**: Prometheus + Thanos + Grafana, long-term retention with downsampling → lower disk/CPU overhead.  
- **p95 latency −30–50%** on critical endpoints (indexes, query plans, async clients with pools/backoff).  
- **Zero-downtime DB migrations** (feature flags, phased rollouts, backward-compatible contracts).  
- **Metrocluster**: stabilized replication, split-brain protection, automated failover/failback; passed chaos/load tests.

---

### Selected work (pin these)
- **dbaas-sdk-python** — idiomatic client (httpx+pydantic): auth, retries/backoff, pagination, examples, tests  
- **backup-scheduler** — FastAPI service for backup jobs: health, schedules, metrics, runbooks  
- **observability-starter** — Prom rules + Grafana dashboards for Python web services  
- **runbooks** — incident checklists (SLO/SLA, failover, PITR notes)

> I usually keep repos minimal and documented. Feel free to open issues or ping me in Telegram.

---

<details>
<summary>GitHub stats (click to expand)</summary>

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=glowystar&show_icons=true&hide=contribs&rank_icon=github" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=glowystar&layout=compact&hide=css,html" height="150" />
</p>

</details>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=glowystar&label=Profile%20views&color=0e75b6&style=flat" alt="profile views" />
</p>
