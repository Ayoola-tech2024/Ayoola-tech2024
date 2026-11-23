<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=auto&height=240&section=header&text=Ayoola%20Damisile&fontSize=60&fontAlignY=32&desc=Solutions%20Architect%20%26%20Cloud%20Systems%20Engineer&descAlignY=52&animation=fadeIn&fontColor=fff">
    <img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=240&section=header&text=Ayoola%20Damisile&fontSize=60&fontAlignY=32&desc=Solutions%20Architect%20%26%20Cloud%20Systems%20Engineer&descAlignY=52&animation=fadeIn" width="100%"/>
  </picture>
</div>

<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=800&color=4285F4&center=true&vCenter=true&width=750&lines=Solutions+Architect+%26+Cloud+Systems+Engineer;BIT+Scholar+%40+FUTA;Sole+Software+Engineer+of+buysolar.ng+%26+lightsupenergy.com;Author+of+fixmcp+%26+%40damisile_ayoola%2Fenvvault;Building+Resilient+Cloud+%26+AI+Systems" alt="Typing SVG" />
  </a>
</div>

<div align="center">
  <a href="https://www.google.com/search?kgmid=/g/11ynvpcp11"><img src="https://img.shields.io/badge/Google_Knowledge_Graph-%2Fg%2F11ynvpcp11-4285F4?style=flat-square&logo=google&logoColor=white" alt="Google Knowledge Graph" /></a>
  <a href="https://www.wikidata.org/wiki/Q141703795"><img src="https://img.shields.io/badge/Wikidata-Q141703795-339966?style=flat-square&logo=wikidata&logoColor=white" alt="Wikidata" /></a>
  <a href="https://www.credly.com/"><img src="https://img.shields.io/badge/IBM_Cybersecurity_Analyst-Verified-052FAD?style=flat-square&logo=ibm&logoColor=white" alt="IBM Cybersecurity Analyst" /></a>
  <a href="https://loop.frontiersin.org/people/3228692/overview"><img src="https://img.shields.io/badge/Frontiers_Loop-%233228692-00A651?style=flat-square" alt="Frontiers Loop" /></a>
  <a href="https://www.npmjs.com/~damisile_ayoola"><img src="https://img.shields.io/badge/npm-Packages-CB3837?style=flat-square&logo=npm&logoColor=white" alt="npm" /></a>
  <a href="https://github.com/Ayoola-tech2024?tab=followers"><img src="https://img.shields.io/github/followers/Ayoola-tech2024?style=flat-square&logo=github&color=181717" alt="Followers"/></a>
  <a href="https://www.linkedin.com/in/damisile-ayoola-096a7b382"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://x.com/damisiledev"><img src="https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white" alt="X"/></a>
  <a href="https://damisile.name.ng"><img src="https://img.shields.io/badge/Portfolio-4285F4?style=flat-square&logo=Google-Chrome&logoColor=white" alt="Portfolio"/></a>
</div>

<br/>

---

### 🏛️ Core Architecture Overview

```mermaid
flowchart LR
    A[Client Traffic & Edge] --> B[Edge API Gateway<br/>Rate Limiting & HMAC Auth]
    B --> C{Core Routing}
    C -->|FinTech & Payments| D[PostgreSQL RLS<br/>Idempotent Ledger]
    C -->|AI & Inference| E[Dual Gemini 2.5 Flash<br/>Vertex AI Failover]
    C -->|Edge Biometrics| F[MediaPipe WebAssembly<br/>468 3D Face Landmarks]
```

---

### 🚀 Anchor Production Systems

