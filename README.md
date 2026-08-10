<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=220&section=header&text=Lucas%20Casa%20Mausa&fontSize=52&fontColor=ffffff&fontAlignY=36&desc=Software%20Engineer%20·%20Backend%20·%20Distributed%20Systems&descSize=17&descAlignY=57&animation=fadeIn" width="100%" />

<a href="https://www.linkedin.com/in/lucas-casa-mausa">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=900&color=36BCF7&center=true&vCenter=true&width=650&lines=Backend+engineer+at+a+Brazilian+credit+fintech;I+care+about+the+failure+mode%2C+not+the+happy+path;TOCTOU%2C+idempotency%2C+race+conditions%2C+CTEs;Cut+a+production+LCP+from+5.2s+to+1.7s;Building+an+L7+load+balancer+in+Go+from+scratch" alt="Typing SVG" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lucas-casa-mausa)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://lucas-casa-mausa.github.io/)
[![Gmail](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:lucascasamausa000@gmail.com)
[![Profile Views](https://komarev.com/ghpvc/?username=Lucas-Casa-Mausa&color=0A66C2&style=for-the-badge&label=PROFILE+VIEWS)](https://github.com/Lucas-Casa-Mausa)

</div>

<img src="https://raw.githubusercontent.com/Lucas-Casa-Mausa/Lucas-Casa-Mausa/output/github-contribution-grid-snake-dark.svg" width="100%" />

## <img src="https://media.giphy.com/media/iY8CRBdQXODJSCERIr/giphy.gif" width="30"> &nbsp; About

I'm one of four engineers building the credit and real estate financing infrastructure at **aMORA**, a Brazilian fintech. At that team size you touch everything — backend, frontend, database, bank integrations — and you learn fast that the interesting part of a financial system is never the happy path.

```python
class Engineer:
    name      = "Lucas Casa Mausa"
    location  = "São Paulo, Brasil"
    role      = "Software Engineer @ aMORA"
    stack     = ["TypeScript", "Python", "Go", "SQL"]
    obsessed  = ["concurrency", "query plans", "failure modes", "observability"]
    currently = "an L7 load balancer in Go, stdlib only"
```

<div align="center">
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Gear.png" width="18" /> <b>Some things I shipped</b>
</div>

<table>
<tr>
<td width="50%" valign="top">

**⚡ Production LCP: 5.2s → 1.7s**

Ran Lighthouse, mapped the load timeline, found an auth waterfall holding every fetch hostage. Same-origin proxy, fetch dedup, cascade broken. API calls per page load went from 12–14 to 4–5.

</td>
<td width="50%" valign="top">

**🗃️ Correlated subqueries → set-based CTEs**

Six correlated `MAX` subselects per row on a 500-card board meant thousands of index scans in one statement. Rewrote as `GROUP BY` aggregations, verified with `EXPLAIN ANALYZE`.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**🔒 Soft-delete under concurrency**

96 files. Portfolio reassignment, TOCTOU guards, retriable races, transaction compensation across auth, service desk and notifications.

</td>
<td width="50%" valign="top">

**🛡️ Multi-tenant audit harness**

Four layers — compile-time gate, CI coverage ledger, Prisma extension, SQL invariants — guarding a migration across 72 models and 310 HTTP handlers.

</td>
</tr>
</table>

## <img src="https://media.giphy.com/media/WFZvB7VIXBgiz3oDXE/giphy.gif" width="30"> &nbsp; Stack

<div align="center">

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Backend & Async**

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)
![BullMQ](https://img.shields.io/badge/BullMQ-FF4438?style=for-the-badge&logo=redis&logoColor=white)

**Data**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white)

**Auth, DevOps & Tooling**

![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)

</div>

## <img src="https://media.giphy.com/media/LnQjpWaON8nhr21vNW/giphy.gif" width="30"> &nbsp; Featured

<table>
<tr>
<td width="50%" valign="top">

### [gobalance](https://github.com/Lucas-Casa-Mausa/gobalance) &nbsp; ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)

L7 load balancer and reverse proxy in **pure Go stdlib** — round-robin, active health checks, rate limiting and circuit breaker.

Built to understand how each piece works from the inside instead of configuring an nginx.

</td>
<td width="50%" valign="top">

### [THREADS](https://github.com/Lucas-Casa-Mausa/THREADS) &nbsp; ![Python](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

Interactive platform teaching **threads, concurrency and parallelism** through visual animations and quizzes.

FastAPI + React + PostgreSQL, Alembic migrations, Docker Compose.

</td>
</tr>
</table>

## <img src="https://media.giphy.com/media/dWesBcTLavkZuG35MI/giphy.gif" width="30"> &nbsp; Stats

<div align="center">

<img width="80%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Lucas-Casa-Mausa&theme=github_dark" />

<img width="42%" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Lucas-Casa-Mausa&theme=github_dark" />
<img width="42%" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Lucas-Casa-Mausa&theme=github_dark" />

<img width="42%" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Lucas-Casa-Mausa&theme=github_dark" />
<img width="42%" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Lucas-Casa-Mausa&theme=github_dark&utcOffset=-3" />

<img width="85%" src="https://streak-stats.demolab.com?user=Lucas-Casa-Mausa&theme=tokyonight&hide_border=true&background=0D1117&ring=36BCF7&fire=36BCF7&currStreakLabel=36BCF7" />

<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=Lucas-Casa-Mausa&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=36BCF7&line=36BCF7&point=ffffff&area=true&area_color=36BCF7" />

<img src="https://github-profile-trophy.vercel.app/?username=Lucas-Casa-Mausa&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=8&margin-h=8" />

</div>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=140&section=footer&text=Open%20to%20backend%20and%20platform%20engineering%20roles&fontSize=17&fontColor=ffffff&fontAlignY=72" width="100%" />

</div>
