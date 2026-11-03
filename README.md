<img src="assets/logo.svg" alt="SK logo" width="56" height="56">

# Sourabha K Kallapur

**Machine Learning Engineer** · Graduate AI Engineer at Allica Bank · MSc Applied AI, University of Warwick (WMG) · Coventry, UK

[Portfolio](https://portfolio-sourabha-kk.vercel.app) · [Resume (PDF)](https://portfolio-sourabha-kk.vercel.app/resume.pdf) · [LinkedIn](https://www.linkedin.com/in/sourabhakk) · [Email](mailto:sourabha.kallapurk@gmail.com)

I build and ship machine-learning systems across the whole lifecycle: leakage-safe feature pipelines, transformer fine-tuning, RAG and agentic LLM systems, FastAPI inference services, experiment tracking and statistical drift monitoring. I write the tests first, and I report every number with how it was measured.

## Featured projects

Each project has a case study on my [portfolio](https://portfolio-sourabha-kk.vercel.app) with its architecture, how each figure was measured, and its limitations.

| Project | What it is | Evidence |
| --- | --- | --- |
| **[FinSight](https://github.com/SourabhaKK/FinSight)** ([case study](https://portfolio-sourabha-kk.vercel.app/projects/finsight)) | Financial-news NLP pipeline: fine-tuned DistilBERT classifier, RAG over SEC and FOMC documents on Qdrant, provider-agnostic LLM risk briefs, drift monitoring, Docker and CI. | 0.9237 macro-F1 on a 2,000-sample held-out set. The RAG evaluation uses 5 questions, so it shows a working pipeline, not a ranking of retrieval modes. |
| **[AAI SecureOps Assistant](https://github.com/SourabhaKK/vector-cartel)** ([case study](https://portfolio-sourabha-kk.vercel.app/hackathons/aai-secureops)) | 2nd place, AAI Tech Talks Hackathon 2026. RAG assistant for industrial-control-system security (NIST, CISA, MITRE ATT&CK for ICS) with a LangGraph agent, a deterministic injection gate and a groundedness-checked answer. I built the agent and LLM layers. | 98.1% Hit@5 on a 54-query retrieval gold set. Direct injection is blocked; indirect injection through the corpus is a documented open gap. |
| **[ChronoScholar](https://github.com/SourabhaKK/ChronoScholar)** ([case study](https://portfolio-sourabha-kk.vercel.app/hackathons/chronoscholar)) | Research-memory agent that flags when newer papers contradict stored claims, built on Cognee's graph-vector memory. Solo project. | F1 1.000 on a 10-pair pilot. Directional only. |
| **[ML Model Deployment](https://github.com/SourabhaKK/ml-model-deployment-fastapi)** ([case study](https://portfolio-sourabha-kk.vercel.app/projects/ml-model-deployment-fastapi)) | Hardened FastAPI inference service: three-layer validation, API-key auth, rate limiting, circuit breaker, Docker on AWS EC2. | 28 tests. No latency benchmark is published, so none is claimed. |
| **[Customer Churn Prediction](https://github.com/SourabhaKK/customer-churn-prediction-ml)** ([case study](https://portfolio-sourabha-kk.vercel.app/projects/customer-churn-prediction-ml)) | Leakage-safe scikit-learn pipeline with a RandomForest and a joblib export for serving. | ROC-AUC 0.839 and 92 tests, from a single train/test split. |
| **[ML Drift Detection](https://github.com/SourabhaKK/ml-model-monitoring-drift-detection)** ([case study](https://portfolio-sourabha-kk.vercel.app/projects/ml-model-monitoring-drift-detection)) | PSI, KS and Chi-Square drift engine with CLI exit codes so a CI step can gate on drift. | 138 tests. |
| **[LLM AI Basket Builder](https://github.com/SourabhaKK/llm-ai-basket-builder)** ([case study](https://portfolio-sourabha-kk.vercel.app/projects/llm-ai-basket-builder)) | FastAPI and GPT-4o-mini backend whose output passes deterministic dietary and budget rules, with a fallback basket if the LLM fails. | 45 tests. The dietary filter is keyword matching; its limits are listed in the case study. |

## More repositories

| Repository | What it is |
| --- | --- |
| **[Groundwork](https://github.com/SourabhaKK/Groundwork)** | Agentic UK company underwriting intelligence: resolves a company, gathers evidence from Companies House and the web, and writes a citation-backed report with explicit per-section confidence. |
| **[Adaptive Fraud Detection Pipeline](https://github.com/SourabhaKK/adaptive-fraud-detection-ml-pipeline)** | Test-driven, leakage-safe fraud pipeline. The demo trains on synthetic transactions, so it is an engineering showcase, not a benchmark. |
| **[NLP Complaint Classification](https://github.com/SourabhaKK/nlp-complaint-classification-pipeline)** | Test-driven binary text classifier (TF-IDF with logistic regression, or BERT). |

## Stack

| | |
| --- | --- |
| **Language** | Python |
| **ML and NLP** | scikit-learn, PyTorch, Hugging Face Transformers and Datasets, BERT and DistilBERT, Pydantic |
| **RAG and LLM systems** | Qdrant, sentence-transformers, LangChain, LangGraph, RAGAS, provider-agnostic LLM layers |
| **Serving and MLOps** | FastAPI, Docker, GitHub Actions, MLflow, AWS EC2 |
| **Monitoring** | PSI, Kolmogorov-Smirnov and Chi-Square drift tests |
| **Testing** | PyTest, test-driven development |
| **Data** | pandas, NumPy, SciPy, Jupyter |

## Background

- **Graduate AI Engineer**, Allica Bank (October 2026 to present)
- **MSc Applied Artificial Intelligence**, WMG, University of Warwick (final result due December 2026)
- **BTech Computer Science and Information Technology**, REVA University, Bangalore (2024, First Class with Distinction)
- **Hackathons:** 2nd place at AAI SecureOps (June 2026); participant at The Hangover Hackathon (July 2026)

I am happy to talk about production ML, LLM systems and MLOps. The quickest routes are [email](mailto:sourabha.kallapurk@gmail.com) and [LinkedIn](https://www.linkedin.com/in/sourabhakk).
