<!-- ═══════════════════════════════════════════════════════════════════════════
     NITIN SINGH — GitHub Profile README
     Terminal-aesthetic, dark-only design. Hand-crafted, not templated.
     No capsule-render · No typing-svg · No badge walls · No stats card wall
     ═══════════════════════════════════════════════════════════════════════════ -->

<div align="center">
<img src="./assets/banner-dark.svg" alt="nitin@ai-lab:~ terminal banner" width="100%">
</div>

<br/>

> **Second-year B.Tech CSE student who builds production AI infrastructure — not wrappers, not demos.**
>
> I architect local-first AI systems in Rust where secrets stay in the OS keychain and models run on-device. I ship full-stack products in TypeScript and orchestrate multi-provider LLM pipelines across Ollama, OpenAI, Anthropic, Gemini, and OpenRouter. Six products shipped solo end to end — from system architecture to deployment. Published on npm. Three professional certifications (OCI DevOps, OCI Developer, CEH).

```
🎯 Currently seeking: a remote, part-time AI Engineering / Generative AI internship
   where I can contribute to production AI systems.
```

<br/>

<img src="./assets/divider.svg" width="100%" alt=""/>

## `> cat flagship.md`

<table>
<tr>
<td width="100%">

### ⚡ [Nitin-AI](https://github.com/nitinsingh2006/Nitin-AI) &nbsp; <a href="https://www.npmjs.com/package/nitin-ai"><kbd>npm</kbd></a> &nbsp; <sub>Apache-2.0</sub>

**Open-source, local-first AI workstation** — your models, your data, your machine.

Most AI tools lock you into cloud APIs and send your data to third-party servers. Nitin-AI is built on a different premise: a **Rust/Tauri trusted core** that keeps secrets in the OS keychain, persists everything to local SQLite, and gives you a **provider registry** that hot-swaps between Ollama, OpenAI, Anthropic, Gemini, and OpenRouter — simultaneously. A sandboxed agent runtime handles autonomous task execution with safety boundaries, all behind a fast React desktop UI.

> **Why this matters:** Provider independence is the biggest operational risk in AI engineering today. Nitin-AI solves it at the infrastructure layer.

```
┌─────────────────┬───────────────────────────────────────────────────────────┬──────────────────────────────────────┐
│ Layer           │ What it does                                            │ Tech                                 │
├─────────────────┼───────────────────────────────────────────────────────────┼──────────────────────────────────────┤
│ Trusted Core    │ OS-level secret management, native process control      │ Rust, Tauri                          │
│ Persistence     │ Conversations, config, provider state — all local       │ SQLite                               │
│ Provider Reg.   │ Hot-swap 5+ local/cloud model providers via unified API │ Ollama, OpenAI, Anthropic, Gemini    │
│ Agent Runtime   │ Autonomous task execution with safety boundaries        │ Sandboxed environment                │
│ Desktop UI      │ Real-time streaming, multi-conversation management      │ React                                │
└─────────────────┴───────────────────────────────────────────────────────────┴──────────────────────────────────────┘
```

</td>
</tr>
</table>

<img src="./assets/divider.svg" width="100%" alt=""/>

## `> ls ~/shipped/`

<table>
<tr>
<td width="50%" valign="top">

### [CodeQuest AI](https://codequest-ai-one.vercel.app) &nbsp; <a href="https://github.com/nitinsingh2006/codequest-ai"><kbd>src</kbd></a>

**Zero-cost, zero-risk coding education.** Gamified platform with quests, leaderboard, and **in-browser Python execution via Pyodide** — no server-side code execution means no infrastructure cost and no security surface. A local Ollama mentor provides AI tutoring without ever hitting a cloud API.

> _Server-side code execution is the #1 cost and security problem in edtech platforms. CodeQuest eliminates both by running Python entirely in the browser via WebAssembly._

`Next.js` `Prisma` `PostgreSQL` `Ollama` `Pyodide` `Docker`

</td>
<td width="50%" valign="top">

### [Invo](https://github.com/nitinsingh2006/invo)

**GST-compliant invoicing for Indian freelancers, without enterprise pricing.** AI-assisted invoicing SaaS with Clerk authentication, Razorpay payment links, PDF generation, and Gemini-powered payment reminders that actually chase your clients.

`Next.js` `Prisma` `Clerk` `Razorpay` `Gemini`

<br/>

### [PortfolioSathi](https://github.com/nitinsingh2006/portfoliosathi)

**Portfolio generation from your existing data.** Feed it a GitHub username and a LinkedIn PDF export — it parses both sources server-side and generates an animated, data-driven portfolio site.

