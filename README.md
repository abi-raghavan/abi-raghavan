# Abi Raghavan

**Senior AI Engineer | Data Scientist | Machine Learning Engineer**

Generative AI and RAG - Forecasting and Predictive Modelling - Production ML and MLOps

Based in Bengaluru, India. 7+ years at IQVIA (Fortune 500 healthcare data and analytics) delivering AI systems from prototype to production, including models, APIs, CI/CD and cloud infrastructure.

## Selected Work

| Area | Outcome |
| --- | --- |
| Generative AI / RAG | Natural-language assistant over an enterprise analytics platform, answering 20+ business KPIs in seconds; built with LangChain and FAISS, with a groundedness evaluation harness. |
| Forecasting | Season-level risk model trained on 9 years of data; 20-30% accuracy improvement over baseline, replacing a 1-2 day manual review with automated daily alerts. |
| Platform Engineering | Lead developer of a patient analytics platform deployed across 5+ countries, with an Elasticsearch backend for sub-second search. |
| Data Engineering | Migrated a legacy C++ system to PySpark and Databricks, reducing full project runtime from approximately one week to 1-4 hours. |
| Explainability | SHAP-based risk models surfacing the specific drivers behind each score for business decision-makers. |

## Technical Skills

- **Generative AI:** RAG architectures, LLM application development, agentic workflows, LangChain, LangGraph, prompt engineering, vector search (FAISS), embeddings, semantic search
- **Machine Learning:** Forecasting and time-series, predictive and risk modelling, ranking and scoring, XGBoost, deep learning, anomaly detection, SHAP
- **Statistics:** A/B testing, experiment design, hypothesis testing, uplift modelling, segmentation
- **Data Engineering:** PySpark, Python, SQL, Databricks, Delta Lake, Elasticsearch, ETL/ELT pipeline design
- **Cloud and MLOps:** Azure, AWS, Docker, MLflow, CI/CD, REST APIs (FastAPI, Flask), microservices, model monitoring and versioning
- **Domain:** Healthcare and life sciences, sports analytics, commercial targeting analytics, regulated data environments

## Public Projects

### [Agentic Stock Intelligence](https://github.com/abi-raghavan/agentic-stock-intelligence)

Multi-agent equity research platform for Indian (NSE/BSE) and US markets. A LangGraph workflow chains planning, research, hybrid RAG retrieval, risk synthesis and report verification, with a re-retrieval pass when claims fail verification. Live prices, fundamentals and news degrade independently to labelled snapshots, and cached evidence caps the reported confidence so a conclusion is never stated more firmly than its sources support.

`Python` `LangGraph` `FastAPI` `Next.js` `BM25 RAG` `SQLite` `Docker`

### [AIRA](https://github.com/abi-raghavan/aira-core)

Privacy-first Android voice companion for predictable, offline assistance. Speech is processed on-device and never stored; chosen phrases map to fixed spoken scripts through deterministic rules rather than an open-ended chatbot, and a separate demo build guarantees no SMS or calls while the release build can alert an approved carer.

`Kotlin` `Android` `On-device speech` `Encrypted storage` `Gradle`

### [x-labs](https://github.com/abi-raghavan/x-labs) - applied ML and GenAI labs

- **[Experimentation Lab](https://x-lab-argon.streamlit.app)** - End-to-end A/B testing workflow: deterministic SHA-256 assignment, conversion and revenue analysis with confidence intervals, plus sample ratio mismatch and power checks that flag untrustworthy data before lift is reported.
- **[Ride Incentive Recommender](https://ride-signal-argon.streamlit.app)** - Explainable rider scoring that compares four incentive options against a no-incentive baseline, separating booking propensity from incentive uplift to avoid discounting riders who would convert anyway.
- **[RAG Support Assistant](https://github.com/abi-raghavan/x-labs/tree/main/rag_support_assistant)** - Grounded document assistant combining dense and BM25 retrieval with reciprocal rank fusion, cross-encoder reranking, inline citations, an explicit refusal path for out-of-scope questions, and a retrieval and groundedness evaluation harness.

The lab projects run on synthetic or sample data; their metrics describe the implemented evaluation workflow rather than production outcomes.

## Education

B.Tech, Electronics and Communication Engineering - National Institute of Technology (NIT) Calicut, 2015-2019

## Contact

- Email: abiraghavan@outlook.com
- LinkedIn: [linkedin.com/in/abiraghavan](https://www.linkedin.com/in/abiraghavan/)
