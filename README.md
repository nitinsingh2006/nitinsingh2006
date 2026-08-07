<!-- ═══════════════════════════════════════════════════════════════════════════
     NITIN SINGH — GitHub Profile README
     Designed as a hiring asset for AI Engineering / GenAI internships.
     Hand-crafted SVG banners, dark/light mode aware, recruiter-optimized.
     ═══════════════════════════════════════════════════════════════════════════ -->

<div align="center">

<!-- Hand-crafted SVG banner — dark/light mode adaptive via <picture> -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/banner-light.svg">
  <img alt="Nitin Singh — AI Systems Engineer" src="./assets/banner-dark.svg" width="100%">
</picture>

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&width=720&lines=Building+AI+systems+that+run+on+your+machine%2C+not+someone+else's+server;Rust+core+%C2%B7+TypeScript+products+%C2%B7+Python+pipelines+%C2%B7+Multi-provider+LLM+orchestration;6+products+shipped+solo+%C2%B7+3+professional+certifications+%C2%B7+Published+on+npm;Open+to+remote+AI+engineering+internships+%E2%86%92)](https://git.io/typing-svg)

<p>
  <a href="https://nitin-portfolio-orpin.vercel.app"><img src="https://img.shields.io/badge/Portfolio-0F172A?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/></a>&nbsp;
  <a href="https://linkedin.com/in/nitinsingh2006"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>&nbsp;
  <a href="https://www.npmjs.com/package/nitin-ai"><img src="https://img.shields.io/badge/npm_package-CB3837?style=for-the-badge&logo=npm&logoColor=white" alt="npm"/></a>
</p>

</div>

---

**Second-year B.Tech CSE student who builds production AI infrastructure — not wrappers, not demos.**

I architect local-first AI systems in Rust where secrets stay in the OS keychain and models run on-device. I ship full-stack products in TypeScript and orchestrate multi-provider LLM pipelines across Ollama, OpenAI, Anthropic, Gemini, and OpenRouter. Six products shipped solo end to end — from system architecture to deployment. Published on npm. Three professional certifications (OCI DevOps, OCI Developer, CEH).

**🎯 Currently seeking:** a remote, part-time **AI Engineering / Generative AI internship** where I can contribute to production AI systems.

---

## ⚡ Flagship: Nitin-AI

> **Open-source, local-first AI workstation** — your models, your data, your machine.

Most AI tools lock you into cloud APIs and send your data to third-party servers. Nitin-AI is built on a different premise: a **Rust/Tauri trusted core** that keeps secrets in the OS keychain, persists everything to local SQLite, and gives you a **provider registry** that hot-swaps between Ollama, OpenAI, Anthropic, Gemini, and OpenRouter — simultaneously. A sandboxed agent runtime handles autonomous task execution with safety boundaries, all behind a fast React desktop UI.

**Why this matters:** Provider independence is the biggest operational risk in AI engineering today. Nitin-AI solves it at the infrastructure layer.

| Layer | What it does | Tech |
|:--|:--|:--|
| **Trusted Core** | OS-level secret management, native process control, memory safety | Rust, Tauri |
| **Persistence** | Conversations, config, provider state — all local, no cloud dependency | SQLite |
| **Provider Registry** | Hot-swap between 5+ local/cloud model providers via unified API | Ollama, OpenAI, Anthropic, Gemini, OpenRouter |
| **Agent Runtime** | Autonomous task execution with safety boundaries and sandboxing | Sandboxed environment |
| **Desktop UI** | Real-time streaming, multi-conversation management | React |

<p>
  <a href="https://github.com/nitinsingh2006/Nitin-AI"><img src="https://img.shields.io/badge/Repository-0F172A?style=for-the-badge&logo=github&logoColor=white" alt="Repo"/></a>&nbsp;
  <a href="https://www.npmjs.com/package/nitin-ai"><img src="https://img.shields.io/badge/nitin--ai_on_npm-CB3837?style=for-the-badge&logo=npm&logoColor=white" alt="npm"/></a>&nbsp;
  <img src="https://img.shields.io/badge/License-Apache_2.0-38BDF8?style=for-the-badge" alt="License"/>
</p>

---

## 🚀 What I've Shipped

### [CodeQuest AI](https://codequest-ai-one.vercel.app) &nbsp; <a href="https://github.com/nitinsingh2006/codequest-ai"><img src="https://img.shields.io/badge/code-0F172A?style=flat-square&logo=github&logoColor=white" alt="code"/></a>

**Zero-cost, zero-risk coding education.** Gamified platform with quests, leaderboard, and **in-browser Python execution via Pyodide** — no server-side code execution means no infrastructure cost and no security surface. A local Ollama mentor provides AI tutoring without ever hitting a cloud API.

> _Technical selling point:_ Server-side code execution is the #1 cost and security problem in edtech platforms. CodeQuest eliminates both by running Python entirely in the browser via WebAssembly.

`Next.js` `Prisma` `PostgreSQL` `Ollama` `Pyodide` `Docker`

### [Invo](https://github.com/nitinsingh2006/invo)

**GST-compliant invoicing for Indian freelancers, without enterprise pricing.** AI-assisted invoicing SaaS with Clerk authentication, Razorpay payment links, PDF generation, and Gemini-powered payment reminders that actually chase your clients.

`Next.js` `Prisma` `Clerk` `Razorpay` `Gemini`

