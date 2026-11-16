<h1 align="center">Hi, I'm Kiệt 👋</h1>

<p align="center">
  <b>Mobile engineer at Apps Cyclone · Ho Chi Minh City, Vietnam</b><br/>
  I build production Flutter apps and the tooling that helps teams ship them faster — increasingly with AI agents in the loop.
</p>

<p align="center">
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

- **Flutter at production scale** — clean architecture, Cubit/BLoC state management, typed routing, offline-first repositories, native code porting.
- **Developer tooling** — code generators and conventions that turn repetitive work (API clients, routes, features, use cases) into a single command.
- **AI-assisted engineering** — agent instructions, MCP servers and knowledge retrieval so coding agents follow a team's real architecture instead of guessing.
- **Backend glue** — Firebase Cloud Functions, Firestore triggers, headless scraping with Puppeteer.

Most of my work lives in private repositories. The open-source parts are under **Featured work**; a summary of the private side is under **Behind closed doors**.

### Featured work

| Project | What it is |
| --- | --- |
| [**flutter_tools**](https://github.com/maxakak1998/flutter_tools) | A toolkit for Flutter teams: Dart generators for API clients, routes, features and use cases, an API test runner, a library of agent instructions for consistent AI-generated code, and a **Knowledge Graph MCP server** (TypeScript, vector embeddings + graph relations) for on-demand project knowledge. |
| [**preview-cloud-function**](https://github.com/maxakak1998/preview-cloud-function) | Firebase Cloud Function that turns a URL into a rich link preview using stealth headless Chrome, with dedicated extractors for YouTube, X and TikTok. Extracted from a production app. |
| [**flutter_api_client**](https://github.com/maxakak1998/flutter_api_client) | A generic, strongly typed API client pattern for Flutter built on Dio. |
| [**slidable_page**](https://github.com/maxakak1998/slidable_page) | A custom sliding page interaction for Flutter, inspired by a movie-app design concept. |

### Behind closed doors

Private projects, described without the code.

| Project | Stack | What I built |
| --- | --- | --- |
| **AI workout coach app** | Flutter · drift · Firebase · Cloudflare Workers | A local-first training app for iOS and web with an AI "next set" coach. All workout data stays on the device (export/import instead of sync), the coach talks to models through a decision proxy, and its answers are checked by benchmark, safety and post-deploy eval suites. Designed as 16 documented modules with explicit contracts. |
| **OpenAI-compatible AI gateway** | Cloudflare Workers · D1 · Durable Objects | A multi-client model router running in production: issued API keys, per-key limits and usage billing, provider chains with silent fallback, retries and hop-health tracking. Covered by unit, integration and contract tests against the official OpenAI SDK. |
| **Reading analytics app** | Flutter · drift · BLoC | An iOS/Android app that measures how people read English documents: one-sentence-at-a-time reader, per-sentence timing, and reports on where the reading time went. Product logic lives in a pure-Dart core with tests that pin every metric. |
| **Tablet POS for retail markets** | Flutter · Firestore · Shorebird | A landscape point-of-sale app for the Vietnamese market with over-the-air patches, a team of specialised coding agents, and a read-only Firestore MCP server for debugging live data. |
| **Crash aggregator** | Python · Sentry · BigQuery · MCP | A CLI and MCP server that pulls crashes from Sentry and Firebase Crashlytics, fingerprints and correlates them across sources, and ranks incidents by user impact so triage starts from the right place. |
| **ML trading research bot** | Python · Freqtrade/FreqAI · XGBoost · Docker | An algorithmic trading research stack: gradient-boosted price models gated by rule-based market-structure confirmations, with stationary engineered features, containerised for local development and cloud spot instances. |

### Activity

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/maxakak1998/maxakak1998/output/github-contribution-grid-snake-dark.svg"/>
    <img src="https://raw.githubusercontent.com/maxakak1998/maxakak1998/output/github-contribution-grid-snake.svg" alt="Contribution graph animation"/>
  </picture>
</p>

<p align="center"><sub>Open to interesting Flutter and AI-tooling work — the fastest way to reach me is an issue or discussion on any repo above.</sub></p>
