<div align="center">

<!-- Typing animation header -->
<a href="https://github.com/CODE-NUBAID">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=2E86C1&center=true&vCenter=true&width=700&lines=Hey%2C+I'm+Nubaid+UDDIN+%F0%9F%91%8B;AI+%26+Backend+Engineer;I+build+RAG+%26+Agentic+AI+Systems;Not+just+prompts+%E2%80%94+real+pipelines." alt="Typing SVG" />
</a>

<br/>

<!-- Social badges -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nubaid-uddin-13ab36327/)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/NUBAID_UDDIN/)
[![HackerRank](https://img.shields.io/badge/HackerRank-2EC866?style=for-the-badge&logo=hackerrank&logoColor=white)](https://www.hackerrank.com/profile/buildwithidea021)
[![Unstop](https://img.shields.io/badge/Unstop-6C4CF1?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iMTAiLz48L3N2Zz4=&logoColor=white)](https://unstop.com/u/nubaiudd28245)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/CODE-NUBAID)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=CODE-NUBAID&color=2E86C1&style=for-the-badge&label=PROFILE+VIEWS)

</div>

---

## 🧠 About Me

```python
nubaid = {
    "role"      : "AI & Backend Engineer",
    "education" : "B.Tech CS&E @ Jamia Hamdard University (2024–2028)",
    "location"  : "Delhi, India 🇮🇳",
    "focus"     : ["RAG Pipelines", "Agentic AI Frameworks", "LLM Integration"],
    "tools"     : ["Claude Code", "GitHub Copilot", "Codex", "Cursor"],
    "approach"  : "AI as a force multiplier — not a crutch",
    "currently" : "Building production-shaped GenAI systems & levelling up in DSA",
}
```

> *I don't just write prompts. I build the retrieval architectures, evaluation harnesses, and agentic frameworks that make Generative AI production-ready.*

---

## ⚡ Proof Points

<div align="center">

| Metric | Value | Project |
|--------|-------|---------|
| 📉 Document turnaround reduction | **70%** | InvoiceAI RAG Pipeline |
| 🎯 Retrieval hit rate | **100%** | InvoiceAI Evaluation Harness |
| ✅ Answer accuracy (holdout eval) | **90%** | InvoiceAI Evaluation Harness |
| ⚡ Avg query latency | **6.4s** | InvoiceAI RAG System |
| 📊 Sales forecast MAPE | **7.72%** | Store Manager AI (XGBoost) |
| 🔢 Evaluation methodology | **85/15 time-based split, zero-sales day filtered** | Store Manager AI |

</div>

---

## 🚀 Featured Projects

<div align="center">

### 🧾 InvoiceAI — Financial Document RAG Assistant

[![Repo](https://img.shields.io/badge/GitHub-InvoiceAI-2E86C1?style=for-the-badge&logo=github)](https://github.com/CODE-NUBAID/Financial-Document-RAG-Assistant)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=chainlink&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E44AD?style=flat-square&logo=google&logoColor=white)

</div>

**What it does:** A production-shaped multi-document RAG web application. Upload invoices, ask questions in natural language, get answers traced to exact source file and page — or "Not found in document" when the answer isn't there. No hallucination.

**What makes it real:**
- 🔍 **FAISS incremental indexing** (`merge_from`) — multiple PDFs, one session, persistent vector index
- 🛡️ **Anti-hallucination prompt contract** — refuses to guess when context is absent
- 🔒 **Per-user session isolation** + per-route rate limiting (Flask-Limiter)
- 📐 **Structured JSON extraction** — vendor, invoice number, totals as typed output
- 📊 **Dual-metric evaluation harness** — retrieval hit rate and answer accuracy tracked independently

```
Retrieval Hit Rate : 5/5  (100%)   ✅
Answer Accuracy    : 4/5  ( 90%)   ✅  (1 edge-case failure, documented)
Avg Query Latency  : 6.4s/question ⚡
```

---

<div align="center">

### 📈 Store Manager AI — Retail Intelligence Dashboard

[![Repo](https://img.shields.io/badge/GitHub-StoreManagerAI-2E86C1?style=for-the-badge&logo=github)](https://github.com/CODE-NUBAID/Store-Manager-AI)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=flat-square&logo=xgboost&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=chainlink&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

</div>

**What it does:** A full-stack retail intelligence dashboard. Ask "What will Store 1 sell tomorrow?" in plain English and get a forecast — backed by a feature-engineered XGBoost model, not vibes.

**What makes it real:**
- 📐 **Feature engineering done right** — cyclic sin/cos encoding for day-of-week & month; lag features with explicit leakage prevention
- 📊 **Honest evaluation** — 85/15 time-based train/test split (no shuffling); MAPE calculated after filtering zero-sales days
- 🤖 **4-tool ReAct agent** (LangChain): `get_recent_sales_data` · `get_store_metadata` · `forecast_next_day_sales` · `get_model_accuracy`
- 🌐 **REST API backend**: `/ask` · `/train` · `/metrics` · `/chart-data`

```
Model   : XGBoost (replaced LSTM baseline after proper evaluation)
MAPE    : 7.72%   ← on held-out test set, model never saw this data
MAE     : 333.97
RMSE    : 416.13
Dataset : Rossmann Retail Sales (Kaggle)
```

---

## 🛠️ Tech Stack

<div align="center">

### 🤖 AI & Agentic Systems
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-FF6B6B?style=for-the-badge&logo=semantic-web&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-8E44AD?style=for-the-badge&logo=google&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic_API-D4A017?style=for-the-badge&logo=anthropic&logoColor=black)

### 🐍 Backend & Data
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI_(learning)-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL_(learning)-336791?style=for-the-badge&logo=postgresql&logoColor=white)

### 🌐 Frontend
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React_(learning)-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind_(learning)-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

### 🤝 AI Dev Tooling — Used Daily
![Claude Code](https://img.shields.io/badge/Claude_Code-D4A017?style=for-the-badge&logo=anthropic&logoColor=black)
![GitHub Copilot](https://img.shields.io/badge/GitHub_Copilot-000000?style=for-the-badge&logo=github&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-412991?style=for-the-badge&logo=openai&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-000000?style=for-the-badge&logo=cursor&logoColor=white)

### 🧮 ML & Data Science
![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=for-the-badge)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

### ☁️ Cloud & Tools
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker_(learning)-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

</div>

---

## 💼 Experience

<table>
<tr>
<td width="50%">

**🏢 AI Builder Intern**
**ALTA School of Technology** · Apr–May 2026
*Remote, India*

- Built production RAG pipeline (70% ↓ processing time)
- Achieved 90% answer accuracy via structured eval harness
- Used Claude Code & GitHub Copilot in daily agile workflow
- Documented architecture diagrams, setup guides on GitHub

</td>
<td width="50%">

**🏢 AI & ML Intern**
**Tanzimam Skills** · Mar 2026
*Remote, India*

- Built ML models & GenAI applications with Scikit-learn, LangChain, RAG
- Engineered data cleaning & feature pipelines
- Collaborated in agile team on workflow automation tools

</td>
</tr>
</table>

---

## 🏆 Certifications & Achievements

<div align="center">

| 🏅 Achievement | Details |
|---|---|
| 🤖 **Google × Kaggle AI Agents Intensive** | ReAct agents, LLM orchestration, Gemini tool-calling |
| ☁️ **Google Cloud Arcade Legend** | 85 pts · Season 1 · BigQuery · Kubernetes · Compute Engine |
| 🏗️ **10+ Hackathons** | AI, ML, Full-Stack — agile, team-based environments |
| 💻 **LeetCode & HackerRank** | Arrays, Strings, Graph Theory, Dynamic Programming |

</div>

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=CODE-NUBAID&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=CODE-NUBAID&layout=compact&langs_count=8&theme=tokyonight&hide_border=true"/>

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=CODE-NUBAID&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

</div>

---

## 🎯 Currently

```
🔨 Building  → Adding Docker containerization to InvoiceAI & Store Manager AI
📚 Learning  → React, Next.js, FastAPI, PostgreSQL — frontend depth in progress
🧮 Solving   → DSA on LeetCode & HackerRank (arrays, graphs, dynamic programming)
🎓 Studying  → B.Tech CS&E @ Jamia Hamdard University (2024–2028)
🎯 Goal      → ML/AI Engineering or Full-Stack AI role at a product company
```

---

## 📬 Let's Connect

<div align="center">

If you're building agentic AI or RAG systems and want to talk shop, or you're hiring for GenAI/backend AI roles — reach out. I'll tell you exactly which of my projects is closest to your stack.

<br/>

[![LinkedIn](https://img.shields.io/badge/Message_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nubaid-uddin-13ab36327/)
[![Email](https://img.shields.io/badge/Send_an_Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your.email@gmail.com)
[![GitHub](https://img.shields.io/badge/Explore_my_GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/CODE-NUBAID)

<br/>

---

<img src="https://capsule-render.vercel.app/api?type=waving&color=2E86C1&height=100&section=footer&text=&fontSize=0" />

*"I don't just write prompts — I build the pipelines, evaluation harnesses, and agentic frameworks that make GenAI production-ready."*

</div>