### [PortfolioSathi](https://github.com/nitinsingh2006/portfoliosathi)

**Portfolio generation from your existing data.** Feed it a GitHub username and a LinkedIn PDF export — it parses both sources server-side and generates an animated, data-driven portfolio site. No manual data entry beyond what you already have.

`Next.js` `GitHub REST API` `pdf-parse` `Three.js`

### [ResumeForge](https://github.com/nitinsingh2006/resume-forge)

**ATS-optimized resume builder with real testing infrastructure.** Live preview, multiple templates, PDF/DOCX/JSON export — tested with Vitest and Playwright, Dockerized, auth-ready. Built to the standard of production software, not a weekend hack.

`Next.js` `Prisma` `Docker` `Vitest` `Playwright`

### [Lead Gen Automation](https://github.com/nitinsingh2006/lead-gen-automation)

**Automated outreach pipeline.** Finds local businesses via Apify, generates custom demo websites with Gemini, deploys to GitHub Pages, and runs email outreach — fully automated, end to end.

`Python` `Apify` `Gemini` `GitHub Pages` `SMTP`

<details>
<summary><b>More projects →</b></summary>
<br/>

**[nitin-free-claude-code](https://github.com/nitinsingh2006/nitin-free-claude-code)** — Python/FastAPI proxy tooling for Claude Code and Codex with provider routing and admin UI

**[GitHub Roaster](https://github.com/nitinsingh2006/github-roaster)** — Analyzes GitHub profiles and generates multilingual AI roasts via Groq-compatible chat API

**[nitin-ai (npm)](https://www.npmjs.com/package/nitin-ai)** — Autonomous AI developer agent for terminal workflows, BYO API key

</details>

---

## 🧠 Stack

<table>
<tr>
<td valign="top" width="50%">

**AI & LLM Infrastructure**<br/>
<img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/Anthropic-D97757?style=flat-square&logoColor=white"/>
<img src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenRouter-000000?style=flat-square&logoColor=white"/>
<img src="https://img.shields.io/badge/Groq-F55036?style=flat-square&logoColor=white"/>
<br/><br/>
**Systems & Desktop**<br/>
<img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white"/>
<img src="https://img.shields.io/badge/Tauri-24C8D8?style=flat-square&logo=tauri&logoColor=white"/>
<img src="https://img.shields.io/badge/SQLite-07405E?style=flat-square&logo=sqlite&logoColor=white"/>

</td>
<td valign="top" width="50%">

**Full-Stack**<br/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
<br/><br/>
**DevOps & Quality**<br/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/OCI-F80000?style=flat-square&logo=oracle&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
<img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white"/>
<img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white"/>
<img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white"/>

</td>
</tr>
</table>

---

## 🏅 Credentials

<table>
<tr>
<td align="center" width="33%">
<img src="https://img.shields.io/badge/OCI_DevOps_Professional-F80000?style=flat-square&logo=oracle&logoColor=white"/><br/>
<sub>Oracle Cloud Infrastructure</sub>
</td>
<td align="center" width="33%">
<img src="https://img.shields.io/badge/OCI_Developer_Professional-F80000?style=flat-square&logo=oracle&logoColor=white"/><br/>
<sub>Oracle Cloud Infrastructure</sub>
</td>
<td align="center" width="33%">
<img src="https://img.shields.io/badge/Certified_Ethical_Hacker_(CEH)-1BA098?style=flat-square&logoColor=white"/><br/>
<sub>EC-Council</sub>
</td>
</tr>
</table>

🎓 &nbsp;B.Tech CSE — **Indore Institute of Science & Technology** (RGPV University) · Class of 2028
<br/>
🏆 &nbsp;**Smart India Hackathon** (Mini SIH 2025) participant — built with Claude Code + Opus

---

## 📊 GitHub

<div align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=nitinsingh2006&show_icons=true&include_all_commits=true&hide_border=true&bg_color=0F172A&title_color=38BDF8&text_color=CBD5E1&icon_color=38BDF8" alt="GitHub Stats"/>
  <img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=nitinsingh2006&hide_border=true&background=0F172A&ring=38BDF8&fire=38BDF8&currStreakLabel=38BDF8&sideLabels=CBD5E1&dates=94A3B8&currStreakNum=FFFFFF&sideNums=CBD5E1" alt="Streak Stats"/>
</div>

<br/>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/nitinsingh2006/nitinsingh2006/output/github-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/nitinsingh2006/nitinsingh2006/output/github-snake.svg">
    <img alt="Contribution Snake" src="https://raw.githubusercontent.com/nitinsingh2006/nitinsingh2006/output/github-snake-dark.svg" width="100%"/>
  </picture>
</div>

---

<div align="center">

### Let's build something together

I'm looking for a **remote, part-time AI engineering internship** where I can contribute to production AI systems.<br/>
I bring Rust + TypeScript + Python fluency, multi-provider LLM integration experience,<br/>
and the ability to ship end-to-end — solo.

<br/>

<a href="https://linkedin.com/in/nitinsingh2006"><img src="https://img.shields.io/badge/Message_me_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>&nbsp;
<a href="https://nitin-portfolio-orpin.vercel.app"><img src="https://img.shields.io/badge/View_Full_Portfolio-0F172A?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/></a>

</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1E293B,100:0F172A&height=80&section=footer" width="100%"/>
