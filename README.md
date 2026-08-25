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

**Databricks Intern** | **Jio Platforms Limited (JPL)**
> *June 2026 – Present*
- *Just got started! Currently setting up my environment, diving into the Databricks ecosystem, and drinking from the firehose. More updates coming soon as I start building out scalable data pipelines.*

**Technical Assistant** | **Official University E-Learning Portal (Vityarthi)**
> *Sept 2025 – Jan 2026*
- Spearheaded the end-to-end technical development of the university wide Linux course (CSE0002) for 4,100+ students in just first semester of the launch.
- Systematized 90 Bash and Shell automation scripts replicating real-world system administration workflows including log analysis and process monitoring.
- Delivered 100% of technical screen demonstrations capturing real-time execution of advanced Linux commands for asynchronous learning at scale.

**Research Assistant** | **Vellore Institute of Technology**
> *Jan 2025 – Present*

* **Research Focus 4: Causal Evaluation of EV Subsidies**: Evaluated the Maharashtra EV Policy 2025 via a macro-panel (N=9, T=54). Engineered an out-of-core DuckDB/Polars ETL pipeline and implemented Synthetic Difference-in-Differences (SDiD) in Python to quantify the "Demand Displacement Paradox."
* **Research Focus 3: Rondônia Fishbone Harmonizer**: Upscaled historical 30m Landsat imagery to 10m Sentinel-2 resolution to monitor Amazon deforestation. Built a PySTAC ETL pipeline and benchmarked 7 PyTorch architectures (EDSR, SwinIR, ESRGAN) for super-resolution.
* **Research Focus 2: ADAS & Neural Networks**: Co-authored a technical review mapping the shift to Deep Learning in autonomous driving. Quantified a 40% drop in trajectory prediction error (Kalman Filters to LSTM/GNNs) and proposed Neuro-Symbolic AI integrations for ISO 26262 compliance.
* **Research Focus 1: AV Perception & Integration**: Co-authored a published review on autonomous vehicle perception. Benchmarked classical filters vs. deep learning for LiDAR/vision fusion, and analyzed SLAM HD mapping & GAN dehazing for adverse weather.

**AI Intern** | **Jio Platforms Limited (JPL)**
> *May 2025 – June 2025*
- Constructed autonomous AI agents using LangChain and LLaMA 3, implementing a RAG pipeline over 500+ internal documents for precise information retrieval.
- Implemented dynamic SQL generation enabling structured querying across complex relational databases within the agent workflow.
- Launched a LangGraph-based multi-agent system that automated 90% of complaint routing and reduced operational latency by 20%.
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

