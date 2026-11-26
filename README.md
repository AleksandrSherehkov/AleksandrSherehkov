<!-- Aleksandr Shereshkov | Engineering portfolio -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&amp;color=0:0B1220,55:163653,100:075E63&amp;height=185&amp;section=header&amp;text=Aleksandr%20Shereshkov&amp;fontSize=42&amp;fontColor=F0F6FC&amp;fontAlignY=36&amp;desc=FULL-STACK%20SOFTWARE%20ENGINEER&amp;descSize=17&amp;descAlignY=57" alt="Aleksandr Shereshkov — Full-Stack Software Engineer" />
  <h3>Backend Architecture · Application Security · AI-Assisted Engineering</h3>
  <p>Building secure web applications, reliable APIs, and developer tools.<br/>Ukraine 🇺🇦 · Remote collaboration</p>
  <a href="https://www.linkedin.com/in/aleksandr-shereshkov/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&amp;logo=linkedin&amp;logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:aleksandr.shereshkov@gmail.com"><img src="https://img.shields.io/badge/Email-334155?style=for-the-badge&amp;logo=gmail&amp;logoColor=white" alt="Email" /></a>
  <a href="https://t.me/Alexander_Shereshkov"><img src="https://img.shields.io/badge/Telegram-167DA5?style=for-the-badge&amp;logo=telegram&amp;logoColor=white" alt="Telegram" /></a>
  <p><a href="#selected-projects">Projects</a> · <a href="#ai-assisted-engineering">AI workflow</a> · <a href="#technology-stack">Tech stack</a> · <a href="#github-activity">GitHub activity</a></p>
</div>

## About

I'm a **Full-Stack Software Engineer** with a strong backend and system-design focus. I work across the development lifecycle, from requirements and architecture to implementation, testing, deployment, and maintenance.

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>01 / Full-Stack Engineering</h3>
      Type-safe web applications, reusable interfaces, API integration, and predictable state management.
      <br/><br/><code>React</code> <code>Next.js</code> <code>TypeScript</code>
    </td>
    <td width="50%" valign="top">
      <h3>02 / Backend &amp; Architecture</h3>
      Modular services, REST APIs, relational data modeling, transactions, and system design.
      <br/><br/><code>NestJS</code> <code>Node.js</code> <code>PostgreSQL</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>03 / Application Security</h3>
      Authentication, authorization, server-side session lifecycle, and defense-in-depth controls.
      <br/><br/><code>JWT</code> <code>RBAC</code> <code>OWASP</code>
    </td>
    <td width="50%" valign="top">
      <h3>04 / AI-Assisted Engineering</h3>
      Agent-assisted development, specification-driven changes, automated verification, and LLM evaluation.
      <br/><br/><code>Codex</code> <code>Claude</code> <code>Local LLMs</code>
    </td>
  </tr>
</table>

> I use AI to accelerate engineering, not to outsource engineering judgment. Correctness, security, and maintainability remain the priorities.

## Selected projects

### 01 · Authentication & session management

