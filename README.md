<h1 align="center">Aditya Gupta</h1>
<h3 align="center">AI Engineer building agentic systems that plan, use tools, and execute real workflows</h3>

<p align="center">
  <a href="https://github.com/adi9336"><img src="https://img.shields.io/badge/GitHub-adi9336-181717?style=for-the-badge&logo=github" alt="GitHub" /></a>
  <a href="https://www.linkedin.com/in/aditya-gupta-7a0546203/"><img src="https://img.shields.io/badge/LinkedIn-Aditya%20Gupta-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn" /></a>
  <a href="https://x.com/aditya__9336"><img src="https://img.shields.io/badge/X-aditya__9336-000000?style=for-the-badge&logo=x" alt="X" /></a>
</p>

<p align="center">
  <b>AI Engineer</b> • <b>Full-Stack Builder</b> • <b>Workflow Automator</b><br />
  Designing intelligence that <i>reasons</i>, <i>acts</i>, <i>streams progress</i>, and <i>scales</i>.
</p>

---

## About Me

I build agentic software systems where LLMs do more than generate text. My work focuses on systems that can understand a request, plan the next steps, call tools, run workflows, validate outputs, and expose the whole process through clean product interfaces.

I care about production-grade AI: modular architecture, real data paths, streaming backends, evaluation loops, observability, and systems that stay useful after the demo is over.

```text
Agent design      Graph-based orchestration, tool use, memory, validation
Backend systems   FastAPI services, async execution, workers, queues, APIs
Data workflows    RAG pipelines, retrieval, enrichment, scoring, analytics
Product layer     React, TypeScript, Tailwind, Streamlit, dashboards
```

---

## Core Stack

<table>
  <tr>
    <td><b>AI Engineering</b></td>
    <td>LangChain · LangGraph · OpenAI API · RAG · Tool Calling · Vector Stores</td>
  </tr>
  <tr>
    <td><b>Backend</b></td>
    <td>Python · FastAPI · PostgreSQL · SQLite · REST APIs · Webhooks</td>
  </tr>
  <tr>
    <td><b>Frontend</b></td>
    <td>React · TypeScript · Tailwind CSS · Streamlit · Plotly</td>
  </tr>
  <tr>
    <td><b>Data & Orchestration</b></td>
    <td>Redis · Celery · Async Workers · Event Streaming · Background Jobs</td>
  </tr>
  <tr>
    <td><b>Infra & DevOps</b></td>
    <td>Docker · GitHub Actions · API-first Architecture · Service Observability</td>
  </tr>
</table>

---

## Flagship Projects

### POSEIDON — Multi-Agent Oceanographic Analysis

<a href="https://github.com/adi9336/POSEIDON"><b>Repository</b></a>

POSEIDON is a multi-agent scientific analysis system for Argo float oceanographic data. It turns natural language questions into structured data retrieval, analytical workflows, validation checks, and visual outputs.

**Agent graph**

```text
query_understanding -> data_retrieval -> analysis -> validation
```

**What it does**

- Parses natural language into location, depth, time range, and variable constraints
- Ingests oceanographic data through ERDDAP and stores analysis-ready data in SQLite
- Runs validation with confidence scoring, time-window checks, and outlier-rate detection
- Streams progress events for long-running workflows
- Provides a Streamlit control panel with diagnostics cards and Plotly visualizations
- Exposes API endpoints for structured execution and real-time progress updates

**Core idea:** agent orchestration for scientific data pipelines.

---

### LeadFlow — AI B2B Lead Intelligence Engine

<a href="https://github.com/adi9336/LeadFlowAI"><b>Repository</b></a>

LeadFlow is a production-style lead intelligence backend for extracting, enriching, scoring, caching, and orchestrating B2B outreach workflows.

**Architecture**

```text
FastAPI -> LangChain/OpenAI -> PostgreSQL/SQLite -> Redis/Celery -> Campaign workflows
```

**What it does**

- Extracts leads from LinkedIn-style sources, business directories, and job boards
- Enriches companies with AI-generated intelligence, pain points, and lead scores
- Uses a persistent SQLite lead cache for deduplication and query reuse
- Runs in strict real-data mode with no mock fallback path
- Uses async workers for scalable enrichment and campaign execution
- Ships interactive FastAPI docs for testing the pipeline end to end

**Core idea:** AI-powered data pipelines with distributed task execution.

---

## Engineering Principles

- Design for tool use, not just text output
- Prefer graphs over chains for complex reasoning
- Separate LLM reasoning from business logic
- Treat validation, retries, and observability as first-class system concerns
- Build API-first backends that agents and humans can both operate
- Optimize for real users, real data, and workflows that can survive production friction

---

## Currently Exploring

- Long-running agents and background execution models
- Memory architectures across vector, relational, and episodic stores
- Evaluation harnesses for agent reliability
- Observability patterns for LLM systems
- MLOps and deployment workflows for agentic products

---

## GitHub Snapshot

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=adi9336&label=Profile%20views&color=38bdf8&style=flat" alt="Profile views" />
  <img src="https://img.shields.io/github/followers/adi9336?label=Followers&style=flat&color=22c55e" alt="GitHub followers" />
  <img src="https://img.shields.io/github/stars/adi9336?affiliations=OWNER%2CCOLLABORATOR&label=Stars&style=flat&color=facc15" alt="GitHub stars" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=adi9336&theme=tokyonight&no-frame=true&no-bg=true&margin-w=8&row=1&column=6" alt="GitHub trophies" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=adi9336&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github&include_all_commits=true" height="165" alt="Aditya's GitHub stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com?user=adi9336&theme=tokyonight&hide_border=true" height="165" alt="Aditya's GitHub streak" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=adi9336&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" height="165" alt="Most used languages" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=adi9336&theme=tokyo-night&hide_border=true&area=true" alt="Contribution activity graph" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake.svg" alt="Contribution snake animation" />
</p>

---

## Let’s Collaborate

I’m open to working on:

- AI agent infrastructure
- Full-stack AI products
- RAG and workflow automation systems
- Research-to-production LLM applications
- Hackathons, experiments, and fast-moving prototypes

<p align="center">
  <a href="https://www.linkedin.com/in/aditya-gupta-7a0546203/">LinkedIn</a> ·
  <a href="https://github.com/adi9336">GitHub</a> ·
  <a href="https://x.com/aditya__9336">Twitter/X</a> ·
  <a href="https://www.instagram.com/aditya__9336">Instagram</a>
</p>

---

<h3 align="center">Building agents that do not just answer. They execute.</h3>
