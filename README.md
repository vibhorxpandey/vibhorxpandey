<!-- Profile README for github.com/vibhorxpandey.
     Assets live in /assets. The contribution snake regenerates daily
     via .github/workflows/snake.yml. -->

<div align="center">

<img src="assets/hero.svg" alt="Vibhor Pandey. Builder, researcher, founder." width="100%">

<img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&weight=500&size=19&duration=3000&pause=1000&color=E3B341&center=true&vCenter=true&width=680&height=45&lines=Founder+%40+Veil;Building+fact-checked+AI+research+infrastructure;ML+engineer+%E2%80%A2+hybrid+retrieval+%E2%80%A2+agentic+systems;Author+of+The+Quiet+Mathematics+of+Life" alt="Founder @ Veil. Building fact-checked AI research infrastructure. ML engineer working on hybrid retrieval and agentic systems. Author of The Quiet Mathematics of Life.">

<p>
  <a href="https://veilresearch.com">veilresearch.com</a>
  &nbsp;·&nbsp;
  <a href="https://veilfinance.ink">veilfinance.ink</a>
  &nbsp;·&nbsp;
  <a href="https://pypi.org/project/aurelius-mcp/"><code>pip install aurelius-mcp</code></a>
  &nbsp;·&nbsp;
  <a href="https://orcid.org/0009-0009-2810-6222">ORCID</a>
</p>

</div>

<br>

## The Short Version

I'm a second-year B.Tech CSE (AI/ML) student at UPES, Dehradun, and I got impatient with toy projects early. So I ship production systems instead: **[Veil](https://veilresearch.com)**, the AI research infrastructure company I founded; **[Aurelius](https://github.com/vibhorxpandey/Aurelius)**, a fact-checked research MCP server on PyPI that refuses to show you a citation it hasn't verified; and a string of retrieval systems I benchmark properly before I talk about them. Recall@1 and MRR, or it didn't happen.

Away from the keyboard I trade Indian equities and crypto derivatives, I'm preparing for CFA Level 1, and I run a hyperlocal kirana delivery operation across 55+ shops. Logistics, it turns out, is just systems engineering with worse error messages.

First principles over frameworks. Verification over vibes.

<br>

<img src="assets/divider.svg" width="100%" alt="">

## Current Threads

