<div align="right">
  <a href="./README.md">🇪🇸 Español</a> &nbsp;|&nbsp; <strong>🇬🇧 English</strong>
</div>

<p align="center">
  <img src="./assets/header.svg" width="100%" alt="Víctor Auñón" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/angelaunon/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://victoraunon.com"><img src="https://img.shields.io/badge/Web-victoraunon.com-111111?style=flat-square&logo=safari&logoColor=white" alt="Website" /></a>
  <a href="mailto:hola@victoraunon.com"><img src="https://img.shields.io/badge/Email-hola%40victoraunon.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Location-Valencia%2C%20Spain-orange?style=flat-square&logo=google-maps&logoColor=white" alt="Location" />
  <img src="https://img.shields.io/badge/Role-Senior%20Software%20Developer%20%40%20SNGULAR-blue?style=flat-square" alt="Role" />
</p>

I am a fullstack developer at **SNGULAR** with a background in **mechanical engineering (PhD)**. I come from academic research and fluid numerical simulation, but for years my daily craft has been building real-world software.

I mostly operate across three playing fields:
* 🔬 **R&D and AI-assisted engineering:** I don't believe in blind vibe-coding or letting LLMs invent stuff. I spend significant time researching **Spec-Driven Development (SDD)** workflows and mechanical guardrails so that AI agents work against strict contracts, solid typing, and deterministic validation instead of hallucinations.
* 🛠️ **Tinkering, hardware & maker spirit:** I love connecting the physical world to the web. If it runs Bluetooth, sensors, or streams real-time data, sooner or later I end up building a gateway, an API, or a dashboard to visualize it on screen.
* ⚡ **Automation & Homelab:** If I have to do something manually more than twice, I can't wait to automate it. I build and maintain my own stack: from a local inference workstation with an Intel Arc Pro GPU to run open models at home, to a cloud VPS powered by Dokploy to orchestrate autonomous agents, route LLMs through LiteLLM, and deploy personal projects without vendor lock-in.

---

### 🧪 Things I've been tinkering with

A curated selection of personal projects and lab experiments:

