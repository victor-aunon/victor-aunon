<div align="right">
  <strong>🇪🇸 Español</strong> &nbsp;|&nbsp; <a href="./README.en.md">🇬🇧 English</a>
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

Soy desarrollador fullstack en **SNGULAR** con background en **ingeniería mecánica (PhD)**. Vengo del mundo de la investigación y la simulación numérica, pero hace ya años que mi día a día está en el desarrollo de software.

Me muevo sobre todo en tres terrenos:
* 🔬 **I+D y desarrollo con IA:** No me gusta programar a ciegas ni dejar que los modelos inventen. Paso bastante tiempo investigando flujos de **Spec-Driven Development (SDD)** y barandillas mecánicas para que los agentes de IA trabajen con contratos claros, tipado estricto y verificación real en vez de alucinaciones.
* 🛠️ **Cacharreo, hardware y maker:** Me gusta conectar cosas del mundo físico a la web. Si tiene Bluetooth, sensores o escupe datos en tiempo real, antes o después le acabo montando un puente, una API o un dashboard para verlo en pantalla.
* ⚡ **Automatización & Homelab:** Si tengo que hacer algo a mano más de un par de veces, me falta tiempo para automatizarlo. Me monto y mantengo mis propios servicios: desde una estación de inferencia local con una GPU Intel Arc Pro para correr modelos en casa, hasta un VPS con Dokploy para orquestar agentes, enrutar LLMs con LiteLLM y desplegar mis proyectos sin depender de plataformas cerradas.

---

### 🧪 Cosas en las que he estado trasteando

Una selección de proyectos personales y experimentos de laboratorio:

