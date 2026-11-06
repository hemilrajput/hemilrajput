<h1 align="center">Hemil Rajput</h1>

<p align="center">
  <strong>Senior Full-Stack, AI &amp; Infrastructure Engineer</strong><br/>
  Laravel · TypeScript · Python · Node.js · AWS · AI Workflows
</p>

<p align="center">
  <a href="https://hemil-rajput.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-hemil--rajput.vercel.app-0e75b6?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio"/>
  </a>
  <a href="mailto:rajputhemil4@gmail.com">
    <img src="https://img.shields.io/badge/Email-rajputhemil4%40gmail.com-0e75b6?style=flat-square&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://www.linkedin.com/in/hemil-rajput/">
    <img src="https://img.shields.io/badge/LinkedIn-hemil--rajput-0e75b6?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://packagist.org/packages/hemilrajput/laravel-typegen">
    <img src="https://img.shields.io/badge/Packagist-laravel--typegen-0e75b6?style=flat-square&logo=packagist&logoColor=white" alt="Packagist"/>
  </a>
</p>

<p align="center">
  <em>Open to high-impact Full-Stack, Backend, and AI Product Engineering roles — Global Remote (UTC+5:30).</em>
</p>

---

I architect, build, and operate production web systems and AI-powered workflows: from type-safe frontends and high-throughput API layers to the databases, LLM pipelines, and cloud servers underneath. Currently leading full-stack product engineering and AWS infrastructure at **cWiser InfoTech**.

Five years into shipping production software, my work spans the full lifecycle—building end-to-end product features in **Laravel, TypeScript, Node.js, and Python**, designing **autonomous AI agent workflows**, and automating the **Docker + AWS infrastructure** that keeps systems fast and reliable.

<br/>

## Open Source Spotlight: `laravel-typegen`

<table>
<tr>
<td width="60%" valign="top">

One Artisan command that generates strict TypeScript definitions directly from your Eloquent models, PHP Enums, and FormRequests.

Solves the manual type-syncing bottleneck in decoupled Laravel + Inertia/React/Vue projects, where backend PHP models and frontend TypeScript interfaces drift apart silently and cause runtime failures in production.

**[Repository](https://github.com/hemilrajput/laravel-typegen)** ·
**[Documentation](https://hemilrajput.github.io/laravel-typegen/)** ·
**[Packagist](https://packagist.org/packages/hemilrajput/laravel-typegen)**

<br/>

<a href="https://packagist.org/packages/hemilrajput/laravel-typegen">
  <img src="https://img.shields.io/packagist/v/hemilrajput/laravel-typegen?style=flat-square&color=0e75b6&label=version" alt="Version"/>
</a>
<a href="https://packagist.org/packages/hemilrajput/laravel-typegen">
  <img src="https://img.shields.io/packagist/dt/hemilrajput/laravel-typegen?style=flat-square&color=0e75b6&label=downloads" alt="Downloads"/>
</a>
<img src="https://img.shields.io/packagist/l/hemilrajput/laravel-typegen?style=flat-square&color=0e75b6&label=license" alt="License"/>

</td>
<td width="40%" valign="top">

```bash
composer require \
  hemilrajput/laravel-typegen --dev

php artisan typegen:generate
```

```ts
// resources/js/types/generated.ts
export interface User {
  id: number
  email: string
  role: UserRole
}
```

</td>
</tr>
</table>

<br/>

## Selected Engineering Work

**AI Workflow Automation & Agentic Pipelines**
Built deterministic LLM orchestration flows and autonomous coding/data pipelines using **Python, Node.js, Claude API, and OpenAI**. Implemented structured JSON schema validation, tool-calling integrations, and automated execution loops that cut manual engineering and data processing overhead by over **60%**.

**Multi-Tenant SaaS & API Platform** — *cWiser InfoTech*
Architected and own the core backend and API layer for high-concurrency web applications using **Laravel, MySQL/PostgreSQL, and Redis**. Engineered asynchronous queue workers, webhook processing, and query-level caching to maintain sub-150ms API response times under heavy production traffic.

**Zero-Downtime CI/CD Deployment Pipeline**
Replaced fragile manual server deployments with automated **GitHub Actions CI/CD** pipelines and containerized **Docker** builds. Cut production deployment times from **35+ minutes to under 3 minutes**, with automated health checks and single-command rollbacks.

**AWS Cloud Infrastructure & Cost Optimization**
Manage server provisioning, **Nginx** reverse-proxy tuning, SSL/security hardening, and database backups across **AWS (EC2, RDS, S3)**. Reduced monthly cloud infrastructure spend by **~30%** by right-sizing compute instances, optimizing RDS slow queries, and offloading static assets to S3 lifecycle policies.

<br/>

## Technical Capabilities

| Layer | Technologies & Tooling |
|---|---|
| **Backend & APIs** <br/> <sub>daily production stack</sub> | PHP · Laravel · Python · Node.js (Express) · REST APIs · Webhooks · Queue Workers |
| **AI & Automation** <br/> <sub>agentic systems & LLM flows</sub> | Claude API · OpenAI API · Agentic Workflows · Tool Calling · Structured JSON Outputs · Prompt Engineering |
| **Frontend & DX** <br/> <sub>type-safe interfaces & tooling</sub> | TypeScript · Vue.js · React · Next.js · Inertia.js · Tailwind CSS · AST / Reflection Codegen |
| **Data & Caching** <br/> <sub>schema design & indexing</sub> | MySQL · PostgreSQL · Redis (Caching, Queues, Pub/Sub) · Query Optimization |
| **Cloud & DevOps** <br/> <sub>provisioning & delivery</sub> | AWS (EC2, RDS, S3) · Docker · Linux Server Admin · Nginx · GitHub Actions (CI/CD) |
| **Exploring** <br/> <sub>active R&D</sub> | Kubernetes · Terraform · Go · Vector Databases (`pgvector`) |

<br/>

<details>
<summary><strong>What I typically build</strong></summary>

<br/>

- **AI-Powered Workflows & Agents:** Multi-step LLM automation pipelines in Python and Node.js that connect Claude/GPT models to internal APIs, databases, and validation schemas.
- **Scalable API Backends:** High-throughput REST and headless APIs in Laravel, Node.js, and Python with JWT/OAuth security, rate limiting, and Redis job queues.
- **Type-Safe Full-Stack Apps:** End-to-end web products using Laravel + Inertia or decoupled Vue/React/Next.js frontends backed by automated TypeScript contract generation (`laravel-typegen`).
- **Cloud & Deployment Infrastructure:** Containerized Docker environments behind Nginx on AWS EC2/RDS, wired to GitHub Actions for automated testing, deployment, and instant rollback.

</details>

<details>
<summary><strong>How I work</strong></summary>

<br/>

I prefer boring, predictable systems over clever code, and I would rather spend an hour automating a CLI tool or deployment pipeline than waste ten minutes doing a repetitive task by hand. Most of what I know about building resilient architecture—and why I built `laravel-typegen`—comes from being the engineer responsible for maintaining and scaling systems in production after launch.

</details>

<br/>

---

<p align="center">
  <sub>
    <a href="https://hemil-rajput.vercel.app/">Portfolio</a> ·
    <a href="mailto:rajputhemil4@gmail.com">rajputhemil4@gmail.com</a> ·
    <a href="https://www.linkedin.com/in/hemil-rajput/">LinkedIn</a> ·
    <a href="https://packagist.org/packages/hemilrajput/laravel-typegen">Packagist</a> ·
    <a href="https://hemilrajput.github.io/laravel-typegen/">laravel-typegen Docs</a>
  </sub>
</p>