#### 🤖 1. Agentic AI & Spec-Driven Development
* **[Speckit Vite+ Stitch Bundle](https://github.com/victor-aunon/speckit-viteplus-stitch-bundle)**  
  A strict frontend quality pipeline combining fast Rust-powered tooling (Oxlint, Oxfmt), cyclomatic complexity limits, clean architectural boundaries, and AI-assisted visual design with Google Stitch MCP.
* **[Gemini SDD Harness](https://github.com/victor-aunon/gemini-cli-harness) & [OpenCode Harness](https://github.com/victor-aunon/opencode-harness)**  
  Quality harnesses for working with AI agents under specifications (*Spec-Driven Development*). They equip models with contracts, persistent memory, and local verification rails so they follow blueprinted specs before writing code.
* **[CRIT Skill](https://github.com/victor-aunon/crit-skill)**  
  An agent skill implementing the CRIT method (Context → Role → Interview → Task), prompting LLMs to ask key clarifying questions and align with requirements before jumping into code.

---

#### ⚙️ 2. Homelab, Infrastructure & Automation
* **Local Inference Rig & Cloud VPS (Dokploy + LiteLLM)**  
  My personal playground to run and orchestrate AI models without relying solely on third-party commercial APIs. Locally, I host an inference workstation with an **Intel Arc Pro B70** GPU serving open LLMs. In the cloud, I maintain a VPS managed via **Dokploy** hosting **LiteLLM** as an intelligent gateway (routing requests to local models with automatic fallbacks to **OpenRouter** for larger models), alongside autonomous workflows using **Hermes Agent** and self-hosted tools.
* **[Digital Life Manager (DLM)](https://github.com/victor-aunon/digital-life-manager)**  
  A Turborepo monorepo for file and document ingestion (from heavy assets to personal archives), featuring Next.js 16, a Python background worker, vector search with PostgreSQL + pgvector, and a custom Manifest V3 Chrome extension for automatic session synchronization.
* **[Expenses Manager](https://github.com/victor-aunon/expenses-manager)**  
  A cross-platform personal finance monorepo: NestJS REST API, Next.js 15 web app, and an Expo / React Native mobile app with OCR receipt scanning.
* **[nvim.dots](https://github.com/victor-aunon/nvim.dots) & [n8n-docker-compose](https://github.com/victor-aunon/n8n-docker-compose)**  
  My daily driver terminal workspace: finely tuned Neovim in Lua, terminal multiplexers (Zellij / Tmux), Fish shell, and self-hosted Docker containers with n8n for background automations.

---

#### 🏃 3. Passions & Laboratory
* **[Running Activity Support System](https://github.com/victor-aunon/running-activity-companion)**  
  A live telemetry system I built for long-distance training and races: collects live metrics at 1 Hz from a Garmin Fenix 7S via BLE, processes them through an Android companion gateway (with live Spotify integration), broadcasts via a WebSocket relay, and renders real-time stats on an interactive Next.js Bento Box dashboard for race spectators.
* **[Oanda Trading Bot](https://github.com/victor-aunon/Oanda-trading-bot)**  
  An algorithmic trading bot built in Python on top of Backtrader to backtest and execute quantitative forex and crypto strategies against the Oanda API with automated risk management.

---

### 💡 How I like to build

* **Foundations over fleeting trends:** Frameworks come and go. Designing with clear boundaries, understanding how browsers and runtimes actually work, and sticking to proven patterns saves exponentially more time than chasing the latest tutorial.
* **AI as the copilot, human as the architect:** AI provides extraordinary speed when writing code, but architecture, system design, and acceptance criteria remain firmly in human hands.
* **No cheap shortcuts:** If something feels fragile in the architecture or the type system, I'd rather address the root cause than patch over it with tech debt that explodes next week.

---

### 🧰 Toolbox

<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=ts,js,py,html,css,nextjs,react,tailwind,vite,nodejs,nestjs,postgres,docker,redis,vscode,neovim,git&theme=dark" alt="Core technologies" />
  </a>
</p>

<details>
<summary><b>🛠️ View detailed breakdown of tools, hardware & services</b></summary>

<br />

#### Infrastructure, Homelab & AI Gateway
<p align="left">
  <img src="https://img.shields.io/badge/Intel_Arc_Pro_B70-0071C5?style=flat-square&logo=intel&logoColor=white" alt="Intel Arc Pro B70" />
  <img src="https://img.shields.io/badge/Dokploy-000000?style=flat-square&logo=docker&logoColor=white" alt="Dokploy" />
  <img src="https://img.shields.io/badge/LiteLLM-1E1E2E?style=flat-square" alt="LiteLLM" />
  <img src="https://img.shields.io/badge/OpenRouter-6566F1?style=flat-square" alt="OpenRouter" />
  <img src="https://img.shields.io/badge/Hermes_Agent-10B981?style=flat-square" alt="Hermes Agent" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white" alt="pgvector" />
  <img src="https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white" alt="WebSockets" />
</p>

#### Agentic AI & Methodology
<p align="left">
  <img src="https://img.shields.io/badge/Spec--Driven%20Development%20(SDD)-4F46E5?style=flat-square" alt="SDD" />
  <img src="https://img.shields.io/badge/MCP%20(Model%20Context%20Protocol)-10B981?style=flat-square" alt="MCP" />
  <img src="https://img.shields.io/badge/Prompt%20Eng-F59E0B?style=flat-square" alt="CRIT" />
</p>

#### Terminal & Environment Productivity
<p align="left">
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white" alt="VS Code" />
  <img src="https://img.shields.io/badge/Neovim-57A143?style=flat-square&logo=neovim&logoColor=white" alt="Neovim" />
  <img src="https://img.shields.io/badge/OpenCode-2B3A4A?style=flat-square" alt="OpenCode" />
  <img src="https://img.shields.io/badge/Pi_Agent-7C3AED?style=flat-square" alt="Pi Agent" />
  <img src="https://img.shields.io/badge/Orca-0EA5E9?style=flat-square" alt="Orca" />
  <img src="https://img.shields.io/badge/Zellij%20%2F%20Tmux-FF5F00?style=flat-square" alt="Zellij / Tmux" />
  <img src="https://img.shields.io/badge/Turborepo-EF4444?style=flat-square&logo=turborepo&logoColor=white" alt="Turborepo" />
  <img src="https://img.shields.io/badge/Fish%20Shell-4E8088?style=flat-square&logo=gnubash&logoColor=white" alt="Fish" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white" alt="n8n" />
</p>

</details>

---

### 📊 GitHub Activity & Stats

<p align="center">
  <img src="https://github-readme-stats-eight-theta.vercel.app/api?username=victor-aunon&show_icons=true&theme=catppuccin_mocha&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9" height="150" alt="GitHub Stats" />
  <img src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=victor-aunon&layout=compact&theme=catppuccin_mocha&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9" height="150" alt="Top Languages" />
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com/?user=victor-aunon&theme=catppuccin_mocha&hide_border=true&background=0D1117&ring=58A6FF&fire=58A6FF&currStreakNum=58A6FF" height="150" alt="Streak Stats" />
</p>

---

### 💬 Let's Connect

If you'd like to talk software architecture, AI-assisted development, sports telemetry, or maker experiments:

* 💼 Connect on [LinkedIn: Ángel Auñón](https://www.linkedin.com/in/angelaunon/)
* 🌐 Check out my site: [victoraunon.com](https://victoraunon.com)
* 📬 Drop me an email at: [hola@victoraunon.com](mailto:hola@victoraunon.com)