#### 🤖 IA Agéntica & Spec-Driven Development
* **[Speckit Vite+ Stitch Bundle](https://github.com/victor-aunon/speckit-viteplus-stitch-bundle)**  
  Un pipeline estricto de calidad para frontend que combina herramientas rápidas en Rust (Oxlint, Oxfmt), límites de complejidad, separación limpia entre capas y generación visual asistida con Google Stitch MCP.
* **[Gemini SDD Harness](https://github.com/victor-aunon/gemini-cli-harness) & [OpenCode Harness](https://github.com/victor-aunon/opencode-harness)**  
  Arneses para trabajar con agentes de IA bajo especificaciones previas (*Spec-Driven Development*). Añaden contratos, memoria persistente y validaciones en local para obligar al modelo a seguir planos antes de tocar código.
* **[CRIT Skill](https://github.com/victor-aunon/crit-skill)**  
  Implementación del método CRIT (Contexto → Rol → Entrevista → Tarea) como habilidad agéntica, para que los modelos hagan preguntas clave y se alineen con el usuario antes de lanzarse a responder.

---

#### ⚙️ Homelab, Infraestructura & Automatización
* **Estación de Inferencia Local & VPS (Dokploy + LiteLLM)**  
  Mi laboratorio personal para correr y orquestar modelos de IA sin depender exclusivamente de APIs externas. En local tengo una estación de inferencia equipada con una GPU **Intel Arc Pro B70** para servir modelos abiertos. En la nube mantengo un VPS orquestado con **Dokploy** donde despliego mis proyectos y corre **LiteLLM** como pasarela inteligente (enruta a mis modelos locales y salta con fallbacks a **OpenRouter** si necesito modelos mayores), además de automatizaciones autónomas con **Hermes Agent** y un montón de servicios autoalojados.
* **[Digital Life Manager (DLM)](https://github.com/victor-aunon/digital-life-manager)**  
  Monorepo en Turborepo para ingesta y gestión de archivos (desde ficheros grandes hasta documentos personales), con Next.js 16, worker en segundo plano en Python, base de datos vectorial (PostgreSQL + pgvector) y una extensión propia de Chrome en Manifest V3 para sincronizar sesiones.
* **[Expenses Manager](https://github.com/victor-aunon/expenses-manager)**  
  Monorepo multiplataforma para finanzas personales: API en NestJS, frontend web en Next.js 15 y app móvil con Expo / React Native, con pipeline para escanear tickets y facturas vía OCR.
* **[nvim.dots](https://github.com/victor-aunon/nvim.dots) & [n8n-docker-compose](https://github.com/victor-aunon/n8n-docker-compose)**  
  Mi entorno diario en terminal: Neovim ajustado al detalle en Lua, multiplexores (Zellij / Tmux), shell Fish y contenedores Docker con n8n para automatizar tareas rutinarias.

---

#### 🏃 Pasiones y Laboratorio
* **[Running Activity Support System](https://github.com/victor-aunon/running-activity-companion)**  
  Un invento que monté para mis entrenamientos y carreras de fondo: leo métricas a 1 Hz del Garmin Fenix 7S por BLE, las paso por una pasarela en Android (que además sincroniza música con Spotify), las emito por WebSockets y las pinto en directo en un dashboard web Bento Box en Next.js para que me sigan en carrera.
* **[Oanda Trading Bot](https://github.com/victor-aunon/Oanda-trading-bot)**  
  Bot en Python montado sobre Backtrader para probar estrategias cuantitativas de Forex y cripto contra la API de Oanda, con backtesting y control de riesgo automático.

---

### 💡 Cómo me gusta trabajar

* **Fundamentos antes que modas:** Los frameworks vienen y van. Saber diseñar con límites limpios, entender cómo funciona el navegador por dentro y apoyarse en buenos patrones ahorra mucho más tiempo que aprender el enésimo tutorial de turno.
* **La IA como copiloto, el humano como arquitecto:** La IA aporta una velocidad brutal creando código, pero el diseño, las decisiones arquitectónicas y los criterios de aceptación siguen siendo responsabilidad nuestra.
* **Sin atajos chapuceros:** Si algo cojea en el diseño o en los tipos, prefiero arreglar la raíz antes que meter un parche que nos explote a todos la semana que viene.

---

### 🧰 Caja de Herramientas

<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=ts,js,py,html,css,nextjs,react,tailwind,vite,nodejs,nestjs,postgres,docker,redis,vscode,neovim,git&theme=dark" alt="Tecnologías principales" />
  </a>
</p>

<details>
<summary><b>🛠️ Ver desglose detallado de herramientas y servicios</b></summary>

<br />

#### Infraestructura, Homelab & IA Gateway
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

#### IA Agéntica & Metodología
<p align="left">
  <img src="https://img.shields.io/badge/Spec--Driven%20Development%20(SDD)-4F46E5?style=flat-square" alt="SDD" />
  <img src="https://img.shields.io/badge/MCP%20(Model%20Context%20Protocol)-10B981?style=flat-square" alt="MCP" />
  <img src="https://img.shields.io/badge/Prompt%20Eng-F59E0B?style=flat-square" alt="CRIT" />
</p>

#### Entorno & Productividad de Terminal
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

### 📊 Actividad en GitHub

<p align="center">
  <img src="https://github-readme-stats-eight-theta.vercel.app/api?username=victor-aunon&show_icons=true&theme=catppuccin_mocha&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9" height="150" alt="GitHub Stats" />
  <img src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=victor-aunon&layout=compact&theme=catppuccin_mocha&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9" height="150" alt="Top Languages" />
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com/?user=victor-aunon&theme=catppuccin_mocha&hide_border=true&background=0D1117&ring=58A6FF&fire=58A6FF&currStreakNum=58A6FF" height="150" alt="Streak Stats" />
</p>

---

### 💬 ¿Hablamos?

Si te apetece charlar sobre arquitecturas de software, desarrollo asistido por IA o cualquier proyecto:

* 💼 Conéctate en [LinkedIn: Ángel Auñón](https://www.linkedin.com/in/angelaunon/)
* 🌐 Pásate por mi web: [victoraunon.com](https://victoraunon.com)
* 📬 Envíame un correo a: [hola@victoraunon.com](mailto:hola@victoraunon.com)
