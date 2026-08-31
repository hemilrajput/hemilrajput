<h1 align="center">Hemil Rajput</h1>

<p align="center">
  <strong>Backend &amp; Infrastructure Engineer</strong><br/>
  Laravel · AWS · Ahmedabad, India
</p>

<p align="center">
  <a href="mailto:rajputhemil4@gmail.com">
    <img src="https://img.shields.io/badge/Email-rajputhemil4%40gmail.com-0e75b6?style=flat-square&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://www.linkedin.com/in/hemil-rajput/">
    <img src="https://img.shields.io/badge/LinkedIn-hemil--rajput-0e75b6?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://packagist.org/packages/hemilrajput/laravel-typegen">
    <img src="https://img.shields.io/badge/Packagist-hemilrajput-0e75b6?style=flat-square&logo=packagist&logoColor=white" alt="Packagist"/>
  </a>
</p>

<p align="center">
  <em>Open to backend and platform engineering roles — remote or Ahmedabad.</em>
</p>

---

I build and run production web applications: the API layer, the database, and the
servers underneath. Currently Senior Web Developer at **cWiser InfoTech**, where I own
Laravel product development and the AWS infrastructure it runs on.

Five years in, my work has moved steadily down the stack — from building features, to
building the APIs behind them, to running the infrastructure that keeps them up.

<br/>

## `laravel-typegen`

<table>
<tr>
<td width="60%" valign="top">

One Artisan command that generates TypeScript definitions from your Eloquent models,
Enums, and FormRequests.

Solves the hand-syncing problem in Laravel + Inertia projects, where PHP types and
TypeScript types drift apart silently and you find out in production.

**[Repository](https://github.com/hemilrajput/laravel-typegen)** ·
**[Documentation](https://hemilrajput.github.io/laravel-typegen/)**

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

## Selected work

> **Fill in the bracketed values with real numbers from your own systems, then delete
> this note. A vague claim is worse than no claim.**

**Laravel product platform** — *cWiser InfoTech*
Own the backend for `[what the product does, one line]`. Serving
`[requests/day, active users, or data volume]`.

**Deployment pipeline**
Replaced manual deploys with GitHub Actions CI/CD. Deploy time went from
`[before]` to `[after]`; rollback is now a single revert.

**AWS infrastructure**
Provisioning, nginx configuration, monitoring, and cost management across EC2, RDS,
and S3. Reduced monthly spend by `[% or rupee amount]` through `[what you actually changed]`.

<br/>

## Technical background

| | |
|---|---|
| **Core** <br/> <sub>daily work, interview-ready</sub> | PHP · Laravel · MySQL · TypeScript · Vue · Linux · nginx · Docker · AWS (EC2, RDS, S3) · GitHub Actions |
| **Working knowledge** <br/> <sub>shipped to production, not my specialism</sub> | Node.js · Express · PostgreSQL · Redis · React · Tailwind CSS |
| **Currently learning** | Kubernetes · Terraform · Go |

<br/>

<details>
<summary><strong>What I typically build</strong></summary>

<br/>

- REST and headless APIs in Laravel, with JWT / OAuth authentication
- Laravel + Inertia applications with Vue or React front ends
- Containerised deployments behind nginx on AWS EC2
- CI/CD pipelines in GitHub Actions — test, build, deploy, rollback
- Database design and query optimisation on MySQL and PostgreSQL

</details>

<details>
<summary><strong>How I work</strong></summary>

<br/>

I prefer boring, obvious code over clever code, and I would rather spend an hour on a
deployment script than an hour redoing a deploy by hand. Most of what I have learned
about writing maintainable software came from being the person on call for it
afterwards.

</details>

<br/>

---

<p align="center">
  <sub>
    <a href="mailto:rajputhemil4@gmail.com">rajputhemil4@gmail.com</a> ·
    <a href="https://www.linkedin.com/in/hemil-rajput/">LinkedIn</a> ·
    <a href="https://packagist.org/packages/hemilrajput/laravel-typegen">Packagist</a>
  </sub>
</p>
