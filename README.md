<div align="center">
<!-- HEADER BANNER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0D1117&height=120&section=header&text=&fontSize=0" width="100%"/>

<!-- NAME + ROLE -->
<h1>
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=378ADD&center=true&vCenter=true&width=600&lines=Pankaj+Baid;AI+%2B+Backend+Engineer;Building+AI+that+actually+ships." alt="Typing SVG" />
</h1>

<!-- SUBTITLE -->
<p>
  <img src="https://img.shields.io/badge/LLMs%20%C2%B7%20RAG%20%C2%B7%20Agentic%20AI%20%C2%B7%20FastAPI%20%C2%B7%20Node.js-0D1117?style=flat-square&labelColor=0D1117&color=378ADD" />
</p>

<!-- BADGES ROW 1 -->
<p>
  <a href="https://linkedin.com/in/pankaj-baid">
    <img src="https://img.shields.io/badge/LinkedIn-Pankaj%20Baid-0A66C2?style=flat-square&logo=linkedin&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://leetcode.com/u/baidpankaj567">
    <img src="https://img.shields.io/badge/LeetCode-500%2B%20Solved-FFA116?style=flat-square&logo=leetcode&logoColor=black" />
  </a>
  &nbsp;
  <img src="https://img.shields.io/badge/B.Tech%20CS%20%2B%20AI-CGPA%3A%209.043-22C55E?style=flat-square&logo=academia&logoColor=white" />
  &nbsp;
  <img src="https://img.shields.io/badge/IIT%20Roorkee%20Hackathon-Runner--Up%20🏆-EF9F27?style=flat-square" />
</p>

<!-- VISITOR COUNTER -->
<p>
  <img src="https://komarev.com/ghpvc/?username=pankajbaid567&style=flat-square&color=378ADD&label=Profile+Views" />
  &nbsp;
  <a href="https://github.com/pankajbaid567?tab=followers">
    <img src="https://img.shields.io/github/followers/pankajbaid567?style=flat-square&color=378ADD&label=Followers" />
  </a>
</p>

</div>

---

## `> whoami`

```python
pankaj = {
    "role":        "AI + Backend Engineer",
    "building":    "Manthan AI — 13-project production AI ecosystem",
    "stack":       ["LangGraph", "FastAPI", "Node.js", "Docker", "PostgreSQL", "Redis"],
    "expertise":   ["RAG Systems", "Agentic AI", "LLM Fine-Tuning", "AI Evaluation"],
    "location":    "Delhi NCR, India",
    "open_to":     "AI / GenAI Internships 2027 · Remote · OSS Collaboration",
    "philosophy":  "If it can't be deployed, monitored, evaluated, and scaled — it isn't finished.",
}
```

> Most AI engineers understand models.
> The rare ones can **build the complete system around the model** — retrieval, orchestration, evaluation, infrastructure, and deployment.
> That's where I operate.

---

## `> ls -la ~/projects` &nbsp; ⚡ Featured Work

### 🔬 ScholarForge AI &nbsp; — &nbsp; Production RAG System

> AI-powered research and knowledge intelligence platform with enterprise-grade retrieval architecture.

| Metric | Result |
|--------|--------|
| RAG Faithfulness (Ragas) | **87%+** |
| Answer Relevance | **85%+** |
| P95 Retrieval Latency | **< 1.5s** |
| Documents Indexed | **10K+** |

```
Architecture: Hybrid BM25 + Dense Retrieval → Cross-Encoder Reranking → LLM Generation → Ragas Eval Pipeline
```

**Stack:**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=chainlink&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-0D1117?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

**Key decisions:**
- Hybrid BM25 + dense retrieval over naive vector search — keyword recall matters for domain-specific corpora
- Ragas evaluation pipeline integrated into CI/CD — faithfulness gates every deployment
- FastAPI with SSE streaming, JWT auth, rate limiting — not Streamlit

---

### 🤖 Multi-Agent Research Assistant &nbsp; — &nbsp; LangGraph Orchestration

> Autonomous research system with stateful multi-step reasoning, tool orchestration, and memory-aware workflows.

```
Agent Loop: Plan → Tool Call → Error Recovery → State Update → Memory Write → Next Step
```

**Capabilities:**
- Multi-step reasoning with persistent state graphs (LangGraph)
- Tool registry: web search, code execution, retrieval, structured output
- Short-term context + long-term vector memory
- Streaming FastAPI backend with real-time agent thought visibility
- Full Docker + GitHub Actions CI/CD pipeline

