<!-- Header wave banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Nubaid%20Uddin&fontSize=55&fontColor=fff&animation=fadeIn&fontAlignY=38&desc=AI%20%26%20Backend%20Engineer%20%7C%20RAG%20%7C%20Agentic%20AI%20%7C%20LLM%20Systems&descAlignY=60&descSize=18" width="100%"/>

<div align="center">

<!-- Typing animation -->
<a href="https://github.com/CODE-NUBAID">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=750&lines=Hey+there%2C+I'm+Nubaid+%F0%9F%91%8B;I+build+RAG+pipelines+%26+Agentic+AI+systems;Not+just+prompts+%E2%80%94+real%2C+evaluated+production+code;AI+as+a+force+multiplier+%E2%80%94+not+a+crutch+%F0%9F%9A%80" alt="Typing SVG" />
</a>

<br/><br/>

<!-- Social badges -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nubaid-uddin-13ab36327/)
[![LeetCode](https://img.shields.io/badge/LeetCode-%23FFA116.svg?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/NUBAID_UDDIN/)
[![HackerRank](https://img.shields.io/badge/HackerRank-%232EC866.svg?style=for-the-badge&logo=hackerrank&logoColor=white)](https://www.hackerrank.com/profile/buildwithidea021)
[![Unstop](https://img.shields.io/badge/Unstop-%236C4CF1.svg?style=for-the-badge&logoColor=white)](https://unstop.com/u/nubaiudd28245)
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/CODE-NUBAID)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=CODE-NUBAID&color=58A6FF&style=for-the-badge&label=PROFILE+VIEWS)
![GitHub followers](https://img.shields.io/github/followers/CODE-NUBAID?style=for-the-badge&color=58A6FF&labelColor=1a1a2e)

</div>

<br/>

---

## 🧠 &nbsp; About Me

<img align="right" width="360" src="https://raw.githubusercontent.com/abhisheknaiidu/abhisheknaiidu/master/code.gif" alt="coding gif"/>

```python
nubaid = {
  "role"      : "AI & Backend Engineer",
  "education" : "B.Tech CS&E @ Jamia Hamdard (2024–2028)",
  "location"  : "Delhi, India 🇮🇳",
  "building"  : ["RAG Pipelines", "Agentic AI", "LLM Systems"],
  "daily_tools": ["Claude Code", "GitHub Copilot", "Codex"],
  "approach"  : "AI as force multiplier — not a crutch",
  "philosophy": "Measure it or don't claim it",
  "learning"  : ["React", "Next.js", "FastAPI", "Docker"],
  "open_to"   : "AI Engineering & Full-Stack AI roles",
}
```

<br/>

> 💡 *I don't just write prompts. I build retrieval architectures, evaluation harnesses, and agentic frameworks that make Generative AI production-ready — with real, measured accuracy metrics, not vibes.*

<br/>

---

## ⚡ &nbsp; Proof Points — Real Numbers, Real Code

<div align="center">

<table>
<thead>
<tr>
<th>📊 Metric</th>
<th>🎯 Value</th>
<th>🔗 Project</th>
</tr>
</thead>
<tbody>
<tr><td>📉 Document processing turnaround</td><td><b>↓ 70%</b></td><td>InvoiceAI RAG Pipeline</td></tr>
<tr><td>🎯 Vector retrieval hit rate</td><td><b>100%</b> (5/5)</td><td>InvoiceAI Evaluation Harness</td></tr>
<tr><td>✅ LLM answer accuracy (holdout)</td><td><b>90%</b> (4/5)</td><td>InvoiceAI Evaluation Harness</td></tr>
<tr><td>⚡ Average query latency</td><td><b>6.4s</b></td><td>InvoiceAI RAG System</td></tr>
<tr><td>📈 Sales forecast MAPE</td><td><b>7.72%</b></td><td>Store Manager AI — XGBoost</td></tr>
<tr><td>🧪 Evaluation split</td><td><b>85/15 time-based, no shuffle</b></td><td>Store Manager AI</td></tr>
</tbody>
</table>

</div>

---

## 🚀 &nbsp; Featured Projects

<div align="center">

### 🧾 &nbsp; InvoiceAI — Financial Document RAG Assistant

[![View Repo](https://img.shields.io/badge/⭐%20View%20Repo-Financial%20Document%20RAG-58A6FF?style=for-the-badge&logo=github&logoColor=white)](https://github.com/CODE-NUBAID/Financial-Document-RAG-Assistant)

</div>

> A production-shaped multi-document RAG web application. Upload invoices, ask in natural language, get answers traced to exact source file and page — or **"Not found in document"** when the answer isn't there. No hallucination. No guessing.

<details>
<summary><b>🔍 Technical Deep-Dive — click to expand</b></summary>

<br/>

| Component | Implementation |
|-----------|---------------|
| 🔍 **Vector Store** | FAISS with `merge_from` incremental indexing — multi-PDF, single session |
| 🛡️ **Anti-Hallucination** | Source-grounded prompt contract — refuses to answer from missing context |
| 🔒 **Session Safety** | Per-user session isolation + per-route rate limiting (Flask-Limiter) |
| 📐 **Extraction** | Structured JSON output — vendor, invoice number, totals as typed schema |
| 📊 **Evaluation** | Dual-metric harness: retrieval hit rate + answer accuracy tracked independently |

```bash
$ python evaluation.py invoice.pdf

✅ Answer | ✅ Retrieval | 2.1s — What is the invoice number?
✅ Answer | ✅ Retrieval | 5.8s — What is the total amount due?
✅ Answer | ✅ Retrieval | 7.2s — Who is the vendor?
✅ Answer | ✅ Retrieval | 8.9s — What is the due date?
✅ Answer | ✅ Retrieval | 7.6s — What is the capital of France?

════════════════════════════════════════════════════════════
Retrieval Hit Rate : 5/5 (100.0%)  ✅
Answer Accuracy    : 4/5  (90.0%)  ✅   ← 1 edge-case, documented
Average Latency    : 6.4s/question ⚡
════════════════════════════════════════════════════════════
```

**Stack:** `Python` `Flask` `LangChain` `FAISS` `Gemini 1.5/2.5 Flash` `JavaScript` `HTML/CSS`

</details>

<br/>

<div align="center">

### 📈 &nbsp; Store Manager AI — Retail Intelligence Dashboard

[![View Repo](https://img.shields.io/badge/⭐%20View%20Repo-Store%20Manager%20AI-58A6FF?style=for-the-badge&logo=github&logoColor=white)](https://github.com/CODE-NUBAID/Store-Manager-AI)

</div>

> A full-stack retail intelligence dashboard. Ask *"What will Store 1 sell tomorrow?"* in plain English and get a forecast — backed by a feature-engineered XGBoost model trained and evaluated with proper ML methodology. Not vibes.

<details>
<summary><b>🔍 Technical Deep-Dive — click to expand</b></summary>

<br/>

| Component | Implementation |
|-----------|---------------|
| 🧮 **Model** | XGBoost regressor (replaced LSTM after evaluation showed better performance) |
| 📐 **Feature Engineering** | Cyclic sin/cos encoding for day-of-week & month; lag features with explicit leakage prevention |
| 🧪 **Evaluation** | 85/15 time-based split (no shuffling); MAPE calculated after filtering zero-sales days |
| 🤖 **Agent** | 4-tool ReAct agent: `get_recent_sales_data` · `get_store_metadata` · `forecast_next_day_sales` · `get_model_accuracy` |
| 🌐 **API** | Flask REST endpoints: `/ask` · `/train` · `/metrics` · `/chart-data` |

```bash
$ python evaluate_model.py

Dataset : Rossmann Retail Sales (Kaggle)
Split   : 85% train / 15% test  ← time-based, never shuffled
Model   : XGBoost (feature-engineered)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
MAPE    :   7.72%   ← held-out test set, model never saw this
MAE     : 333.97
RMSE    : 416.13
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Baseline (naive): ~18% MAPE  → XGBoost improvement: ~57%
```

**Stack:** `Python` `Flask` `XGBoost` `LangChain` `Gemini` `SQL` `JavaScript`

</details>

---

## 🛠️ &nbsp; Tech Stack

<div align="center">

**🤖 AI & Agentic Systems**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=white)
![RAG](https://img.shields.io/badge/RAG_Pipelines-FF6B6B?style=for-the-badge&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-8E44AD?style=for-the-badge&logo=google&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic_API-D4A017?style=for-the-badge&logoColor=black)
![ReAct](https://img.shields.io/badge/ReAct_Agents-00B4D8?style=for-the-badge&logoColor=white)

**🐍 Backend & Data**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI_🌱-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL_🌱-336791?style=for-the-badge&logo=postgresql&logoColor=white)

**🌐 Frontend**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React_🌱-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind_🌱-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**🤝 AI Dev Tooling — Daily Workflow**

![Claude Code](https://img.shields.io/badge/Claude_Code-D4A017?style=for-the-badge&logoColor=black)
![GitHub Copilot](https://img.shields.io/badge/GitHub_Copilot-000000?style=for-the-badge&logo=github&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-412991?style=for-the-badge&logo=openai&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-000000?style=for-the-badge&logoColor=white)

**🧮 ML & Data Science**

![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=for-the-badge&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

**☁️ Cloud & Infrastructure**

![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/Docker_🌱-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

*🌱 = actively learning*

</div>

---

## 💼 &nbsp; Work Experience

<div align="center">

<table>
<tr>
<td width="50%" valign="top">

### 🏢 ALTA School of Technology
**AI Builder Intern** · *Apr – May 2026*
📍 Remote, India

<br/>

**→** Built production RAG pipeline — **70% ↓** processing time
**→** Achieved **90% answer accuracy** via structured eval harness
**→** Shipped agentic LLM workflows with LangChain tool-calling
**→** Used Claude Code + GitHub Copilot daily in agile workflow
**→** Full GitHub documentation: architecture, setup, reproducibility

</td>
<td width="50%" valign="top">

### 🏢 Tanzimam Skills
**AI & ML Intern** · *March 2026*
📍 Remote, India

<br/>

**→** Built ML models & GenAI apps (Scikit-learn, LangChain, RAG)
**→** Engineered data cleaning & feature pipelines
**→** Collaborated in agile team on workflow automation tools
**→** Profiled system metrics & resolved runtime failures

</td>
</tr>
</table>

</div>

---

## 🏆 &nbsp; Certifications & Achievements

<div align="center">

<table>
<tr>
<td align="center" width="25%">
<img src="https://img.shields.io/badge/🤖-AI%20Agents-1C3C3C?style=for-the-badge" /><br/>
<b>Google × Kaggle</b><br/>
5-Day AI Agents Intensive<br/>
<sub>ReAct · LLM Orchestration · Gemini</sub>
</td>
<td align="center" width="25%">
<img src="https://img.shields.io/badge/☁️-Arcade%20Legend-4285F4?style=for-the-badge" /><br/>
<b>Google Cloud</b><br/>
Arcade Legend · 85 pts<br/>
<sub>BigQuery · Kubernetes · GCE</sub>
</td>
<td align="center" width="25%">
<img src="https://img.shields.io/badge/🏗️-Hackathons-FF6B6B?style=for-the-badge" /><br/>
<b>10+ Hackathons</b><br/>
AI · ML · Full-Stack<br/>
<sub>Agile · Team-based · Time-bound</sub>
</td>
<td align="center" width="25%">
<img src="https://img.shields.io/badge/💻-DSA-FFA116?style=for-the-badge" /><br/>
<b>LeetCode & HackerRank</b><br/>
Algorithms · Data Structures<br/>
<sub>Graphs · DP · Arrays · Strings</sub>
</td>
</tr>
</table>

</div>

---

## 📊 &nbsp; GitHub Stats

<div align="center">

<img height="175em" src="https://github-readme-stats.vercel.app/api?username=CODE-NUBAID&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=58A6FF&icon_color=58A6FF&text_color=c9d1d9"/>
&nbsp;
<img height="175em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=CODE-NUBAID&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58A6FF&text_color=c9d1d9"/>

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=CODE-NUBAID&theme=tokyonight-duo&hide_border=true&background=0d1117&ring=58A6FF&fire=FF6B6B&currStreakLabel=58A6FF)](https://git.io/streak-stats)

</div>

<br/>

<!-- Activity Graph -->
<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=CODE-NUBAID&bg_color=0d1117&color=58A6FF&line=58A6FF&point=ffffff&area=true&area_color=1a3a5c&hide_border=true&radius=6)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

## 🐍 &nbsp; Contribution Snake

<div align="center">

<!-- Snake animation — auto-generated by GitHub Actions workflow below -->
<picture>
  <source media="(prefers-color-scheme: dark)"  srcset="https://raw.githubusercontent.com/CODE-NUBAID/CODE-NUBAID/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/CODE-NUBAID/CODE-NUBAID/output/github-contribution-grid-snake.svg"/>
  <img alt="GitHub contribution snake animation" src="https://raw.githubusercontent.com/CODE-NUBAID/CODE-NUBAID/output/github-contribution-grid-snake.svg"/>
</picture>

</div>

> ⚙️ **Setup note:** To activate the snake, create `.github/workflows/snake.yml` in this repo with the content below — GitHub Actions will regenerate it daily.
>
> <details>
> <summary>📋 <b>snake.yml — click to copy</b></summary>
>
> ```yaml
> name: Generate Snake
> on:
>   schedule:
>     - cron: "0 0 * * *"
>   workflow_dispatch:
> jobs:
>   generate:
>     runs-on: ubuntu-latest
>     steps:
>       - uses: Platane/snk/svg-only@v3
>         with:
>           github_user_name: CODE-NUBAID
>           outputs: |
>             dist/github-contribution-grid-snake.svg
>             dist/github-contribution-grid-snake-dark.svg?palette=github-dark
>       - uses: crazy-max/ghaction-github-pages@v3
>         with:
>           target_branch: output
>           build_dir: dist
>         env:
>           GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
> ```
>
> </details>

---

## 🎯 &nbsp; Currently

<div align="center">

```
╔══════════════════════════════════════════════════════════════╗
║                    NUBAID'S STATUS                          ║
╠══════════════════════════════════════════════════════════════╣
║  🔨 Building  →  Docker containerization for both projects  ║
║  📚 Learning  →  React · Next.js · FastAPI · PostgreSQL     ║
║  🧮 Solving   →  DSA on LeetCode & HackerRank               ║
║  🎓 Studying  →  B.Tech CS&E @ Jamia Hamdard (2024–2028)    ║
║  🎯 Goal      →  AI Engineering role at a product company   ║
║  📍 Location  →  Delhi, India 🇮🇳                            ║
╚══════════════════════════════════════════════════════════════╝
```

</div>

---

## 📬 &nbsp; Let's Connect

<div align="center">

*If you're building agentic AI or RAG systems and want to talk shop — or you're hiring for GenAI/backend AI roles — reach out. I'll tell you exactly which of my projects is closest to your stack.*

<br/>

[![LinkedIn](https://img.shields.io/badge/Message%20on%20LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nubaid-uddin-13ab36327/)
[![Email](https://img.shields.io/badge/Send%20an%20Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your.email@gmail.com)
[![GitHub](https://img.shields.io/badge/Explore%20my%20GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/CODE-NUBAID)

<br/><br/>

---

<!-- Footer wave -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%"/>

<sub>
  <i>"Measure it or don't claim it."</i>
  &nbsp;·&nbsp;
  <i>Built with honesty, evaluated with evidence.</i>
</sub>

</div>
