<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1a2e,100:0d1117&height=120&section=header" width="100%"/>

```
██╗   ██╗ █████╗ ██╗     ██╗
██║   ██║██╔══██╗██║     ██║
██║   ██║███████║██║     ██║
╚██╗ ██╔╝██╔══██║██║     ██║
 ╚████╔╝ ██║  ██║███████╗██║
  ╚═══╝  ╚═╝  ╚═╝╚══════╝╚═╝
```

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&pause=1000&color=58A6FF&center=true&vCenter=true&width=500&lines=CS+%40+Lancaster+University;Co-Founder+%26+Lead+Engineer;Full-Stack+%7C+ML+%7C+Mobile;MMA+fan+who+codes+with+discipline)](https://www.vali-hameed.com)

![Profile Views](https://komarev.com/ghpvc/?username=Vali-Hameed&style=flat-square&color=58a6ff&label=profile+views)

[![Website](https://img.shields.io/badge/⚡vali--hameed.com-000000?style=for-the-badge&logoColor=white)](https://www.vali-hameed.com/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vali-hameed)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Valihameed88@gmail.com)

</div>

---

## `> whoami`

CS undergrad at Lancaster University chasing a First — but more importantly, someone who actually ships things.

I build from first principles: no framework cargo-culting, no tutorial-driven code. Across ML systems, full-stack web apps, mobile platforms, and everything in between — I care about taking ideas all the way to deployed, working products.

Currently: co-founding **Picky Eater** 🍽️ — a web + mobile platform I architect and engineer from the ground up.

Outside the terminal: I'm an MMA fan (Muay Thai & Kickboxing), which probably explains why I gravitate toward problems that require sustained effort and discipline.

---

## `> ls ./stack`

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Haskell](https://img.shields.io/badge/Haskell-5D4F85?style=flat-square&logo=haskell&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)

**Frontend / Mobile**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Backend / Infra**

![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

---

## `> cat ./projects`

---

### 🚀 Orbital Risk — *🥈 Runner-up, Leeds Hack 2026*

> A 3D launch-window optimisation system built under hackathon pressure. Real-time satellite orbit and debris field visualisation powered by WebGL and Three.js. A custom risk engine calculates collision probabilities against live debris density data, while an ML-driven weather service generates automated Go/No-Go launch decisions.

| Layer | Tech |
|---|---|
| Frontend | `Next.js 14` `TypeScript` `React` `Three.js / WebGL` |
| Backend | `Python` `FastAPI` `XGBoost` `Scikit-Learn` `Pandas` |

&nbsp;&nbsp;[🔗 Live Demo](https://leedshack2026-prototype.vercel.app/) &nbsp;·&nbsp; [📂 Code](https://github.com/akaltemamey/leedshack2026-prototype)

---

### 🥊 UFC Fight Predictor — *Full Microservices Ecosystem*

> A passion project that became a proper engineering challenge. Three decoupled services working in concert to bring ML-powered fight predictions and community analytics to MMA fans.

**How it fits together:**

```
Next.js Frontend  ──JWT──►  Spring Boot API  ──JPA──►  PostgreSQL
                                    │
                            ┌───────┴────────┐
                            ▼                ▼
                     FastAPI ML Service   Python Scraper
                     (Logistic Regression  (Playwright / live
                      on 6,000+ fights)    UFC data ingestion)
```

**What's inside each service:**

<details>
<summary><b>🌐 Web App</b> — Spring Boot + Next.js monorepo &nbsp;·&nbsp; <a href="https://github.com/Vali-Hameed/UFC-Fight-Predictor-Website">📂 Repo</a></summary>
<br>

- JWT auth with HttpOnly cookies, refresh token rotation, and BCrypt hashing
- Community predictions, discussion forums, and fight card polling
- Real-time leaderboards tracking accuracy, win streaks, and points
- Token-bucket rate limiting via Bucket4j to prevent abuse
- Admin dashboard for managing users, roles, and fights
- Fully containerised local dev stack via Docker Compose — no local Java or Node needed

`Java 17` `Spring Boot 3` `Spring Security` `Next.js 15` `TypeScript` `PostgreSQL` `Docker`
</details>

<details>
<summary><b>🤖 ML Service</b> — Containerised prediction API &nbsp;·&nbsp; <a href="https://github.com/Vali-Hameed/UFC-Fight-Predictor">📂 Repo</a></summary>
<br>

- Logistic regression model trained on 6,000+ historical bouts with Pandas preprocessing
- Served as a containerised FastAPI microservice
- Deployed to AWS ECS via Docker

`Python` `FastAPI` `Scikit-Learn` `Pandas` `Docker` `AWS ECS`
</details>

<details>
<summary><b>🕷️ Scraper Service</b> — Automated live data ingestion &nbsp;·&nbsp; <a href="https://github.com/Vali-Hameed/UFC-Scraper">📂 Repo</a></summary>
<br>

- Autonomous Python worker scraping live UFC fight cards, event data, and fighter stats
- Authenticated pushes to the core API via scraper key
- Built with Playwright for JS-rendered pages

`Python` `FastAPI` `Playwright` `Docker`
</details>

---

## `> git log --stat`

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=Vali-Hameed&theme=dark&hide_border=true&background=0d1117&stroke=30363d&ring=58a6ff&fire=58a6ff&currStreakLabel=ffffff&sideLabels=8b949e&dates=8b949e&sideNums=ffffff&currStreakNum=ffffff)](https://github.com/Vali-Hameed)

[![trophy](https://github-profile-trophy.vercel.app/?username=Vali-Hameed&theme=darkhub&no-frame=true&margin-w=8&rank=-C,-B)](https://github.com/ryo-ma/github-profile-trophy)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Vali-Hameed/Vali-Hameed/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Vali-Hameed/Vali-Hameed/output/github-contribution-grid-snake.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/Vali-Hameed/Vali-Hameed/output/github-contribution-grid-snake.svg" />
</picture>

</div>

---

## `> cat ./currently`

```json
{
  "building"  : "Picky Eater — full-stack web + mobile food platform",
  "studying"  : "Computer Science BSc @ Lancaster University (Year 2)",
  "exploring" : ["distributed systems", "ML serving", "system design"],
  "open_to"   : ["internships", "collaborations", "interesting problems"]
}
```

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1a2e,100:0d1117&height=80&section=footer" width="100%"/>

*If you're building something ambitious — [let's talk](https://www.vali-hameed.com/).*

</div>
