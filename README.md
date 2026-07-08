<h1 align="center">Hi, I'm Guangyu Wang 👋</h1>

<p align="center">
  Data Scientist / Statistician turning messy, real-world data into decisions —
  <b>experimentation &amp; causal inference</b>, <b>machine learning</b>, and production <b>LLM / agent systems</b>.
</p>

<p align="center">
  <a href="mailto:zjugeo@outlook.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://www.linkedin.com/in/guangyu-wang-data/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <img src="https://img.shields.io/badge/Location-Brooklyn,%20NY-555?style=flat&logo=googlemaps&logoColor=white" alt="Location"/>
</p>

---

### 👋 About

- 🔭 I build **end-to-end data systems** — from experiment design and metric definition through modeling, evaluation, and self-service tooling.
- 🧪 I like doing things *correctly*: clean randomization (SRM, covariate balance), quasi-experiments (difference-in-differences), variance reduction (**CUPED / ANCOVA**), and uplift / CATE targeting.
- 🤖 Recently building **LLM / agent systems** — LangChain / LangGraph agents, RAG, and MCP tools — with a rigorous approach to **evaluation** (LLM-as-judge validated against human labels, semantic-retrieval metrics).
- 📫 Reach me at **zjugeo@outlook.com**.

### 🚀 Featured projects

**[retail-loyalty-incrementality](https://github.com/guangyuw/retail-loyalty-incrementality)** — *incrementality experiment + uplift targeting*

- Aggregated a large transaction log into per-customer RFM & behavioral features in **SQL (DuckDB)**; analyzed repeat-purchase rate, cohort retention, and segmentation.
- Analyzed a randomized loyalty experiment end-to-end: validated randomization (SRM, covariate balance) and measured incremental lift with **CUPED / ANCOVA** variance reduction.
- Built an **uplift (CATE) ranking model** to target the most persuadable customers, with PSI drift monitoring and epsilon-randomized control for production readiness.

**[llm-eval-bug-triage](https://github.com/guangyuw/llm-eval-bug-triage)** — *semantic dedup + LLM extraction evaluation*

- Built **semantic duplicate retrieval** over a large bug corpus with hard-labeled pairs (sentence embeddings + vector search), evaluated with **hit@k / MRR** and stratified across themes.
- Engineered a **multi-agent LLM extraction pipeline** (retrieve context → extract → self-critique → retry) to improve field-extraction yield.
- Calibrated an **LLM-as-judge** evaluator against human labels with **Cohen's κ**, and validated embedding clusters against ground-truth duplicate pairs.

### 🧰 Tech I reach for

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![statsmodels](https://img.shields.io/badge/statsmodels-8CAAE6?style=flat)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat&logo=duckdb&logoColor=black)
![Spark](https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

<p align="center"><i>A/B testing · difference-in-differences · CUPED · uplift / CATE · RAG · MCP · LLM-as-judge · vector search (hit@k / MRR)</i></p>

### 📊 GitHub stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=guangyuw&show_icons=true&hide_border=true&theme=default" alt="GitHub stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=guangyuw&layout=compact&hide_border=true&theme=default" alt="Top languages"/>
</p>