**Stack:**
![LangGraph](https://img.shields.io/badge/LangGraph-0D1117?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

---

### 🧠 Domain-Adapted Fine-Tuned LLM &nbsp; — &nbsp; LoRA on Phi-3-mini

> End-to-end fine-tuning pipeline: data curation → LoRA training → quantization → production serving.

| Stage | Detail |
|-------|--------|
| Base Model | Phi-3-mini-4k (Microsoft) |
| Fine-Tuning | LoRA via PEFT — 1% compute, 90% performance |
| Dataset | 1000+ curated domain examples |
| Quantization | GGUF via llama.cpp |
| Serving | Ollama + FastAPI endpoint |
| Hosting | HuggingFace Hub |

**Stack:**
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

### 🔁 MLOps Pipeline with Drift Detection

> Production ML monitoring system with automated drift detection, retraining triggers, and experiment tracking.

```
Data → FastAPI Endpoint → MLflow Tracking → Evidently AI Drift → GitHub Actions Retrain → Model Registry
```

**Stack:**
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

## `> cat tech_stack.json`

<details>
<summary><b>🤖 AI / GenAI Engineering</b></summary>
<br>

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=chainlink&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-0D1117?style=flat-square&logo=python&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=llama&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6C37?style=flat-square)
![Ragas](https://img.shields.io/badge/Ragas%20Eval-8A2BE2?style=flat-square)
![LoRA](https://img.shields.io/badge/LoRA%20%2F%20PEFT-FF4B4B?style=flat-square)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)

</details>

<details>
<summary><b>⚙️ Backend Engineering</b></summary>
<br>

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![REST](https://img.shields.io/badge/REST%20APIs-FF6C37?style=flat-square)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square)

</details>

<details>
<summary><b>🏗️ Infrastructure & DevOps</b></summary>
<br>

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-0D1117?style=flat-square&logo=githubactions&logoColor=white)
![AWS](https://img.shields.io/badge/AWS%20(S3%20%2B%20Lambda)-FF9900?style=flat-square&logo=amazonaws&logoColor=white)

</details>

---

## `> git log --oneline` &nbsp; GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=pankajbaid567&show_icons=true&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=378ADD&icon_color=378ADD&text_color=C9D1D9&rank_icon=github&include_all_commits=true" />
&nbsp;
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=pankajbaid567&layout=compact&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=378ADD&text_color=C9D1D9&langs_count=8" />

</div>

<div align="center">

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=pankajbaid567&bg_color=0D1117&color=378ADD&line=378ADD&point=FFFFFF&area=true&hide_border=true" />

</div>

---

## `> cat achievements.log`

| Signal | Detail |
|--------|--------|
| 🏆 | **IIT Roorkee Cognizance AI Hackathon** — Runner-Up (AI Track, competing vs IIT/NIT teams) |
| 🚀 | **Founding Team** @ in.culcate — EdTech startup, backend architecture, REST APIs, 10K+ users |
| 🌍 | **Open Source Contributor** — PRs merged to major AI frameworks |
| 💻 | **500+ DSA Problems** solved (LeetCode, patterns-focused) |
| 🎓 | **B.Tech CS + AI** @ Rishihood University (NST) — CGPA: **9.043** |
| ⚡ | **Manthan AI** — 13-project production AI ecosystem (3 ultra-elite) |

---

## `> ls manthan_ai/` &nbsp; 🚀 The Manthan AI Ecosystem

> A unified platform of 13 interconnected AI projects — not a portfolio of demos, but a production-grade AI engineering ecosystem. Each project exposes a FastAPI layer, is containerized with Docker, and feeds signal into the next.

```
manthan-ai/
├── scholarforge-ai/          ← Production RAG + Evaluation  [SHIPPED]
├── multi-agent-research/     ← LangGraph Agentic System     [SHIPPED]
├── domain-llm-pipeline/      ← LoRA Fine-Tune + Serving     [SHIPPED]
├── mlops-drift-pipeline/     ← MLflow + Evidently AI        [SHIPPED]
├── ai-saas-platform/         ← Real users, full-stack AI    [IN PROGRESS]
├── llm-eval-framework/       ← Custom DeepEval harness      [PLANNED]
├── code-review-agent/        ← LangGraph + GitHub API       [PLANNED]
└── ...6 more                 ← Evolution Engine             [ROADMAP]
```

**The evolution engine:** Each project feeds a critic-agent feedback loop — prompts evolve, architectures refine, and evaluation scores compound across the ecosystem.

---

## `> cat /etc/experience`

### Founding Team Member — in.culcate &nbsp; `Sep 2024 – Mar 2026`

EdTech startup · Delhi · Full-time

- Joined as one of the earliest engineering members; shaped both product and backend architecture from the ground up
- Designed and built REST API infrastructure with **Node.js + Express**; integrated MongoDB for content management at scale
- Built and shipped end-to-end features: user authentication, content delivery pipelines, internal CMS
- Developed the initial **React Native mobile application MVP**
- Contributed to system design decisions targeting **10K+ student users**
- Worked directly with founders — product thinking, cross-functional execution, zero-to-one delivery

`Node.js` `Express` `MongoDB` `React Native` `REST APIs` `System Design`

---

## `> ping connections`

<div align="center">

<a href="https://linkedin.com/in/pankaj-baid">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
&nbsp;
<a href="https://github.com/pankajbaid567">
  <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>
&nbsp;
<a href="https://leetcode.com/u/baidpankaj567">
  <img src="https://img.shields.io/badge/LeetCode-Profile-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" />
</a>

<br><br>

**Open to:** AI/GenAI internship opportunities · OSS collaboration · Referrals · Technical conversations

</div>

---

<div align="center">

```
"If it can't be deployed, monitored, evaluated, and scaled — it isn't finished."
```

<img src="https://capsule-render.vercel.app/api?type=waving&color=0D1117&height=80&section=footer" width="100%"/>

</div>