`Next.js` `GitHub REST API` `pdf-parse` `Three.js`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [ResumeForge](https://github.com/nitinsingh2006/resume-forge)

**ATS-optimized resume builder with real testing infrastructure.** Live preview, multiple templates, PDF/DOCX/JSON export — tested with Vitest and Playwright, Dockerized, auth-ready. Built to the standard of production software, not a weekend hack.

`Next.js` `Prisma` `Docker` `Vitest` `Playwright`

</td>
<td width="50%" valign="top">

### [Lead Gen Automation](https://github.com/nitinsingh2006/lead-gen-automation)

**Automated outreach pipeline.** Finds local businesses via Apify, generates custom demo websites with Gemini, deploys to GitHub Pages, and runs email outreach — fully automated, end to end.

`Python` `Apify` `Gemini` `GitHub Pages` `SMTP`

</td>
</tr>
</table>

<details>
<summary><kbd>more projects →</kbd></summary>
<br/>

**[nitin-free-claude-code](https://github.com/nitinsingh2006/nitin-free-claude-code)** — Python/FastAPI proxy tooling for Claude Code and Codex with provider routing and admin UI

**[GitHub Roaster](https://github.com/nitinsingh2006/github-roaster)** — Analyzes GitHub profiles and generates multilingual AI roasts via Groq-compatible chat API

**[nitin-ai (npm)](https://www.npmjs.com/package/nitin-ai)** — Autonomous AI developer agent for terminal workflows, BYO API key

</details>

<img src="./assets/divider.svg" width="100%" alt=""/>

## `> neofetch --stack`

```
nitin@ai-lab
─────────────────────────────────────────────
AI & LLM Infra    : Ollama · OpenAI · Anthropic · Gemini · OpenRouter · Groq
Systems & Desktop  : Rust · Tauri · SQLite
Full-Stack         : TypeScript · Python · Next.js · React · FastAPI · Node.js · Prisma · PostgreSQL
DevOps & Quality   : Docker · OCI · GitHub Actions · Vitest · Playwright · Vercel
```

<img src="./assets/divider.svg" width="100%" alt=""/>

## `> cat /etc/credentials`

```
┌──────────────────────────────────────┬─────────────────────────────────────┐
│ Certification                        │ Issuer                              │
├──────────────────────────────────────┼─────────────────────────────────────┤
│ OCI DevOps Professional              │ Oracle Cloud Infrastructure         │
│ OCI Developer Professional           │ Oracle Cloud Infrastructure         │
│ Certified Ethical Hacker (CEH)       │ EC-Council                          │
└──────────────────────────────────────┴─────────────────────────────────────┘
```

🎓 &nbsp;B.Tech CSE — **Indore Institute of Science & Technology** (RGPV University) · Class of 2028
<br/>
🏆 &nbsp;**Smart India Hackathon** (Mini SIH 2025) participant — built with Claude Code + Opus

<img src="./assets/divider.svg" width="100%" alt=""/>

## `> git log --oneline -1`

<div align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=nitinsingh2006&show_icons=true&include_all_commits=true&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9&icon_color=3FB950&ring_color=58A6FF" alt="GitHub Stats"/>
  <img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=nitinsingh2006&hide_border=true&background=0D1117&ring=58A6FF&fire=F78166&currStreakLabel=58A6FF&sideLabels=C9D1D9&dates=8B949E&currStreakNum=C9D1D9&sideNums=C9D1D9" alt="Streak Stats"/>
</div>

<br/>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=nitinsingh2006&bg_color=0D1117&color=58A6FF&line=3FB950&point=C9D1D9&area_color=58A6FF&area=true&hide_border=true&custom_title=contribution%20frequency" alt="Contribution Graph" width="97%"/>
</div>

<img src="./assets/divider.svg" width="100%" alt=""/>

<div align="center">

### `> echo "Let's build something together"`

I'm looking for a **remote, part-time AI engineering internship** where I can contribute to production AI systems.<br/>
I bring Rust + TypeScript + Python fluency, multi-provider LLM integration experience,<br/>
and the ability to ship end-to-end — solo.

<br/>

<a href="https://linkedin.com/in/nitinsingh2006"><kbd> 💬 Message me on LinkedIn </kbd></a>&nbsp;&nbsp;
<a href="https://nitin-portfolio-orpin.vercel.app"><kbd> 🌐 View Full Portfolio </kbd></a>

</div>

<br/>

<div align="center">
<img src="./assets/footer.svg" width="100%" alt=""/>
</div>
