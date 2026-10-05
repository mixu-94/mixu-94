<p align="center">
  <img src="assets/banner.svg" alt="MiXu — Michael Schindler · Full-stack · AI agents · Self-hosting" width="100%">
</p>

<h3 align="center">Hey, I'm MiXu ツ 👋</h3>
<p align="center"><sub>やると決めたら、やり抜く。 — once I decide, I build it.</sub></p>

<p align="center">
  <a href="https://michael-schindler.dev"><img src="https://img.shields.io/badge/michael--schindler.dev-6d5dfc?style=for-the-badge&logo=vercel&logoColor=white" alt="Website"></a>
  <a href="https://github.com/HAZRD-Network"><img src="https://img.shields.io/badge/HAZRD_Network-0b0d0b?style=for-the-badge&logo=github&logoColor=9acd32" alt="HAZRD Network"></a>
</p>

---

### 🧠 About me

I'm a state-certified IT technician who drifted from networks and Linux boxes into building web products — and then into letting AI agents help me build them.
Today I build full-stack apps in **TypeScript**, run my own servers, and spend an unreasonable amount of time making repetitive work disappear.

- 🛠️ **TypeScript everywhere** — Next.js on the front, Node.js on the back, Tailwind for everything in between
- 🧠 **AI agents are my daily driver** — agent workflows, MCP integrations and LLM-powered automation, in my own dev setup and in client work
- 🤖 If I do it twice, I script it. The third time it becomes a reusable workflow
- 🏠 Homelab & own servers — Coolify, Docker, monitoring, backups, the whole rabbit hole
- 🎮 I build platforms for game communities — dashboards, Discord bots, game-server bridges

---

### 🔭 Right now <sub><sup>· updated Oct 2026</sup></sub>

- ☢️ Running the **[HAZRD](https://github.com/HAZRD-Network/hazrd-platform)** *7 Days to Die* **Public Alpha** — player portal, live map, auctions, Discord-as-code
- 🌐 Shipped my site **[michael-schindler.dev](https://github.com/mixu-94/michael-schindler.dev)** — press <kbd>Ctrl</kbd>+<kbd>K</kbd> there, you'll see
- 🤖 Building out my AI agent workspace — agents with guardrails, a shared MCP gateway and task tracking they update themselves
- 🎯 Open for projects & partnerships — MVPs, AI automation, full-stack web

---

### 📌 Featured

<table>
  <tr>
    <td width="33%" valign="top">
      <h4>☢️ <a href="https://github.com/HAZRD-Network/hazrd-platform">HAZRD Platform</a></h4>
      Web & ops layer on top of dedicated survival game servers: player portal, live map, economy, monitoring.<br><br>
      <code>Next.js</code> <code>Node.js</code> <code>C#</code> <code>Discord.js</code>
    </td>
    <td width="33%" valign="top">
      <h4>🌌 <a href="https://github.com/mixu-94/michael-schindler.dev">michael-schindler.dev</a></h4>
      My personal site — portfolio, services, a terminal mode and a few easter eggs.<br><br>
      <code>Next.js 16</code> <code>React 19</code> <code>Tailwind 4</code>
    </td>
    <td width="33%" valign="top">
      <h4>⚙️ <a href="https://github.com/mixu-94/github-actions">github-actions</a></h4>
      My shared CI/CD toolbox: reusable workflows for CI, releases, security audits and dependency updates.<br><br>
      <code>GitHub Actions</code> <code>semantic-release</code> <code>zizmor</code>
    </td>
  </tr>
</table>

> Most of my work — client projects and my own products — lives in private repos. The repos above show what I build and how, without handing out the source.

---

### 🔥 Stories from the trenches

- **The live map that wasn't.** A "refresh tiles every N seconds" loop looked perfect in code and did *nothing* — the browser served identical URLs from memory cache, no request ever left. Fixed with ETag/304 and a tiny version endpoint instead of ~400 KB per tick per tab. → [read more](https://github.com/HAZRD-Network/hazrd-platform#-engineering-highlights)
- **Game updates are deployments.** Server mods patch game methods at runtime — one game update can crash the server on start. So updates go through a test realm first, never straight to live.
- **Discord as infrastructure.** Roles, channels and permissions come from one config file with *plan → apply*, like Terraform for a community.

---

### 🤖 How I work with AI

- **Agents get a contract, not a vibe.** Every workspace has an `AGENTS.md` that says where things live, what's off-limits and how to verify work
- **Guardrails over trust.** Production servers, live game state and secrets are protected — agents ask before anything irreversible
- **One gateway for tools.** A self-hosted MCP gateway gives every agent the same tools (Notion, n8n, docs, browser) without copying secrets around
- **Agents track their own work.** Tasks live in Notion; agents claim them, update them and link the result

---

### 🧰 Toolbox

| Area | Stack |
| --- | --- |
| 🏗️ **Build** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![Payload CMS](https://img.shields.io/badge/Payload_CMS-000?style=flat-square&logo=payloadcms&logoColor=white) |
| 🗄️ **Data & Infra** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Coolify](https://img.shields.io/badge/Coolify-6B16ED?style=flat-square&logo=coolify&logoColor=white) |
| 🤖 **Automation & AI** | ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white) ![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-000?style=flat-square&logo=modelcontextprotocol&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white) |

---

### 🗺️ How I got here

| When | What |
| --- | --- |
| **Foundation** | State-certified IT technician (*Staatlich geprüfter Techniker für Informatiktechnik*) — Linux, networks, C++, databases |
| **2022** | Full-stack bootcamp → React, Node.js, MongoDB, my first real web apps |
| **2022 – 2024** | Web3 rabbit hole — Cardano NFTs, an art engine and NFC-based verification for physical items |
| **2025 – now** | Client platforms, the HAZRD game network and AI agents everywhere |

---

### ⚙️ How I like to build

- **Understandable > clever.** Automation should save work, not become magic nobody dares to touch
- **Let the robots catch the boring bugs.** Types, lint, tests and CI before anything ships
- **Automate repetition, not judgement.** Patch updates auto — major upgrades get a human
- **Security is part of the job.** Pinned SHAs, minimal permissions, no secrets in repos. Ever.

---

<p align="center">
  <sub>MiXu is my long-time handle — Michael Schindler is the human behind it.<br>
  Wanna build something? → <a href="https://michael-schindler.dev">michael-schindler.dev</a></sub>
</p>