| thread | what it is | right now |
|:--|:--|:--|
| **[Veil Research](https://veilresearch.com)** | AI-native research infrastructure (the company) | hardening citation-enforced paper generation across five front-ends: web · CLI/SDK · MCP server · Skill · Claude Code plugin |
| **[Veil Finance](https://veilfinance.ink)** | AI research terminal for Indian small mid cap equities | a portfolio-aware materiality classifier over SEBI LODR Reg-30 labels, built with LightGBM and Mondrian conformal prediction |
| **[Aurelius](https://github.com/vibhorxpandey/Aurelius)** | fact-checked research MCP server | `v0.6.0` is live on PyPI. next: more verification backends and a deeper autonomous mode |

<br>

<img src="assets/divider.svg" width="100%" alt="">

## Aurelius · the signature build (still building)

<div align="center">

<a href="https://pypi.org/project/aurelius-mcp/"><img src="https://img.shields.io/pypi/v/aurelius-mcp?style=flat-square&labelColor=0d1117&color=e3b341&label=PyPI" alt="PyPI version"></a>
&nbsp;<img src="https://img.shields.io/pypi/pyversions/aurelius-mcp?style=flat-square&labelColor=0d1117&color=21262d" alt="Python ≥3.10">
&nbsp;<img src="https://img.shields.io/badge/license-MIT-21262d?style=flat-square&labelColor=0d1117" alt="MIT license">

</div>

A research assistant is only as good as its worst citation. **Aurelius** is a research MCP server that checks **every citation** against OpenAlex and Crossref (DOI-backed and retraction-aware) and **every claim** against live web sources, all before anything reaches you. It plugs into any MCP-capable app (Claude Desktop and Claude Code, Gemini CLI, Cursor, ChatGPT) and runs host-driven, so it needs no LLM key of its own. There's an autonomous mode for when you want it to run alone.

```text
topic -> screen -> draft -> fact-check -> revise -> you

inside fact-check:
  every citation  ->  OpenAlex + Crossref   (DOI-backed, retraction-aware)
  every claim     ->  live web sources      (verified before you see it)
```

```bash
pip install aurelius-mcp
```

<p align="center">
  <a href="https://github.com/vibhorxpandey/Aurelius"><b>Repository</b></a>
  &nbsp;·&nbsp;
  <a href="https://pypi.org/project/aurelius-mcp/"><b>PyPI</b></a>
</p>

<br>

<img src="assets/divider.svg" width="100%" alt="">

## Veil · the company

Research tooling that treats verification as infrastructure instead of an afterthought.

<table width="100%">
<tr>
<td width="50%" valign="top">

<h3 align="center"><a href="https://veilresearch.com">Veil Research</a></h3>

<p>A unified AI workspace for researchers and ML engineers, with five expert modes and citation-enforced research-paper generation. Compile and export are <b>structurally blocked</b> on unresolved citations, so you can't ship an unverified claim even if you try.</p>

<p><sub><b>Architecture</b>: Supabase Postgres · libsodium BYOK encryption · LiteLLM gateway · five front-ends (web, CLI/SDK, MCP server, Skill, Claude Code plugin)</sub></p>

<p align="center"><a href="https://veilresearch.com">site</a> · <a href="https://github.com/vibhorxpandey/veil">repo</a></p>

</td>
<td width="50%" valign="top">

<h3 align="center"><a href="https://veilfinance.ink">Veil Finance</a></h3>

<p>An AI-native research terminal for Indian small and mid-cap equity markets. At its core sits a portfolio-aware materiality classifier over SEBI LODR Reg-30 disclosure labels, running LightGBM under Mondrian conformal prediction, so every signal carries a calibrated confidence guarantee instead of a guess.</p>

<p><sub><b>Architecture</b>: LightGBM · Mondrian conformal prediction · TypeScript front-end</sub></p>

<p align="center"><a href="https://veilfinance.ink">site</a> · <a href="https://github.com/vibhorxpandey/veil-finance">repo</a></p>

</td>
</tr>
</table>

<br>

<img src="assets/divider.svg" width="100%" alt="">

## Selected Builds

<table width="100%">
<tr>
<td width="50%" valign="top">

<h3 align="center"><a href="https://github.com/vibhorxpandey/Echomind">EchoMind</a></h3>

<p><i>"The senior who never graduates."</i> An institutional-memory AI agent for college clubs. Hybrid retrieval over Qdrant (BM25 + dense + Reciprocal Rank Fusion + cross-encoder reranking) with long-term memory, and a verified ablation to back it up: <b>93% Recall@1 and 0.967 MRR</b>.</p>

<p><sub><b>Stack</b>: Google ADK · Gemini · Qdrant · FastAPI · Next.js / React-Three-Fiber</sub></p>

<p align="center"><a href="https://echomindai.vercel.app">live</a> · <a href="https://github.com/vibhorxpandey/Echomind">repo</a></p>

</td>
<td width="50%" valign="top">

<h3 align="center"><a href="https://github.com/vibhorxpandey/vayudhrishti">VayuDrishti</a></h3>

<p>Hyperlocal, multi-modal pollution-hotspot intelligence. Satellite, sensor and citizen signals fused into a mission-control dashboard for the air you actually breathe.</p>

<p><sub><b>Stack</b>: Gemini 2.5 Flash · FastAPI · LightGBM · Next.js / deck.gl</sub></p>

<p align="center"><a href="https://vayudhrishti.vercel.app">live</a> · <a href="https://github.com/vibhorxpandey/vayudhrishti">repo</a></p>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3 align="center"><a href="https://github.com/vibhorxpandey/IDBI">LendLens</a></h3>

<p>AI lead generation and income assessment for retail lending, built for <b>IDBI Innovate 2026, Track 02</b>. Uplift-modeled targeting with SHAP explainability and fairness auditing baked in, because in lending a model you can't explain is a liability.</p>

<p><sub><b>Stack</b>: XGBoost · SHAP · scikit-uplift · fairlearn · Vite / React</sub></p>

<p align="center"><a href="https://lendlens-idbi-track02.vercel.app">live</a> · <a href="https://github.com/vibhorxpandey/IDBI">repo</a></p>

</td>
<td width="50%" valign="top">

<h3 align="center"><a href="https://github.com/vibhorxpandey/redrob-ranker">redrob-ranker · redrob-hire</a></h3>

<p>A hybrid-retrieval scoring engine (BM25 + BGE-M3 dense + cross-encoder reranking) with honeypot and prompt-injection detection and <b>76/76 tests passing</b>, plus the recruiter-screening Lemma pod that wraps it. Built for the Gappy AI Hackathon.</p>

<p><sub><b>Stack</b>: Python · BM25 · BGE-M3 · cross-encoders · Lemma</sub></p>

<p align="center"><a href="https://github.com/vibhorxpandey/redrob-ranker">ranker</a> · <a href="https://github.com/vibhorxpandey/redrob-hire">hire</a></p>

</td>
</tr>
</table>

<details>
<summary><b>Also on the shelf</b></summary>
<br>

- **[remindr](https://github.com/vibhorxpandey/remindr)**: a task-reminder PWA with an adaptive neural network and an AI companion named Rem *(TypeScript)*
- **[jarvis / FRIDAY](https://github.com/vibhorxpandey/jarvis)**: a speech-recognition voice assistant prototype *(Python)*
- **[100-days-of-code](https://github.com/vibhorxpandey/100-days-of-code)** · **[100-days-of-code-DSA](https://github.com/vibhorxpandey/100-days-of-code-DSA)**: the C/C++ grind that started all of this

</details>

<br>

<img src="assets/divider.svg" width="100%" alt="">

## Toolbox

<div align="center">

<table>
<tr>
<td align="right" valign="middle"><sub><b>LANGUAGES</b></sub></td>
<td>
<img src="https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=e3b341" alt="Python">
<img src="https://img.shields.io/badge/C-0d1117?style=flat-square&logo=c&logoColor=e3b341" alt="C">
<img src="https://img.shields.io/badge/C%2B%2B-0d1117?style=flat-square&logo=cplusplus&logoColor=e3b341" alt="C++">
<img src="https://img.shields.io/badge/Java-0d1117?style=flat-square&logo=openjdk&logoColor=e3b341" alt="Java">
<img src="https://img.shields.io/badge/JavaScript-0d1117?style=flat-square&logo=javascript&logoColor=e3b341" alt="JavaScript">
<img src="https://img.shields.io/badge/TypeScript-0d1117?style=flat-square&logo=typescript&logoColor=e3b341" alt="TypeScript">
</td>
</tr>
<tr>
<td align="right" valign="middle"><sub><b>ML &amp; AI</b></sub></td>
<td>
<img src="https://img.shields.io/badge/XGBoost-0d1117?style=flat-square" alt="XGBoost">
<img src="https://img.shields.io/badge/LightGBM-0d1117?style=flat-square" alt="LightGBM">
<img src="https://img.shields.io/badge/SHAP-0d1117?style=flat-square" alt="SHAP">
<img src="https://img.shields.io/badge/scikit--uplift-0d1117?style=flat-square" alt="scikit-uplift">
<img src="https://img.shields.io/badge/fairlearn-0d1117?style=flat-square" alt="fairlearn">
<img src="https://img.shields.io/badge/vLLM-0d1117?style=flat-square" alt="vLLM">
<img src="https://img.shields.io/badge/Qdrant-0d1117?style=flat-square" alt="Qdrant">
<img src="https://img.shields.io/badge/pgvector-0d1117?style=flat-square" alt="pgvector">
<img src="https://img.shields.io/badge/LiteLLM-0d1117?style=flat-square" alt="LiteLLM">
</td>
</tr>
<tr>
<td align="right" valign="middle"><sub><b>WEB &amp; DATA</b></sub></td>
<td>
<img src="https://img.shields.io/badge/Next.js-0d1117?style=flat-square&logo=nextdotjs&logoColor=e3b341" alt="Next.js">
<img src="https://img.shields.io/badge/React-0d1117?style=flat-square&logo=react&logoColor=e3b341" alt="React">
<img src="https://img.shields.io/badge/FastAPI-0d1117?style=flat-square&logo=fastapi&logoColor=e3b341" alt="FastAPI">
<img src="https://img.shields.io/badge/PostgreSQL-0d1117?style=flat-square&logo=postgresql&logoColor=e3b341" alt="PostgreSQL">
<img src="https://img.shields.io/badge/Supabase-0d1117?style=flat-square&logo=supabase&logoColor=e3b341" alt="Supabase">
<img src="https://img.shields.io/badge/Redis-0d1117?style=flat-square&logo=redis&logoColor=e3b341" alt="Redis">
</td>
</tr>
<tr>
<td align="right" valign="middle"><sub><b>INFRA &amp; PROTOCOLS</b></sub></td>
<td>
<img src="https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=e3b341" alt="Docker">
<img src="https://img.shields.io/badge/Vercel-0d1117?style=flat-square&logo=vercel&logoColor=e3b341" alt="Vercel">
<img src="https://img.shields.io/badge/Git-0d1117?style=flat-square&logo=git&logoColor=e3b341" alt="Git">
<img src="https://img.shields.io/badge/MCP-0d1117?style=flat-square&logo=modelcontextprotocol&logoColor=e3b341" alt="Model Context Protocol">
<img src="https://img.shields.io/badge/Google_ADK-0d1117?style=flat-square&logo=google&logoColor=e3b341" alt="Google ADK">
<img src="https://img.shields.io/badge/Lyzr-0d1117?style=flat-square" alt="Lyzr">
</td>
</tr>
</table>

</div>

**What the badges don't say:**

| | |
|--:|:--|
| **retrieval** | hybrid sparse + dense search: BM25 and BGE-M3 fused with Reciprocal Rank Fusion, cross-encoder reranking on top. Qdrant and pgvector in production, benchmarked with Recall@1 and MRR |
| **llm systems** | RAG pipelines, agentic orchestration, MCP servers, LiteLLM gateways, self-hosted inference (Qwen 14B on vLLM)prompt-injection detection, citation-integrity gating |
| **uncertainty** | Mondrian conformal prediction, Neyman-Pearson classification, uplift modeling, fairness auditing |
| **classical ml** | gradient-boosted trees, SHAP explainability, NLP, neural nets |

<br>

<img src="assets/divider.svg" width="100%" alt="">

## The Quiet Mathematics of Life

<div align="center">

<img src="assets/quiet-mathematics.svg" alt="&quot;Reality has a grammar: entropy, equilibrium, signal, noise. Most of us never learn to read it.&quot; From The Quiet Mathematics of Life, a book in progress." width="100%">

</div>

I'm writing a book about reality as it actually is, not as we assume it to be. A fictionalized protagonist moves through the real, underlying structure of the world, and the prose keeps the physics close: entropy, equilibrium, phase transitions, signal and noise.

Slow work, on purpose.

<br>

<img src="assets/divider.svg" width="100%" alt="">

## The Ledger

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=vibhorxpandey&show_icons=true&hide_border=true&bg_color=0d1117&title_color=e3b341&icon_color=e3b341&text_color=c9d1d9&include_all_commits=true&count_private=true&rank_icon=github" alt="GitHub stats">
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=vibhorxpandey&layout=compact&hide_border=true&bg_color=0d1117&title_color=e3b341&text_color=c9d1d9&langs_count=8" alt="Top languages">

<br><br>

<img src="https://streak-stats.demolab.com?user=vibhorxpandey&hide_border=true&background=0D1117&ring=E3B341&fire=E3B341&currStreakNum=E6EDF3&sideNums=E6EDF3&currStreakLabel=E3B341&sideLabels=8B949E&dates=6E7681" alt="Contribution streak">

<br><br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/vibhorxpandey/vibhorxpandey/output/github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/vibhorxpandey/vibhorxpandey/output/github-snake.svg">
  <img src="https://raw.githubusercontent.com/vibhorxpandey/vibhorxpandey/output/github-snake-dark.svg" alt="contribution snake" width="100%">
</picture>

<sub>the repos are young; the substance isn't.</sub>

</div>

<br>

<img src="assets/divider.svg" width="100%" alt="">

## Find Me

<div align="center">

<a href="https://www.linkedin.com/in/vibhorpandeyx/"><img src="https://img.shields.io/badge/LinkedIn-0d1117?style=flat-square&logo=linkedin&logoColor=e3b341" alt="LinkedIn"></a>
<a href="https://x.com/vibhorxpandey"><img src="https://img.shields.io/badge/X-0d1117?style=flat-square&logo=x&logoColor=e3b341" alt="X"></a>
<a href="https://pypi.org/user/vibhorxpandey/"><img src="https://img.shields.io/badge/PyPI-0d1117?style=flat-square&logo=pypi&logoColor=e3b341" alt="PyPI"></a>
<a href="https://orcid.org/0009-0009-2810-6222"><img src="https://img.shields.io/badge/ORCID-0d1117?style=flat-square&logo=orcid&logoColor=e3b341" alt="ORCID"></a>
<a href="https://veilresearch.com"><img src="https://img.shields.io/badge/veilresearch.com-0d1117?style=flat-square" alt="Website"></a>
<a href="mailto:vibhorpandey09@gmail.com"><img src="https://img.shields.io/badge/Email-0d1117?style=flat-square&logo=gmail&logoColor=e3b341" alt="Email"></a>

<br><br>

<img src="assets/divider.svg" width="100%" alt="">

<sub><i>i like dogs and andrew ng.</i></sub>

<br><br>

<img src="https://komarev.com/ghpvc/?username=vibhorxpandey&style=flat-square&color=e3b341&label=visitors" alt="visitor count">

</div>
