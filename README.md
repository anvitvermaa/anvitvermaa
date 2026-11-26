<!--
**anvitvermaa/anvitvermaa** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->

<div align="center">
  <h1>Hi there, I'm Anvit 👋</h1>
  <p><em>Building autonomous agents, scaling AI infrastructure, and digging into causal machine learning.</em></p>

  [![Portfolio](https://img.shields.io/badge/Portfolio-anvitvermaa.github.io-000000?style=for-the-badge&logo=About.me&logoColor=white)](https://anvitvermaa.github.io)
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/anvit-verma)
  [![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:anvitvermaa@gmail.com)
</div>

---

I’m a Final Year Computer Science engineering student at Vellore Institute of Technology (VIT). For me, code is about building systems that reason and scale. Whether I'm building AI tools for Jio Platforms or teaching 4,100+ students Linux, I spend most of my time geeking out over **Multi-Agent Systems, RAG Pipelines, and Causal Machine Learning**.

### 💼 Experience

**Databricks Intern** | **Jio Platforms Limited** | Navi Mumbai, IN
> *Jun 2026 – Present*
- Developing a churn prediction pipeline on Databricks, cleaning **2.07M** raw records down to **1.17M** eligible users; compared **6+** churn-labeling methods with statistical tests, engineered **19 trend features**, and selected the final **49** via a 4-stage funnel.
- Benchmarking Lasso, Decision Tree, Random Forest, LightGBM, and XGBoost models with separate feature and label time windows to prevent leakage; currently achieving **0.90 ROC-AUC** and capturing **65% of churners in the top 10% of users** by risk score.
- Developed a PySpark/Spark SQL reconciliation engine that validates **2,300+ tables** across 14 business domains daily during a migration from SAP HANA and Oracle to Databricks, flagging missing or out-of-sync tables for remediation.
- Created a Databricks AI/BI dashboard tracking **1,100+ jobs** and **760K+ monthly runs**; used Quartz cron parsing and SQL date-spine analysis to expose an **8.2% schedule deviation** hidden behind a 99.9% on-time metric.

**Technical Assistant Intern** | **VITyarthi** | Bhopal, IN
> *Sep 2025 – Jan 2026*
- **Single-handedly** built the **university-wide** CSE0002 Linux System Administration course on VIT's official e-learning portal, writing every lecture and recording every coding walkthrough, and it has grown to **5,900+ enrollments**.
- Wrote **90+ Bash scripts** replicating real-world system administration workflows, providing the core hands-on demonstrations for the course.
- Earned a **4.7/5 rating from 741 reviews**, making it the **highest-rated course** on the portal.

**AI Intern** | **Jio Platforms Limited** | Navi Mumbai, IN
> *May 2025 – Jun 2025*
- Prototyped Telecom Optimizer, a **LangGraph** multi-agent network support assistant powered by **Llama 3** that diagnoses network issues reported by customers, checks the expected restoration time, and replies in natural language.
- Integrated context-aware RAG, tested on **500+** internal documents with Llama 3 embeddings, **Chroma**, and conversation memory, plus **LangChain Text-to-SQL** to query outage and restoration data in **MySQL** via parameterized queries.

**Research Assistant** | **Vellore Institute of Technology** | Bhopal, IN
> *Nov 2024 – Apr 2025*
- Co-authored a **published research paper** reviewing **35 peer-reviewed papers** on the evolution of neural networks in autonomous driving and advanced driver-assistance systems (ADAS).
- Contributed to a faculty-led study on Amazon deforestation in Rondônia, Brazil, comparing 30 m Landsat with 10 m Sentinel-2 satellite imagery, where narrow logging roads invisible at Landsat's resolution become detectable.
<br>

### 🛠️ Featured Projects

**[GitHub Repo Analyst AI](https://github.com/anvitvermaa/Repo_Analyst_AI)** | **Autonomous Agents**

> Fully automated complex security audits directly within an interactive Windows XP OS simulation

* Architected an autonomous LangGraph orchestration layer with LLaMA 3 agents and a ChromaDB RAG pipeline for conversational codebase analysis.
* Engineered an interactive React frontend with a flawless Windows XP-themed desktop experience.
* Completely automated complex three-stage security audits (SAST & dependencies) directly within the OS simulation.
* Built with LangGraph, LLaMA 3, ChromaDB, React (Vite), and Framer Motion

<br>

**[Causal Evaluation of Maharashtra EV Policy](https://github.com/anvitvermaa/Casual-Evaluation-of-EV)** | **Causal Inference & Data Engineering**


**Project Context:** A rigorous quasi-experimental causal evaluation of the Maharashtra EV Subsidy Policy 2025 across a balanced macro-state panel of top vehicle-registering Indian states ($N=16$, $T=54$ months).

* **Isolated True Policy Impact:** Mathematically demonstrated a statistically null short-run demand signal (ATT = $+0.0347$ pp, $p > 0.05$) for the Maharashtra EV subsidy by rigorously correcting the outcome variable to isolate Battery Electric Vehicles (BEVs), eliminating confounding from a simultaneous national surge in Strong Hybrids.
* **High-Performance Data Engineering:** Engineered an out-of-core ETL pipeline utilizing a Python AJAX scraper, DuckDB for in-memory SQL normalization, and Polars to lazily ingest, transform, and evaluate nearly 34 million API-sourced vehicle registrations across 54 months of macroscopic Vahan data.
* **Advanced Causal Architecture:** Pioneered a rigorous dual-specification causal architecture utilizing the Synthetic Difference-in-Differences (SDiD) estimator with L2 Ridge Regularization to construct unconfounded baseline counterfactuals.
* **Mathematical Robustness:** Designed advanced spatial robustness checks ("Donut Hole" specifications) and placebo bootstrap permutation tests to mathematically validate SUTVA compliance against cross-border arbitrage spillovers.
<br>

**[Tastelytics](https://github.com/anvitvermaa/tastelytics)** | **Serverless Music Review Platform**

**Project Context:** A highly scalable, serverless Single Page Application (SPA) and monolithic backend orchestrating real-time music discovery, community reviews, and social feeds. Users can search for tracks via the Spotify API, write and share reviews, and follow other users' activities through sub-second social feeds.

* **Serverless Monolithic Architecture:** Engineered a "Fat Lambda" containerized backend utilizing AWS API Gateway and Dockerized Python runtimes, achieving sub-300ms social feed query latencies via optimized DynamoDB Global Secondary Indexes (GSI).
* **Hardened Security Posture:** Spearheaded a comprehensive security audit mitigating 7 critical vulnerabilities—including Insecure Direct Object References (IDOR), Self-XSS, and CORS wildcards—and hardened OAuth flows natively through Amazon Cognito.
* **Native Cloud Administration:** Eliminated external attack surfaces by deprecating insecure web-based admin dashboards in favor of purely native AWS console management (DynamoDB/Cognito) for all privileged administrative operations.
* **Automated Infrastructure:** Deployed a globally distributed React (Vite) frontend via AWS S3 and CloudFront, fully orchestrating the zero-downtime CI/CD pipeline and infrastructure-as-code leveraging AWS CDK.
* **Built with:** React, AWS (Lambda, DynamoDB, API Gateway, Cognito, CDK, CloudFront, S3), Docker, Spotify API
<br>
