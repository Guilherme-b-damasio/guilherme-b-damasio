<p align="right">
  <b>🇺🇸 English</b> · <a href="README.pt-BR.md">🇧🇷 Português</a>
</p>

<h1 align="center">Guilherme Boeira Damasio</h1>
<h3 align="center">Backend Software Engineer · Node.js / TypeScript · PHP · AWS Serverless & Event-Driven Architecture</h3>

<p align="center">
  <a href="https://portfolio.devdek.online" target="_blank"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-111111?style=for-the-badge&logo=googlechrome&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/guilherme-boeira-damasio/" target="_blank"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge"/></a>
  <a href="mailto:tabletgbd@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://dev.to/guimk9" target="_blank"><img alt="Dev.to" src="https://img.shields.io/badge/Dev.to-0A0A0A?style=for-the-badge&logo=dev.to&logoColor=white"/></a>
  <a href="https://instagram.com/guiboeirad" target="_blank"><img alt="Instagram" src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/></a>
</p>

---

## About

Backend engineer based in Joinville 🇧🇷, working on systems that have to stay up and stay correct under load.

- 🚚 **Now:** APIs in **Node.js (Express, NestJS) with TypeScript** for a vehicle tracking and fleet management platform — an **event-driven pipeline on SQS/SNS that processes millions of tracker positions per day**, with async processing and resilient reprocessing. **AWS Lambda** for asynchronous workloads and integrations, **IoT devices** and third-party systems, and the services running on **Kubernetes (EKS/Rancher)** with their GitHub Actions deploy pipelines.
- 🧪 **Before:** ~2 years on **PHP** in a LIMS platform, implementing critical calculation routines with **DDD and Clean Architecture** and taking test coverage from **10% to 40%** with PHPUnit while refactoring legacy modules.
- 🤖 **Learning in public:** **applied AI** — LLM integrations, RAG and **MCP servers**. [docsage](https://github.com/Guilherme-b-damasio/docsage) is where that goes.

What I care about: clear boundaries, tests that mean something, observability before the incident, and code the next person can read.

---

## Featured: docsage

> **Ask questions about your own documents** — a RAG CLI and MCP server in Python, built with Claude.

[**docsage**](https://github.com/Guilherme-b-damasio/docsage) indexes Markdown, text, HTML, Word and PDF files (and web pages by URL), retrieves the most relevant passages and asks Claude for an answer that **cites its sources** — down to the heading path or the PDF page.

- **Retrieval you can tune:** BM25, local embeddings (sentence-transformers) or **hybrid** with reciprocal rank fusion, plus optional **re-ranking by Claude**
- **Measured, not guessed:** `docsage evaluate` reports recall@k on labeled queries; every result explains its score term by term
- **MCP server** (stdio and HTTP) so Claude Code and Claude Desktop can search your docs, with **MCP Apps** HTML reports showing highlighted citations
- Incremental indexing, prompt caching, token usage and cost per answer, English and Portuguese aware
- Clean Architecture (domain / application / infrastructure / interfaces), SOLID, **460+ tests**, CI with ruff and mypy, git flow

`Python` · `Claude API` · `MCP` · `BM25` · `sentence-transformers` · `pytest`

---

## Tech Stack

**Core**

<p>
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white"/>
  <img alt="NestJS" src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white"/>
  <img alt="Express" src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white"/>
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img alt="PHP" src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white"/>
  <img alt="Laravel" src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white"/>
  <img alt="Slim" src="https://img.shields.io/badge/Slim-6C78AF?style=for-the-badge"/>
</p>

**Cloud & Serverless**

<p>
  <img alt="AWS Lambda" src="https://img.shields.io/badge/AWS%20Lambda-FF9900?style=for-the-badge"/>
  <img alt="Amazon SQS" src="https://img.shields.io/badge/Amazon%20SQS-FF4F8B?style=for-the-badge"/>
  <img alt="Amazon SNS" src="https://img.shields.io/badge/Amazon%20SNS-FF4F8B?style=for-the-badge"/>
  <img alt="Amazon S3" src="https://img.shields.io/badge/Amazon%20S3-569A31?style=for-the-badge"/>
  <img alt="API Gateway" src="https://img.shields.io/badge/API%20Gateway-FF4F8B?style=for-the-badge"/>
  <img alt="Serverless" src="https://img.shields.io/badge/Serverless-FD5750?style=for-the-badge&logo=serverless&logoColor=white"/>
</p>

**Applied AI**

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img alt="Claude API" src="https://img.shields.io/badge/Claude%20API-D97757?style=for-the-badge&logo=anthropic&logoColor=white"/>
  <img alt="MCP" src="https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=modelcontextprotocol&logoColor=white"/>
  <img alt="RAG" src="https://img.shields.io/badge/RAG-4B5563?style=for-the-badge"/>
  <img alt="sentence-transformers" src="https://img.shields.io/badge/sentence--transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
</p>

**Databases**

<p>
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img alt="MySQL" src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>
  <img alt="Redis" src="https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white"/>
  <img alt="SQLite" src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white"/>
  <img alt="Prisma" src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white"/>
</p>

**DevOps & Infrastructure**

<p>
  <img alt="Kubernetes" src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
  <img alt="Jenkins" src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white"/>
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img alt="Bitbucket" src="https://img.shields.io/badge/Bitbucket-0052CC?style=for-the-badge&logo=bitbucket&logoColor=white"/>
  <img alt="NGINX" src="https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=white"/>
</p>

**Observability & Testing**

<p>
  <img alt="Sentry" src="https://img.shields.io/badge/Sentry-362D59?style=for-the-badge&logo=sentry&logoColor=white"/>
  <img alt="Jest" src="https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white"/>
  <img alt="pytest" src="https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white"/>
  <img alt="Cypress" src="https://img.shields.io/badge/Cypress-69D3A7?style=for-the-badge&logo=cypress&logoColor=black"/>
  <img alt="Selenium" src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white"/>
  <img alt="Postman" src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"/>
</p>

<details>
<summary><b>Also worked with</b></summary>
<br/>
<p>
  <img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
  <img alt="Spring Boot" src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"/>
  <img alt="Apache Kafka" src="https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white"/>
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
  <img alt="React" src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
  <img alt="Vue.js" src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white"/>
  <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/>
  <img alt="Expo" src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white"/>
</p>
</details>

**Architecture & practices**

`Event-Driven Architecture` · `Microservices` · `REST APIs` · `Clean Architecture` · `DDD` · `SOLID` · `TDD` · `Code Review` · `Scrum` · `Kanban` · `LLM Integration` · `RAG` · `MCP Servers`

---

## What I've Built

### DevDek — a collectible card game built on the Joinville tech scene

Devs sign in with GitHub and become a character card made of their own stats — languages as powers, activity, badges. Companies are checkpoints on a 3D map: get physically close to one and you earn its badge card. Two separate codebases, private for now — see it at [portfolio.devdek.online](https://portfolio.devdek.online).

| Project | What I did | Stack |
| --- | --- | --- |
| **DevDek — Backend** 🔒 | The API and the game rules: GitHub OAuth issuing JWTs, card generation rendered server-side to images, **real-time card battles over WebSockets**, geolocation check-ins against curated company checkpoints, community submissions with a moderation flow, and logo delivery through Cloudflare R2. Migrated persistence from Mongoose/MongoDB to **Prisma/PostgreSQL**. Battle rules are covered by simulation scripts that check invariants across thousands of generated duels. | `NestJS` · `TypeScript` · `Prisma` · `PostgreSQL` · `Socket.IO` · `Passport (GitHub OAuth, JWT)` · `Satori/resvg` · `Cloudflare R2` · `Docker` |
| **DevDek — Mobile** 🔒 | Android app on **Expo** with expo-router, consuming the same API as the web client. GitHub OAuth through a system browser tab with a `devdek://` deep link back (no embedded WebView — GitHub blocks OAuth there, and the user needs to see the address bar), secure token storage, card collection with filters, native MapLibre map, GPS check-ins, camera-based QR and 3D rendering with react-three-fiber. | `React Native` · `Expo` · `TypeScript` · `expo-router` · `MapLibre` · `react-three-fiber` · `expo-location` · `expo-secure-store` · `Socket.IO` |

### Open source

| Project | What it is | Stack |
| --- | --- | --- |
| [**docsage**](https://github.com/Guilherme-b-damasio/docsage) | RAG over your own documents: CLI and MCP server that index Markdown, HTML, Word, PDF and web pages, retrieve with BM25 / embeddings / hybrid search and answer with Claude, citing the sources. | `Python` · `Claude API` · `MCP` · `sentence-transformers` |
| [**Asaas Payment Gateway for Bagisto**](https://github.com/Guilherme-b-damasio/AsaasApiBagisto) | Two complementary packages integrating the Asaas gateway into Bagisto — PIX, boleto and credit card — exposing REST endpoints and handling payment webhooks (`PAYMENT_CONFIRMED`, `PAYMENT_RECEIVED`, `PAYMENT_REFUNDED`). | `PHP 8.1+` · `Laravel` · `Bagisto` · `REST API` · `Webhooks` |
| [**VulnUI**](https://github.com/Guilherme-b-damasio/vulnui) | Dashboard that orchestrates **OWASP ZAP** and **Nikto** scans from a single interface: spider crawling, active scanning, real-time progress and report history with risk categorization. | `Next.js 15` · `TypeScript` · `Tailwind CSS 4` · `Docker` |
| [**vuln.ai**](https://github.com/Guilherme-b-damasio/vuln.ai) | The scanning engine behind VulnUI — a Python orchestrator that drives the ZAP API and the Nikto CLI and consolidates the findings. | `Python` · `OWASP ZAP API` · `Nikto` |

---

## GitHub

<p align="center">
  <img alt="GitHub streak" src="https://streak-stats.demolab.com/?user=Guilherme-b-damasio&theme=tokyonight&hide_border=true&date_format=j%20M%5B%20Y%5D"/>
</p>

<p align="center">
  <img alt="Followers" src="https://img.shields.io/github/followers/Guilherme-b-damasio?style=for-the-badge&logo=github&color=1F6FEB&labelColor=0D1117"/>
  <img alt="Stars" src="https://img.shields.io/github/stars/Guilherme-b-damasio?style=for-the-badge&logo=github&color=1F6FEB&labelColor=0D1117"/>
</p>

---

## Let's Connect

🌐 [portfolio.devdek.online](https://portfolio.devdek.online) · 📧 [tabletgbd@gmail.com](mailto:tabletgbd@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/guilherme-boeira-damasio/) · 📝 [Dev.to](https://dev.to/guimk9)

<p align="center"><i>Open to conversations about backend architecture, distributed systems and applied AI.</i></p>