#### 1. [BuySolar.ng](https://buysolar.ng) — Resilient FinTech Edge Architecture & Dual Gemini Quoting
> **Role:** Sole Founding Software Engineer (Built from scratch) · CAC: 8168912
* **Distributed Edge:** 682 edge routes engineered with Next.js and optimized for high-volume transactions.
* **Cryptographic Reconciliation:** Enforces raw-body Paystack HMAC SHA-512 webhook signature verification with cryptographic idempotency nonces, eliminating double-allocation race conditions during payment bursts.
* **Multimodal Solar AI Engine:** Dual Gemini 2.5 Flash pipeline with circuit-breaker failover (<800ms latency), translating rooftop imagery and appliance loads into production solar equipment quotes.
* **Corporate Platform:** Engineered corporate energy portal at [lightsupenergy.com](https://lightsupenergy.com).

#### 2. [checkIn](https://github.com/Ayoola-tech2024/checkIn) — Campus Facial Geometry & Offline Geofence Engine
> **Role:** Lead Systems Architect · Deployed at FUTA SLIT
* **Edge Geometry Matching:** Real-time 468-point 3D facial landmark geometry extracted with Google MediaPipe WebAssembly.
* **Client-Side Verification:** Geometric Euclidean landmark comparisons run strictly client-side; zero face images or templates stored on servers (GDPR/NDPR compliant).
* **Offline Resilience:** Haversine spatial geofencing combined with an idempotent IndexedDB transactional drain queue, ensuring zero attendance loss during campus connectivity dropouts.

#### 3. [fixmcp](https://github.com/Ayoola-tech2024/fixmcp) — Model Context Protocol Doctor & Diagnostic Stdio Server
> **Published on npm:** `npx fixmcp` · [npm link](https://www.npmjs.com/package/fixmcp)
* **Dual-Mode Architecture:** Operates both as a CLI doctor (`npx fixmcp`) and a standard MCP stdio server (`fixmcp serve`), exposing 4 diagnostic tools (`diagnose_mcp_configs`, `test_mcp_server`, `repair_mcp_configs`, `list_agent_config_paths`).
* **Real stdio JSON-RPC Handshakes:** Tests live MCP server processes with JSON-RPC 2.0 `initialize` and `tools/list` handshakes across Claude Code, Claude Desktop, Cursor, VS Code, opencode, and Codex. 24 passing automated tests.

#### 4. [@damisile_ayoola/envvault](https://github.com/Ayoola-tech2024/envvault) — Zero-Disk Runtime Secrets Manager
> **Published on npm:** `npm install -g @damisile_ayoola/envvault` · [npm link](https://www.npmjs.com/package/@damisile_ayoola/envvault)
* **Cryptographic Memory Injection:** Injects decrypted environment variables directly into process memory (`process.env`) via `envvault run`, preventing plaintext `.env` disk leaks.
* **High-Stretching KDF & Integrity:** 100,000 PBKDF2 SHA-512 iterations with 32-byte salt, AES-256-GCM authenticated encryption, and an 18-test tamper detection suite.

---

### 🌐 Standards & Open Source Contributions

* **W3C Web Machine Learning Spec**:
  * Author of Issue [#288](https://github.com/webmachinelearning/web-nn/issues/288) discovering user-activation approval loop bypasses when AI agents automate the DOM; cited directly by specification editors in Issue #365.
* **InsForge (YC W24)**:
  * PR [#1965](https://github.com/InsForge/InsForge/pull/1965): Authored Paystack payment provider integration for West African developers (15 green CI suites, clean merge state).
  * Security Code Reviews: Audited PR [#2218](https://github.com/InsForge/InsForge/pull/2218) (PostgreSQL DDL event triggers for Row Level Security) and PR [#2219](https://github.com/InsForge/InsForge/pull/2219) (SMTP host SSRF prevention & DNS rebinding mitigations).
* **Published npm Packages**:
  * [`fixmcp`](https://github.com/Ayoola-tech2024/fixmcp) (v0.2.0): Cross-agent MCP configuration doctor & stdio diagnostic server (24 passing unit tests).
  * [`@damisile_ayoola/envvault`](https://github.com/Ayoola-tech2024/envvault): Zero-dependency AES-256-GCM runtime secrets manager (18 passing unit tests).

---

### 🛠️ Systems & Cloud Stack

* **Cloud & Infrastructure:** Google Cloud Platform (Cloud Run, Cloud SQL, VPC, Vertex AI), Docker, Coolify, Traefik, Nginx.
* **Languages & Runtimes:** TypeScript, JavaScript (Node.js/Bun), Python, SQL (PostgreSQL, SQLite), Bash.
* **Security & Reliability:** AES-256-GCM, HMAC SHA-512, PBKDF2, Zero-Trust Architecture, Row-Level Security (RLS).
* **Architecture:** Idempotent transaction queues, Circuit breakers, WebAssembly, Multi-agent workflows.

---

### 📬 Connect & Verified Footprint

- 🌐 **Portfolio & Case Studies:** [damisile.name.ng](https://www.damisile.name.ng)
- 💼 **LinkedIn:** [linkedin.com/in/damisile-ayoola-096a7b382](https://www.linkedin.com/in/damisile-ayoola-096a7b382)
- 🐦 **X (Twitter):** [@damisiledev](https://x.com/damisiledev)
- 📧 **Email:** [damisileayoola@gmail.com](mailto:damisileayoola@gmail.com)
