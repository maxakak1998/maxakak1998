<h1 align="center">Hi, I'm Kiệt 👋</h1>

<p align="center">
  <b>Technical Lead · Senior Mobile &amp; Agentic AI Engineer at AppsCyclone · Ho Chi Minh City, Vietnam</b><br/>
  6+ years shipping production mobile apps and leading teams — now building the multi-agent tooling that lets those teams ship faster.
</p>

<p align="center">
  <a href="https://linkedin.com/in/phi-anh-kiet-0372b829b"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square" alt="LinkedIn"/></a>
  <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" alt="Flutter"/>
  <img src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white" alt="Dart"/>
  <img src="https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white" alt="Firebase"/>
  <img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/Cloudflare%20Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare Workers"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Claude%20Certified%20Architect-Foundations-D97757?style=flat-square" alt="Claude Certified Architect – Foundations"/>
</p>

---

### What I do

- **Mobile at production scale** — Flutter, Kotlin and Swift; Clean Architecture, BLoC/Cubit, realtime engines on isolates and WebSockets, payments, KYC and OTA updates.
- **Technical leadership** — led a team of 5 engineers, owning architecture, delivery and technical direction.
- **Developer tooling** — code generators and conventions that turn repetitive work (API clients, routes, features, use cases) into a single command.
- **Agentic AI engineering** — role-scoped agents, domain skills, enforcement hooks, MCP servers and knowledge graphs so coding agents follow a team's real architecture instead of guessing.
- **Backend and infrastructure** — Cloudflare Workers, Firebase, Node.js, Python, Docker.

Most of my work lives in private repositories, so this page describes it instead: client products first, then independent projects, then the parts I've open-sourced.

### Professional work

Shipped at AppsCyclone since 2020, across regulated wagering, Web3, recruitment and fitness.

| Product | Domain | My part |
| --- | --- | --- |
| **UPCOZ Mobile** | Regulated sports betting | Architected a 38-module Clean Architecture codebase and a background-isolate WebSocket engine for live odds and balances with auto-reconnect and state recovery. Built a JSON API generator for typed requests and models; integrated payments, KYC, biometrics, responsible-gambling controls and Shorebird OTA updates. |
| **Vincere Mobile** | Recruitment CRM / ATS | Technical team leader for 5 engineers across 40+ screens. Rich-text job editing (Markdown, Delta, HTML), offline sync, speech-to-text dictation; later led the Flutter 3 migration. |
| **GM2 Social Web3 Wallet** | Web3 / SocialFi | Flutter wallet infrastructure on the Aptos Dart SDK: key security, transaction signing, BNB staking, portfolio dashboards and rewards. |
| **WolfDen Mobile** | Social video | Flutter/BLoC messaging, a custom FFmpeg video-trimming pipeline, unified REST + GraphQL transport, Apple Pay and Google Pay. |
| **SDP · Meterpal · ShokWavz** | Betting · utilities · fitness | Sports tipping with KYC; utility meter tracking; realtime trainer–trainee sessions with BLE heart-rate monitoring and video calls. |
| **Skale Work Joy** | Enterprise HR | Employee engagement app for payroll, work timelines and HR requests. |

### Open source

| Project | What it is |
| --- | --- |
| [**flutter_tools**](https://github.com/maxakak1998/flutter_tools) | A toolkit for Flutter teams: Dart generators for API clients, routes, features and use cases, an API test runner, a library of agent instructions for consistent AI-generated code, and a **Knowledge Graph MCP server** (TypeScript, vector embeddings + graph relations) for on-demand project knowledge. |
| [**preview-cloud-function**](https://github.com/maxakak1998/preview-cloud-function) | Firebase Cloud Function that turns a URL into a rich link preview using stealth headless Chrome, with dedicated extractors for YouTube, X and TikTok. Extracted from a production app. |
| [**flutter_api_client**](https://github.com/maxakak1998/flutter_api_client) | A generic, strongly typed API client pattern for Flutter built on Dio. |
| [**slidable_page**](https://github.com/maxakak1998/slidable_page) | A custom sliding page interaction for Flutter, inspired by a movie-app design concept. |

### Independent projects

Private repositories, described without the code.

| Project | Stack | What I built |
| --- | --- | --- |
| **Agentic engineering platform** | Claude Code · MCP · knowledge graph | A multi-agent development framework running across 13 repositories: 7 role-scoped agents, 44 domain skills, 22 process-as-code enforcement hooks, a knowledge graph with 1,375+ durable chunks, and an adversarial multi-model debate protocol for verification. |
| **AI workout coach app** | Flutter · drift · Firebase · Cloudflare Workers | A local-first training app for iOS and web with an AI "next set" coach. All workout data stays on the device (export/import instead of sync), the coach talks to models through a decision proxy, and its answers are checked by benchmark, safety and post-deploy eval suites. Designed as 16 documented modules with explicit contracts. |
| **OpenAI-compatible AI gateway** | Cloudflare Workers · D1 · Durable Objects | A multi-client model router running in production: issued API keys, per-key limits and usage billing, provider chains with silent fallback, retries and hop-health tracking. Covered by unit, integration and contract tests against the official OpenAI SDK. |
| **Reading analytics app** | Flutter · drift · BLoC | An iOS/Android app that measures how people read English documents: one-sentence-at-a-time reader, per-sentence timing, and reports on where the reading time went. Product logic lives in a pure-Dart core with tests that pin every metric. |
| **Tablet POS for retail markets** | Flutter · Firestore · Shorebird | A landscape point-of-sale app for the Vietnamese market with over-the-air patches, a team of specialised coding agents, and a read-only Firestore MCP server for debugging live data. |
| **Crash aggregator** | Python · Sentry · BigQuery · MCP | A CLI and MCP server that pulls crashes from Sentry and Firebase Crashlytics, fingerprints and correlates them across sources, and ranks incidents by user impact so triage starts from the right place. |
| **Algorithmic quant trading platform** | Python · Freqtrade/FreqAI · XGBoost · GCP | Automated crypto strategies across 38 market variants with hyper-optimisation on spot instances, plus an autonomous research loop that requires 4-window walk-forward validation before a strategy is checkpointed. |
| **figma-normalizer** | Figma REST API · compiler design | A compiler that turns Figma REST data into a framework-agnostic semantic IR for AI-driven UI code generation. |

### Activity

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/maxakak1998/maxakak1998/output/github-contribution-grid-snake-dark.svg"/>
    <img src="https://raw.githubusercontent.com/maxakak1998/maxakak1998/output/github-contribution-grid-snake.svg" alt="Contribution graph animation"/>
  </picture>
</p>

<p align="center"><sub>Open to interesting mobile and agentic-AI work — reach me on <a href="https://linkedin.com/in/phi-anh-kiet-0372b829b">LinkedIn</a>.</sub></p>