[![Source code](https://img.shields.io/badge/View_source-mud--state--backend-0969DA?style=flat-square&logo=github&logoColor=white)](https://github.com/AleksandrSherehkov/mud-state-backend)

A modular backend exploring reusable, security-focused authentication and stateful session management on top of JWT.

- Server-side session validation and revocation; atomic refresh-token rotation and reuse detection.
- Role-based access control, CSRF defenses, account lockout, and request throttling.
- PostgreSQL constraints and indexes enforce session invariants beyond application-level checks.
- Threat-model documentation, structured security logging, and Redis-backed replay protection for M2M requests.

`NestJS` · `TypeScript` · `Prisma` · `PostgreSQL` · `Redis` · `JWT`

[Explore the architecture and security design →](https://github.com/AleksandrSherehkov/mud-state-backend#readme)

### 02 · AI-assisted localization & developer tooling

![Private project](https://img.shields.io/badge/Private_project-64748B?style=flat-square)

A domain-specific localization pipeline focused on consistent terminology, structured resource integrity, and reproducible processing.

- Terminology discovery, glossary management, and human-in-the-loop review.
- Checkpoint/resume, preflight validation, and controlled application of changes.
- Cross-platform test automation and comparative evaluation of local language models.

`TypeScript` · `CLI` · `LLMs` · `GitHub Actions` · `Automated Testing`

### 03 · Document generation & processing

![Engineering work](https://img.shields.io/badge/Engineering_work-64748B?style=flat-square)

Backend services that transform structured business data into HTML and PDF documents, with a focus on input validation, reliable processing, and maintainable integrations.

`Node.js` · `TypeScript` · `JSON` · `HTML` · `PDF`

[Browse public repositories →](https://github.com/AleksandrSherehkov?tab=repositories)

## AI-assisted engineering

<p align="center">
  <a href="https://openai.com/codex/"><img src="https://img.shields.io/badge/OpenAI_Codex-182C49?style=for-the-badge" alt="OpenAI Codex" /></a>
  <a href="https://claude.ai/"><img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge" alt="Anthropic Claude" /></a>
  <a href="https://chatgpt.com/"><img src="https://img.shields.io/badge/ChatGPT-0D665F?style=for-the-badge" alt="ChatGPT" /></a>
  <img src="https://img.shields.io/badge/Local_LLMs-475569?style=for-the-badge" alt="Local LLMs" />
</p>

My workflow combines AI coding agents with explicit technical specifications, scoped changes, human review, and automated verification.

```mermaid
flowchart LR
    A["Specify & design"] --> B["Agent-assisted code"]
    B --> C["Human review"]
    C --> D["Tests & CI"]
    D --> E["Delivery"]
    D -. Feedback .-> B
```

**Beyond coding assistance:** I evaluate Qwen, Gemma, and TranslateGemma on domain-specific translation tasks, checking output quality, terminology consistency, and resource-format preservation.

**Quality gates:** review diffs · verify behavior · test regressions · check security boundaries · protect sensitive data.

## Technology stack

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>Frontend &amp; UI</h3>
      <img height="40" src="https://skillicons.dev/icons?i=react,nextjs,ts,tailwind,redux&amp;perline=5" alt="React, Next.js, TypeScript, Tailwind CSS, Redux" />
      <p>React · Next.js · Tailwind CSS · Styled Components · Radix UI</p>
      <p><strong>State &amp; data:</strong> Redux Toolkit · RTK Query · TanStack Query · Zustand</p>
    </td>
    <td width="50%" valign="top">
      <h3>Backend &amp; APIs</h3>
      <img height="40" src="https://skillicons.dev/icons?i=nodejs,nestjs,express,prisma,js&amp;perline=5" alt="Node.js, NestJS, Express, Prisma, JavaScript" />
      <p>Node.js · NestJS · Express.js · REST APIs · TypeScript</p>
      <p><strong>Data access:</strong> Prisma · TypeORM · Mongoose</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Databases &amp; Storage</h3>
      <img height="40" src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis&amp;perline=4" alt="PostgreSQL, MySQL, MongoDB, Redis" />
      <p>PostgreSQL · MySQL · MariaDB · MongoDB · Redis</p>
      <p><strong>Core:</strong> SQL · relational modeling · constraints · transactions</p>
    </td>
    <td width="50%" valign="top">
      <h3>Infrastructure &amp; Delivery</h3>
      <img height="40" src="https://skillicons.dev/icons?i=docker,nginx,linux,git,githubactions&amp;perline=5" alt="Docker, Nginx, Linux, Git, GitHub Actions" />
      <p>Docker · Docker Compose · Nginx · Linux</p>
      <p><strong>Delivery:</strong> Git · GitHub Actions · CI/CD · Bash</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Testing &amp; Quality</h3>
      <img height="40" src="https://skillicons.dev/icons?i=jest,postman&amp;perline=2" alt="Jest, Postman" />
      <p>Jest · Supertest · ESLint · Prettier</p>
      <p><strong>Practices:</strong> integration testing · regression checks · code review</p>
    </td>
    <td width="50%" valign="top">
      <h3>Security &amp; Reliability</h3>
      <img src="https://img.shields.io/badge/JWT-334155?style=flat-square&amp;logo=jsonwebtokens&amp;logoColor=white" alt="JWT" />
      <img src="https://img.shields.io/badge/OWASP-334155?style=flat-square&amp;logo=owasp&amp;logoColor=white" alt="OWASP" />
      <img src="https://img.shields.io/badge/RBAC-334155?style=flat-square" alt="RBAC" />
      <p>Token rotation · session management · CSRF protection</p>
      <p><strong>Practices:</strong> rate limiting · replay protection · threat modeling</p>
    </td>
  </tr>
</table>

<details>
  <summary><b>Additional technologies &amp; tools</b></summary>
  <br/>
  <img height="40" src="https://skillicons.dev/icons?i=vue,html,css,sass,vercel,vscode&amp;perline=6" alt="Vue, HTML, CSS, Sass, Vercel, VS Code" />
  <p>Vue.js · React Native · HTML5 · CSS3 · Sass · Framer Motion · GSAP · Vercel · VS Code</p>
</details>

## GitHub activity

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=AleksandrSherehkov&amp;theme=github-dark-blue&amp;hide_border=true&amp;ring=58A6FF&amp;fire=2DD4BF&amp;currStreakLabel=58A6FF" />
    <img width="520" src="https://streak-stats.demolab.com?user=AleksandrSherehkov&amp;theme=default&amp;hide_border=true&amp;ring=0969DA&amp;fire=0D9488&amp;currStreakLabel=0969DA" alt="GitHub contribution streak" />
  </picture>
  <br/>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=AleksandrSherehkov&amp;hide_border=true&amp;area=true&amp;bg_color=0D1117&amp;color=C9D1D9&amp;line=58A6FF&amp;point=2DD4BF" />
    <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=AleksandrSherehkov&amp;hide_border=true&amp;area=true&amp;bg_color=FFFFFF&amp;color=24292F&amp;line=0969DA&amp;point=0D9488" alt="GitHub contribution activity graph" />
  </picture>
</div>

<details>
  <summary><b>Beyond engineering</b></summary>
  <br/>
  <a href="https://www.codewars.com/users/AleksandrSherehkov"><img src="https://www.codewars.com/users/AleksandrSherehkov/badges/large" alt="Codewars profile" /></a>
  <p>Outside software engineering, I enjoy feeder angling and carp fishing — patience, precision, and continuous learning apply there too.</p>
</details>

---

<div align="center">
  <strong>Good software is built with intention, verified with evidence, and improved continuously.</strong>
  <p><a href="https://www.linkedin.com/in/aleksandr-shereshkov/">LinkedIn</a> · <a href="mailto:aleksandr.shereshkov@gmail.com">Email</a> · <a href="https://t.me/Alexander_Shereshkov">Telegram</a></p>
</div>
