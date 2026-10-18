<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/light.svg">
  <img alt="Khaled Lakhdher, AI Engineer: LLM agents, RAG and data pipelines" src="./assets/dark.svg" width="100%">
</picture>

<p align="center">
  <a href="https://github.com/KhaledLakhdher"><img src="https://img.shields.io/badge/GitHub-0F172A?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>
  <a href="https://www.linkedin.com/in/khaled-lakhdher"><img src="https://img.shields.io/badge/LinkedIn-0F172A?style=flat-square&logo=linkedin&logoColor=22D3EE" alt="LinkedIn"></a>
  <a href="https://khaled-lakhdher-portfolio.vercel.app"><img src="https://img.shields.io/badge/Portfolio-0F172A?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio"></a>
  <a href="mailto:ing.khaledlakhdher@gmail.com"><img src="https://img.shields.io/badge/Email-0F172A?style=flat-square&logo=gmail&logoColor=10B981" alt="Email"></a>
</p>

I'm an AI engineer who builds LLM systems that hold up in production: **multi-agent applications grounded in real data, data pipelines, and evaluation that measures what a model really does.** Engineering degree (Master's level) in AI & Data Science, currently AI Engineer at CTT.

**Open to:** AI / LLM / Data roles in France & Europe, or remote. · Python · LangGraph · FastAPI · PostgreSQL · Next.js

## Featured work

| Project | What it is | Highlights |
|---|---|---|
| [**DecisionFlow**](https://github.com/KhaledLakhdher/DecisionFlow) | AI business analyst: upload a CSV/Excel, get a star-schema warehouse, KPIs, forecasts and an agent fleet that answers questions | 2-min demo video · Postgres RLS tenant isolation enforced twice · LLM SQL sandboxed in 3 layers · numbers always computed from data, never by the model |
| [**Nexus AI**](https://github.com/KhaledLakhdher/nexus-ai) | Platform for *AI employees*: agents with identity, hierarchical memory and IAM-style permissions | Multi-agent orchestration · live WebSocket monitoring · provider-agnostic model gateway (Anthropic, Gemini, OpenRouter) |
| **Hotel Mind** *(built at CTT, private)* | Multilingual hotel search & booking assistant, in production | 9 LangChain/LangGraph agents · 32+ tools · 10 live SOAP services · deterministic critical steps · LangSmith tracing |
| [**LLM Code Review Evaluation**](https://github.com/KhaledLakhdher/llm-code-review-eval) | Benchmark of LLM code review on 500 real bugs (BugsInPy) with an LLM-as-judge | A single score overstates capability **~1.8×** (78% localisation vs 43% diagnosis) |
| [**Steam Player Forecaster (MLOps)**](https://github.com/KhaledLakhdher/steam-player-mlops) | End-to-end MLOps: next-day player-count forecasting | Model registry · drift monitoring · automatic champion/challenger retraining |
| [**Text-to-SQL with guardrails**](https://github.com/KhaledLakhdher/text-to-sql) | Correctness & safety harness for LLM-generated SQL | Measures how often and *how* the model is wrong · the answer can never be a `DROP TABLE` |

More: [Neapolis](https://github.com/KhaledLakhdher/neapolis) (AI operating platform for accounting firms) · [Freight rate prediction](https://github.com/KhaledLakhdher/freight-rate-prediction) (LightGBM, temporal validation)

## Stack

**AI & ML** — LangChain · LangGraph · RAG · PyTorch · Hugging Face · scikit-learn · LightGBM · LLM evaluation
**Backend & data** — Python · FastAPI · PostgreSQL / pgvector · DuckDB · Polars · Redis · SQL
**Frontend & ops** — Next.js · TypeScript · Docker · Git · AWS

## How I work

- **Ground the model in real data.** Agents answer from tool output, not from memory; critical steps stay deterministic.
- **Measure before claiming.** One headline metric hides failure modes — I build evaluation that separates them.
- **Design for the bad day.** Tenant isolation in the database, sandboxed LLM output, scoped permissions for every agent.
