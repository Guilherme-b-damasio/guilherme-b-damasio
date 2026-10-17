<p align="right">
  <a href="README.md">🇺🇸 English</a> · <b>🇧🇷 Português</b>
</p>

<h1 align="center">Guilherme Boeira Damasio</h1>
<h3 align="center">Engenheiro de Software Backend · Node.js / TypeScript · PHP · AWS Serverless & Arquitetura Orientada a Eventos</h3>

<p align="center">
  <a href="https://portfolio.devdek.online" target="_blank"><img alt="Portfólio" src="https://img.shields.io/badge/Portf%C3%B3lio-111111?style=for-the-badge&logo=googlechrome&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/guilherme-boeira-damasio/" target="_blank"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge"/></a>
  <a href="mailto:tabletgbd@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://dev.to/guimk9" target="_blank"><img alt="Dev.to" src="https://img.shields.io/badge/Dev.to-0A0A0A?style=for-the-badge&logo=dev.to&logoColor=white"/></a>
  <a href="https://instagram.com/guiboeirad" target="_blank"><img alt="Instagram" src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/></a>
</p>

---

## Sobre

Engenheiro backend em Joinville 🇧🇷, trabalhando em sistemas que precisam continuar no ar e continuar corretos sob carga.

- 🚚 **Hoje:** APIs em **Node.js (Express, NestJS) com TypeScript** para uma plataforma de rastreamento veicular e gestão de frotas — um **pipeline orientado a eventos em SQS/SNS que processa milhões de posições de rastreadores por dia**, com processamento assíncrono e reprocessamento resiliente. **AWS Lambda** para cargas assíncronas e integrações, **dispositivos IoT** e sistemas de terceiros, e os serviços rodando em **Kubernetes (EKS/Rancher)** com seus pipelines de deploy no GitHub Actions.
- 🧪 **Antes:** ~2 anos com **PHP** em uma plataforma LIMS, implementando rotinas de cálculo críticas com **DDD e Clean Architecture** e levando a cobertura de testes de **10% para 40%** com PHPUnit enquanto refatorava módulos legados.
- 🤖 **Aprendendo em público:** **IA aplicada** — integrações com LLMs, RAG e **servidores MCP**. O [docsage](https://github.com/Guilherme-b-damasio/docsage) é onde isso vai parar.

O que me importa: fronteiras claras, testes que significam alguma coisa, observabilidade antes do incidente e código que a próxima pessoa consegue ler.

---

## Em destaque: docsage

> **Faça perguntas aos seus próprios documentos** — uma CLI de RAG e servidor MCP em Python, feita com Claude.

O [**docsage**](https://github.com/Guilherme-b-damasio/docsage) indexa arquivos Markdown, texto, HTML, Word e PDF (e páginas web por URL), recupera os trechos mais relevantes e pede ao Claude uma resposta que **cita as fontes** — até o caminho de títulos ou a página do PDF.

- **Recuperação configurável:** BM25, embeddings locais (sentence-transformers) ou **híbrida** com reciprocal rank fusion, além de **re-ranking opcional pelo Claude**
- **Medido, não chutado:** `docsage evaluate` calcula recall@k sobre consultas rotuladas; cada resultado explica a pontuação termo a termo
- **Servidor MCP** (stdio e HTTP) para o Claude Code e o Claude Desktop pesquisarem seus documentos, com relatórios HTML via **MCP Apps** mostrando as citações destacadas
- Indexação incremental, prompt caching, uso de tokens e custo por resposta, ciente de inglês e português
- Clean Architecture (domain / application / infrastructure / interfaces), SOLID, **460+ testes**, CI com ruff e mypy, git flow

`Python` · `Claude API` · `MCP` · `BM25` · `sentence-transformers` · `pytest`

---

## Stack

**Principais**

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

**IA aplicada**

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img alt="Claude API" src="https://img.shields.io/badge/Claude%20API-D97757?style=for-the-badge&logo=anthropic&logoColor=white"/>
  <img alt="MCP" src="https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=modelcontextprotocol&logoColor=white"/>
  <img alt="RAG" src="https://img.shields.io/badge/RAG-4B5563?style=for-the-badge"/>
  <img alt="sentence-transformers" src="https://img.shields.io/badge/sentence--transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
</p>

**Bancos de dados**

<p>
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img alt="MySQL" src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>
  <img alt="Redis" src="https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white"/>
  <img alt="SQLite" src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white"/>
  <img alt="Prisma" src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white"/>
</p>

**DevOps & Infraestrutura**

<p>
  <img alt="Kubernetes" src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
  <img alt="Jenkins" src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white"/>
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img alt="Bitbucket" src="https://img.shields.io/badge/Bitbucket-0052CC?style=for-the-badge&logo=bitbucket&logoColor=white"/>
  <img alt="NGINX" src="https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=white"/>
</p>

**Observabilidade & Testes**

<p>
  <img alt="Sentry" src="https://img.shields.io/badge/Sentry-362D59?style=for-the-badge&logo=sentry&logoColor=white"/>
  <img alt="Jest" src="https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white"/>
  <img alt="pytest" src="https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white"/>
  <img alt="Cypress" src="https://img.shields.io/badge/Cypress-69D3A7?style=for-the-badge&logo=cypress&logoColor=black"/>
  <img alt="Selenium" src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white"/>
  <img alt="Postman" src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"/>
</p>

<details>
<summary><b>Também já trabalhei com</b></summary>
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

**Arquitetura & práticas**

`Arquitetura Orientada a Eventos` · `Microsserviços` · `APIs REST` · `Clean Architecture` · `DDD` · `SOLID` · `TDD` · `Code Review` · `Scrum` · `Kanban` · `Integração com LLMs` · `RAG` · `Servidores MCP`

---

## O que eu construí

### DevDek — um jogo de cartas colecionáveis sobre a cena tech de Joinville

Devs entram com o GitHub e viram uma carta de personagem feita das próprias estatísticas — linguagens como poderes, atividade, badges. Empresas são checkpoints num mapa 3D: chegue fisicamente perto de uma e ganhe a carta-badge dela. Dois códigos separados, privados por enquanto — veja em [portfolio.devdek.online](https://portfolio.devdek.online).

| Projeto | O que eu fiz | Stack |
| --- | --- | --- |
| **DevDek — Backend** 🔒 | A API e as regras do jogo: OAuth do GitHub emitindo JWTs, geração de cartas renderizadas em imagem no servidor, **batalhas de cartas em tempo real via WebSockets**, check-ins por geolocalização em checkpoints de empresas curados, envios da comunidade com fluxo de moderação e entrega de logos pelo Cloudflare R2. Migrei a persistência de Mongoose/MongoDB para **Prisma/PostgreSQL**. As regras de batalha são cobertas por scripts de simulação que verificam invariantes em milhares de duelos gerados. | `NestJS` · `TypeScript` · `Prisma` · `PostgreSQL` · `Socket.IO` · `Passport (GitHub OAuth, JWT)` · `Satori/resvg` · `Cloudflare R2` · `Docker` |
| **DevDek — Mobile** 🔒 | App Android em **Expo** com expo-router, consumindo a mesma API do cliente web. OAuth do GitHub numa aba do navegador do sistema com deep link `devdek://` de volta (sem WebView embutida — o GitHub bloqueia OAuth nela, e o usuário precisa ver a barra de endereço), armazenamento seguro de token, coleção de cartas com filtros, mapa nativo com MapLibre, check-ins por GPS, QR pela câmera e renderização 3D com react-three-fiber. | `React Native` · `Expo` · `TypeScript` · `expo-router` · `MapLibre` · `react-three-fiber` · `expo-location` · `expo-secure-store` · `Socket.IO` |

### Open source

| Projeto | O que é | Stack |
| --- | --- | --- |
| [**docsage**](https://github.com/Guilherme-b-damasio/docsage) | RAG sobre os seus próprios documentos: CLI e servidor MCP que indexam Markdown, HTML, Word, PDF e páginas web, recuperam com BM25 / embeddings / busca híbrida e respondem com o Claude, citando as fontes. | `Python` · `Claude API` · `MCP` · `sentence-transformers` |
| [**Asaas Payment Gateway para Bagisto**](https://github.com/Guilherme-b-damasio/AsaasApiBagisto) | Dois pacotes complementares que integram o gateway Asaas ao Bagisto — PIX, boleto e cartão de crédito — expondo endpoints REST e tratando os webhooks de pagamento (`PAYMENT_CONFIRMED`, `PAYMENT_RECEIVED`, `PAYMENT_REFUNDED`). | `PHP 8.1+` · `Laravel` · `Bagisto` · `REST API` · `Webhooks` |
| [**VulnUI**](https://github.com/Guilherme-b-damasio/vulnui) | Dashboard que orquestra varreduras do **OWASP ZAP** e do **Nikto** numa única interface: spider, varredura ativa, progresso em tempo real e histórico de relatórios com classificação de risco. | `Next.js 15` · `TypeScript` · `Tailwind CSS 4` · `Docker` |
| [**vuln.ai**](https://github.com/Guilherme-b-damasio/vuln.ai) | O motor de varredura por trás do VulnUI — um orquestrador em Python que controla a API do ZAP e a CLI do Nikto e consolida os achados. | `Python` · `OWASP ZAP API` · `Nikto` |

---

## GitHub

<p align="center">
  <img alt="GitHub streak" src="https://streak-stats.demolab.com/?user=Guilherme-b-damasio&theme=tokyonight&hide_border=true&date_format=j%20M%5B%20Y%5D&locale=pt_BR"/>
</p>

<p align="center">
  <img alt="Seguidores" src="https://img.shields.io/github/followers/Guilherme-b-damasio?style=for-the-badge&logo=github&color=1F6FEB&labelColor=0D1117"/>
  <img alt="Estrelas" src="https://img.shields.io/github/stars/Guilherme-b-damasio?style=for-the-badge&logo=github&color=1F6FEB&labelColor=0D1117"/>
</p>

---

## Vamos conversar

🌐 [portfolio.devdek.online](https://portfolio.devdek.online) · 📧 [tabletgbd@gmail.com](mailto:tabletgbd@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/guilherme-boeira-damasio/) · 📝 [Dev.to](https://dev.to/guimk9)

<p align="center"><i>Aberto a conversas sobre arquitetura backend, sistemas distribuídos e IA aplicada.</i></p>
