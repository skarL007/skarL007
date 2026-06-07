<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=160&color=0:020617,35:1d4ed8,75:14b8a6,100:0f172a&text=Marcelo%20Machuca&fontColor=ffffff&fontSize=42&fontAlignY=35&desc=AI%20Product%20Engineer%20%7C%20RAG%20%7C%20Voice%20AI%20%7C%20LLMOps%20%7C%20Open%20Source&descAlignY=61&descSize=14" alt="Marcelo Machuca - AI Product Engineer" />

<br />

<img src="https://img.shields.io/badge/AI%20Product%20Engineer-2563eb?style=for-the-badge" alt="AI Product Engineer" />
<img src="https://img.shields.io/badge/RAG%20%2B%20Memory-14b8a6?style=for-the-badge" alt="RAG and Memory" />
<img src="https://img.shields.io/badge/Open%20Source%20Contributor-0f172a?style=for-the-badge" alt="Open Source Contributor" />

<br />
<br />

<h3>
I build AI products with RAG, voice pipelines, observability, agentic workflows and production-style validation.
</h3>

<p>
Python, TypeScript, FastAPI, React, LLM workflows, evals, runtime checks and pragmatic delivery.
</p>

</div>

---

## Snapshot

- **31 merged public PRs** across GitHub projects as of June 2026.
- **6 merged upstream PRs in [qdrant/qdrant](https://github.com/qdrant/qdrant)**.
- **19 merged PRs in [smaramwbc/statewave](https://github.com/smaramwbc/statewave)**.
- Building applied AI systems around **RAG, memory, voice AI, LLMOps, automation and validation**.
- Open to focused work on AI product engineering, backend correctness, AI-assisted delivery and production hardening.

---

## Open Source Contributions

| Project | Signal | Areas |
| --- | ---: | --- |
| [Qdrant](https://github.com/qdrant/qdrant) | 6 merged upstream PRs | API validation, gRPC hardening, geo validation, snapshot checksum validation, overflow hardening |
| [Statewave](https://github.com/smaramwbc/statewave) | 19 merged PRs | tenant isolation, backend correctness, data integrity, admin/runtime behavior |
| [sound_voice](https://github.com/skarL007/sound_voice) | public product repo | local-first TTS launcher for assistive communication |

Selected Qdrant PRs:

- [qdrant/qdrant#9271](https://github.com/qdrant/qdrant/pull/9271) - return formula default validation errors.
- [qdrant/qdrant#9302](https://github.com/qdrant/qdrant/pull/9302) - validate shard snapshot upload checksum.
- [qdrant/qdrant#9308](https://github.com/qdrant/qdrant/pull/9308) - reject empty multi-vector in flattened `vectors_count` path.
- [qdrant/qdrant#9309](https://github.com/qdrant/qdrant/pull/9309) - validate geo polygon in gRPC `FieldCondition`.
- [qdrant/qdrant#9321](https://github.com/qdrant/qdrant/pull/9321) - avoid query limit + offset overflow.
- [qdrant/qdrant#9323](https://github.com/qdrant/qdrant/pull/9323) - harden geo-polygon interior cardinality estimation.

More contribution views:

- [Statewave PRs authored by me](https://github.com/smaramwbc/statewave/pulls?q=author%3AskarL007)
- [Qdrant PRs authored by me](https://github.com/qdrant/qdrant/pulls?q=author%3AskarL007)
- [All merged GitHub PRs authored by me](https://github.com/search?q=author%3AskarL007+type%3Apr+is%3Amerged&type=pullrequests)

---

## Featured Work

### [LumenAI SDK](https://github.com/skarL007/-lumen-ai-sdk)

GenAI FinOps and observability SDK for tenant-aware cost attribution, OpenTelemetry metadata, Redis/JSONL exporters and typed event contracts.

`Python` `OpenTelemetry` `Redis` `JSONL` `Cost tracking` `SDK design`

What it shows:

- Tenant-level GenAI cost attribution.
- Metadata-first event tracking.
- Local demo paths that do not require paid model calls.
- SDK-style documentation and typed contracts.

### [VoiceLaunch TTS](https://github.com/skarL007/sound_voice)

Local-first desktop TTS launcher for assistive communication. It turns typed text into speech and can route audio to local playback or a virtual microphone for Discord, games and calls.

`Electron` `React` `FastAPI` `Python` `Piper` `Kokoro` `TTS` `Accessibility`

What it shows:

- Local-first voice product architecture.
- Assistive communication use case.
- React + Electron + Python/FastAPI runtime.
- Accessibility thinking around quick phrases, history, keyboard flow and high-contrast UI.

### [CapiNews Data](https://github.com/skarL007/capinews-data)

Static data and frontend layer for automated daily AI intelligence reports.

`Automation` `Static frontend` `JSON data` `Reports` `GitHub Pages`

What it shows:

- Lightweight automated publishing.
- Daily generated report data.
- Public-facing information product workflow.

### [AI Software Engineering Notes](https://github.com/skarL007/engenharia-de-software-com-ia-aplicada)

Learning and reference repository around AI engineering, prompt engineering, LLMs, RAG, MCPs, browser AI, local models and applied automation.

`AI engineering` `LLMs` `RAG` `MCP` `Automation` `Research notes`

---

## How I Build

I work with AI coding agents as part of the development workflow, but I keep ownership on the parts that matter professionally:

- architecture and product direction;
- decomposition into small, reviewable changes;
- code review and risk assessment;
- tests, evals, smoke checks and validation;
- documentation of trade-offs, limits and rollback paths;
- iteration based on evidence instead of demos that only look good.

```text
idea -> architecture -> implementation -> review -> validation -> deploy -> iteration
```

The goal is not to make AI-generated code look traditional. The goal is to build systems that can be tested, explained, maintained and improved.

---

## Strongest Areas

### Product architecture

- Turn ambiguous AI product ideas into concrete services, flows and validation gates.
- Balance deterministic logic, LLM calls, RAG, memory, caching and fallback paths.
- Design around user experience, latency, cost and reliability.

### Applied AI engineering

- RAG pipelines with embeddings, metadata and contextual retrieval.
- Voice AI flows with STT, LLM, TTS, streaming and cache strategy.
- LLM routing, prompt contracts, evals, cost tracking and latency benchmarks.
- Observability for quality, usage, errors, cost and runtime behavior.

### Delivery and validation

- Release gates, tests, smoke checks and benchmark reports.
- Production-like validation before calling something done.
- Documentation of risks, trade-offs, rollback paths and known limitations.

---

## Technical Stack

**Backend:** Python, FastAPI, Pydantic, SQLAlchemy, async services, REST APIs, validation and runtime checks.

**Frontend:** TypeScript, React, Vite, dashboards, validation UIs and desktop/web product surfaces.

**AI / RAG:** LLM APIs, embeddings, vector search, memory layers, prompt contracts, evals and model comparisons.

**Voice AI:** STT/TTS pipelines, Piper, Kokoro, streaming audio, cache strategy and local-first voice workflows.

**Ops / Quality:** Docker, PostgreSQL, Redis, OpenTelemetry, pytest, smoke tests, health checks and release discipline.

---

## Private Labs

Some stronger product experiments are private because they include client-style delivery flows, internal workflows or unpublished product code. The relevant public signal is the pattern behind them:

- RAG + persona + voice AI systems with memory, observability, cost tracking and deployment gates.
- Agentic workflow platforms with dry-run execution, human approval and validation reports.
- Local AI architecture workbenches for prompt-to-product workflows.
- Automation systems for lead workflows, research and internal operations.

Case studies can be shared without exposing private source code.

---

## Current Focus

```text
RAG + memory systems
Voice AI and TTS/STT pipelines
LLMOps dashboards and cost tracking
AI-assisted software engineering
Agentic workflows with guardrails
Production validation and release discipline
```

---

<div align="center">

<strong>Build useful systems. Validate the behavior. Keep improving the evidence.</strong>

<br />
<br />

<a href="https://github.com/skarL007">
  <img src="https://img.shields.io/badge/GitHub-skarL007-18181b?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>

</div>
