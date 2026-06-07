<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1000&color=58A6FF&center=true&width=500&lines=Mohammad+Yusif+Albeladi;Software+Engineer+%E2%80%94+Saudi+Arabia;Full-stack+%7C+AI+%7C+Cloud" alt="Typing SVG" />
</div>

<p align="center">
  <a href="https://github.com/MohammadYusif?tab=followers">
    <img src="https://custom-icon-badges.demolab.com/github/followers/MohammadYusif?color=236ad3&labelColor=1155ba&style=for-the-badge&logo=person-add&label=Follow&logoColor=white" alt="Follow on GitHub" />
  </a>
  <a href="https://github.com/MohammadYusif?tab=repositories&sort=stargazers">
    <img src="https://custom-icon-badges.demolab.com/github/stars/MohammadYusif?color=55960c&style=for-the-badge&labelColor=488207&logo=star" alt="Total stars" />
  </a>
  <a href="mailto:mosefbel@gmail.com">
    <img src="https://img.shields.io/badge/mosefbel@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

<br/>

I'm a software engineer based in Saudi Arabia. I build things end-to-end — from the database schema and the API to the UI and the infrastructure that runs it all. Most of what I make is either a production SaaS product or an AI tool that solves a specific, real problem.

---

## 📦 Projects

### [Pointly](https://github.com/MohammadYusif/pointly)
![Next.js](https://img.shields.io/badge/Next.js-black?style=flat-square&logo=next.js&logoColor=white) ![AWS Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white) ![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)

A loyalty platform built for the Saudi market. Merchants issue and manage loyalty points through a branded portal; customers track their balance, tier status, and transaction history through a separate portal. The whole system runs on AWS — Fastify on Lambda, DynamoDB, CloudFront — managed with Terraform and deployed as a monorepo. I designed the data model, built both dashboards in Next.js, and wrote all the infrastructure.

### [Raff](https://github.com/MohammadYusif/raff)
![Next.js](https://img.shields.io/badge/Next.js-black?style=flat-square&logo=next.js&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)

A product discovery and aggregation platform for Saudi e-commerce. Merchants on Salla and Zid connect their stores and their products surface in a single unified shelf — searchable, filterable, and sorted by what's actually trending. The goal was to give small Saudi merchants the kind of visibility that usually requires a paid ad budget.

### [agentslog](https://github.com/MohammadYusif/agentslog)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

A developer tool for anyone using AI coding agents. It indexes every Claude Code session — every tool call, file edit, and decision — into a local SQLite database you can query however you like. The idea came from my own frustration of watching agents repeat the same mistakes across sessions with no memory of what went wrong last time.

### [blind-nav-ai](https://github.com/MohammadYusif/blind-nav-ai)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)

An Arabic-speaking navigation assistant for visually impaired users, built with zero-shot vision-language models. The Arabic-first design was intentional — most accessibility tools in this space assume English. This started as a university project and ended up being something I was genuinely proud of shipping.

### [baseera-ai](https://github.com/MohammadYusif/baseera-ai)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Meta Llama](https://img.shields.io/badge/Llama_3.1-7C3AED?style=flat-square&logo=meta&logoColor=white)

A RAG-powered support companion for drug awareness, using Llama 3.1. Built to feel like a conversation rather than a lookup table — the goal was approachability for people who wouldn't otherwise seek out information on their own.

---

<details>
  <summary><h2>🤝 Open Source Contributions</h2></summary>
  <br/>

  Bug fixes and features shipped to production open-source projects:

  | Project | What I fixed / added |
  |---|---|
  | [pallets/click](https://github.com/pallets/click) | Added missing `skipif` markers to surrogate-filename tests that failed on non-UTF-8 filesystems |
  | [scrapy/scrapy](https://github.com/scrapy/scrapy) | Fixed `pathlib.Path` feed URIs being URL-encoded, breaking `%`-format specifiers in filenames |
  | [aio-libs/aiohttp](https://github.com/aio-libs/aiohttp) | Fixed `BodyPartReader.read()` returning `bytearray` instead of `bytes`, breaking JSON serialization |
  | [marshmallow-code/marshmallow](https://github.com/marshmallow-code/marshmallow) | Fixed `get_value` raising `TypeError` on out-of-range integer indexes instead of returning the default |
  | [open-telemetry/opentelemetry-js](https://github.com/open-telemetry/opentelemetry-js) | Fixed `timeInputToHrTime` misclassifying epoch-ms timestamps as relative readings due to clock skew |
  | [open-webui/open-webui](https://github.com/open-webui/open-webui) | Fixed silent failure when LLM calls a non-existent tool name — now returns structured error feedback |
  | [sveltejs/language-tools](https://github.com/sveltejs/language-tools) | Fixed optional properties completing without `?` in the completion label |
  | [dask/distributed](https://github.com/dask/distributed) | Replaced wall-clock boundary in `get_task_stream` context manager with a monotonic append index |
  | [mozilla/pilo](https://github.com/mozilla/pilo) | Added inactivity timeout to LLM stream consumption, preventing silent hangs on stalled providers |
  | [Lightning-AI/litData](https://github.com/Lightning-AI/litData) | Fixed lexicographic chunk ordering in `train_test_split` corrupting datasets with 10+ chunks |
  | [elevenlabs/packages](https://github.com/elevenlabs/packages) | Fixed `PingEvent.ping_ms` type to allow `null`; added missing `Ping` wrapper to exports barrel |
  | [excaliburjs/Excalibur](https://github.com/excaliburjs/Excalibur) | Fixed per-particle `z` config being ignored when `ParticleTransform.Global` is set |
  | [unjs/ofetch](https://github.com/unjs/ofetch) | Fixed `instanceof` guards running after `value.buffer` check in `isJSONSerializable` |
  | [apache/solr-orbit](https://github.com/apache/solr-orbit) | Added fallback to Cores API when delete-collection runs against standalone (non-cloud) Solr |
  | [openwisp/openwisp-notifications](https://github.com/openwisp/openwisp-notifications) | Fixed `get_user_email_preference` ignoring the notification type default for org-less shared targets |
  | [barebaric/rayforge](https://github.com/barebaric/rayforge) | Fixed `ValueError` crash when deleting the currently active machine |
  | [snw-mint/fluent-new-tab](https://github.com/snw-mint/fluent-new-tab) | Fixed hardcoded English `<title>` not being wired into the extension's i18n system |
  | [go-via/via](https://github.com/go-via/via) | Added `reason` label (`client`/`shutdown`/`ttl`) to the `via.sse.disconnect` metrics counter |
  | [NEAR-DevHub/trezu](https://github.com/NEAR-DevHub/trezu) | Fixed bulk payment amounts ~1000× too small when input used comma as thousands separator |
  | [pewdiepie-archdaemon/odysseus](https://github.com/pewdiepie-archdaemon/odysseus) | Added `GET /api/history/stats` endpoint for zero-config token and session usage aggregation |
  | [0b01001001/spectree](https://github.com/0b01001001/spectree) | Fixed `NameError` crash on `TYPE_CHECKING`-only return annotations in `annotations=True` mode |
  | [OWASP/cve-lite-cli](https://github.com/OWASP/cve-lite-cli) | Added 100% test coverage for `validate.ts`; extracted `pluralize` utility across 8 files |
  | [repowise-dev/repowise](https://github.com/repowise-dev/repowise) | Fixed structlog output polluting `--format json` stdout |
  | [404-PF/commit-echo](https://github.com/404-PF/commit-echo) | Fixed git error swallowing, dollar-sign corruption in prompt expansion, bullet-list parsing |

</details>

<details>
  <summary><h2>🛠️ Stack</h2></summary>
  <br/>

  <p>
    <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" />
    <img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white" />
    <img src="https://img.shields.io/badge/Next.js-black?style=flat&logo=next.js&logoColor=white" />
    <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
    <img src="https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-web-services&logoColor=white" />
    <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white" />
    <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white" />
  </p>

</details>

---

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/MohammadYusif/MohammadYusif/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/MohammadYusif/MohammadYusif/output/github-contribution-grid-snake.svg" />
    <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/MohammadYusif/MohammadYusif/output/github-contribution-grid-snake.svg" />
  </picture>
</div>

<br/>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=MohammadYusif&style=flat-square&color=58A6FF&label=profile+views" />
</div>
