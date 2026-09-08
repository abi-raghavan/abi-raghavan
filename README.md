# Abi Raghavan

**Senior AI Engineer | Data Scientist | Machine Learning Engineer**

GenAI and RAG - Forecasting and Predictive Modelling - Production ML and MLOps

Bengaluru, India. 7+ years at IQVIA taking AI systems from prototype to production: models, APIs, CI/CD and cloud infrastructure.

[abiraghavan@outlook.com](mailto:abiraghavan@outlook.com) | [LinkedIn](https://www.linkedin.com/in/abiraghavan/)

## Projects

**[Agentic Stock Intelligence](https://github.com/abi-raghavan/agentic-stock-intelligence)** - Multi-agent equity research for NSE/BSE and US markets. A LangGraph workflow chains planning, research, hybrid RAG, risk synthesis and report verification, re-retrieving when claims fail verification. Live data falls back to labelled snapshots that cap reported confidence.
`Python` `LangGraph` `FastAPI` `Next.js` `BM25` `Docker`

**[AIRA](https://github.com/abi-raghavan/aira-core)** - Offline-first Android voice companion. Speech is processed on-device and never stored, phrases map to fixed scripts through deterministic rules, and a separate demo build cannot send SMS or place calls.
`Kotlin` `Android` `On-device speech` `Encrypted storage`

**[x-labs](https://github.com/abi-raghavan/x-labs)** - Three applied ML and GenAI labs:

- **[Experimentation Lab](https://x-lab-argon.streamlit.app)** - A/B testing with deterministic SHA-256 assignment, z and t-tests, and SRM plus power checks that run before lift is reported.
- **[Ride Incentive Recommender](https://ride-signal-argon.streamlit.app)** - Scores four incentive options against a no-incentive baseline, separating booking propensity from incentive uplift.
- **[RAG Support Assistant](https://github.com/abi-raghavan/x-labs/tree/main/rag_support_assistant)** - Dense and BM25 retrieval fused with RRF, cross-encoder rerank, inline citations, an explicit refusal path, and an evaluation harness.

Labs run on synthetic data; their metrics describe the evaluation workflow, not production outcomes.

## Work

- **GenAI / RAG:** Natural-language assistant over an enterprise analytics platform answering 20+ business KPIs in seconds. LangChain and FAISS, with a groundedness evaluation harness.
- **Forecasting:** Season-level risk model on 9 years of data, 20-30% accuracy improvement over baseline, replacing a 1-2 day manual review with automated daily alerts.
- **Platform:** Lead developer of a patient analytics platform deployed across 5+ countries, Elasticsearch backend for sub-second search.
- **Data engineering:** Migrated a legacy C++ system to PySpark and Databricks, cutting full project runtime from about a week to 1-4 hours.
- **Explainability:** SHAP-based risk models surfacing the specific drivers behind each score for business decision-makers.

## Skills

- **GenAI:** RAG architectures, agentic workflows, LangChain, LangGraph, FAISS, embeddings, semantic search, prompt engineering, evaluation
- **ML and stats:** Forecasting and time-series, risk and uplift modelling, ranking, XGBoost, anomaly detection, SHAP, A/B testing and experiment design
- **Data:** Python, PySpark, SQL, Databricks, Delta Lake, Elasticsearch, ETL/ELT design
- **Cloud and MLOps:** Azure, AWS, Docker, MLflow, CI/CD, FastAPI, Flask, model monitoring and versioning
- **Domain:** Healthcare and life sciences, sports analytics, commercial targeting analytics, regulated data

## Education

B.Tech, Electronics and Communication Engineering - NIT Calicut, 2015-2019
