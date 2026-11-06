# Sourabha K Kallapur

**Machine Learning Engineer** · Graduate AI Engineer at Allica Bank · MSc Applied AI, University of Warwick (WMG) · Coventry, UK

[Portfolio](https://portfolio-sourabha-kk.vercel.app) · [Resume (PDF)](https://portfolio-sourabha-kk.vercel.app/resume.pdf)

I build machine-learning systems that survive production: pipelines that cannot leak test data, services that cope with bad input, agents that refuse instead of guessing, and alarms that fire when data drifts. I write the tests first and publish every number with how it was measured.

- **Now:** Graduate AI Engineer at Allica Bank, since October 2026
- **Studying:** MSc Applied AI at Warwick (WMG)
- **Latest win:** 2nd place at the AAI Tech Talks hackathon (June 2026), where I built the agent and LLM layers

## What I've built

**Agents that know when to say no**
- [SecureOps Assistant](https://github.com/SourabhaKK/vector-cartel): 2nd-place hackathon project. A LangGraph agent behind a regex gate that blocks known prompt-injection patterns before any model sees them.
- [ChronoScholar](https://github.com/SourabhaKK/ChronoScholar): notices when a new paper contradicts one it already stored.
- [Groundwork](https://github.com/SourabhaKK/Groundwork): researches a UK company and writes a citation-backed report that rates its own confidence.
- [LLM AI Basket Builder](https://github.com/SourabhaKK/llm-ai-basket-builder): the model proposes a basket, deterministic rules decide if it is allowed.

**Models that have to earn their numbers**
- [FinSight](https://github.com/SourabhaKK/FinSight): fine-tuned DistilBERT, 0.9237 macro-F1 on 2,000 held-out articles. Its reranker lowered retrieval precision (0.93 to 0.89, five-question check), so I published that.
- [Customer Churn Prediction](https://github.com/SourabhaKK/customer-churn-prediction-ml): leakage-safe pipeline, built test-first.
- [NLP Complaint Classification](https://github.com/SourabhaKK/nlp-complaint-classification-pipeline): TF-IDF or BERT, built test-first.
- [Adaptive Fraud Detection](https://github.com/SourabhaKK/adaptive-fraud-detection-ml-pipeline): test-first pipeline on synthetic data, an engineering showcase.

**Systems that survive contact with reality**
- [ML Model Deployment](https://github.com/SourabhaKK/ml-model-deployment-fastapi): FastAPI service with API-key auth, rate limiting and a circuit breaker, on AWS EC2.
- [ML Drift Detection](https://github.com/SourabhaKK/ml-model-monitoring-drift-detection): PSI, KS and Chi-Square drift alarms with CI-friendly exit codes.

Every project has a case study with its architecture, results and limitations on my [portfolio](https://portfolio-sourabha-kk.vercel.app).

**Stack:** Python, scikit-learn, PyTorch, Hugging Face, Qdrant, LangChain, LangGraph, FastAPI, Docker, GitHub Actions, MLflow, AWS.
