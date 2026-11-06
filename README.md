# Sourabha K Kallapur

**Machine Learning Engineer** · Graduate AI Engineer at Allica Bank · MSc Applied AI, University of Warwick (WMG) · Coventry, UK

[Portfolio](https://portfolio-sourabha-kk.vercel.app) · [Resume (PDF)](https://portfolio-sourabha-kk.vercel.app/resume.pdf)

Most machine-learning projects end in a notebook. I care about what happens next: the pipeline that cannot leak test data, the service that survives bad input, the agent that refuses instead of guessing, and the alarm that goes off when the world drifts away from the training set.

I joined Allica Bank as a Graduate AI Engineer in October 2026 and I'm finishing an MSc in Applied AI at Warwick. Everything below is public, so you can check it.

## What I've built so far

**Agents that know when to say no.** At the AAI Tech Talks hackathon my team took 2nd place with [SecureOps Assistant](https://github.com/SourabhaKK/vector-cartel), an industrial-security assistant. I built its agent and LLM layers: a LangGraph agent behind a regex gate that stops prompt injection before any model sees it, and a groundedness check that won't serve an answer it can't back up. I also built [ChronoScholar](https://github.com/SourabhaKK/ChronoScholar), which notices when a new paper contradicts one it already stored, and [Groundwork](https://github.com/SourabhaKK/Groundwork), which researches a UK company and writes a citation-backed report that rates its own confidence. In [LLM AI Basket Builder](https://github.com/SourabhaKK/llm-ai-basket-builder), the model proposes a shopping basket and deterministic rules decide whether it is allowed.

**Models that have to earn their numbers.** [FinSight](https://github.com/SourabhaKK/FinSight) reads financial news with a fine-tuned DistilBERT that reaches 0.9237 macro-F1 on 2,000 held-out articles. When I tried a reranker, it made retrieval precision worse (0.93 to 0.89 on a small five-question check), and I published that instead of burying it. Alongside it sit [Customer Churn Prediction](https://github.com/SourabhaKK/customer-churn-prediction-ml), [NLP Complaint Classification](https://github.com/SourabhaKK/nlp-complaint-classification-pipeline) and [Adaptive Fraud Detection](https://github.com/SourabhaKK/adaptive-fraud-detection-ml-pipeline), all built test-first. The fraud one runs on synthetic data, so it is an engineering showcase, not a benchmark.

**Systems that survive contact with reality.** [ML Model Deployment](https://github.com/SourabhaKK/ml-model-deployment-fastapi) is a FastAPI inference service with API-key auth, rate limiting, a circuit breaker and a request timeout, running in Docker on AWS EC2. [ML Drift Detection](https://github.com/SourabhaKK/ml-model-monitoring-drift-detection) is the alarm for when production data stops looking like training data, with exit codes a CI pipeline can act on.

## How I work

Tests first. Every number I publish comes with how it was measured and where it stops holding; the [case studies on my portfolio](https://portfolio-sourabha-kk.vercel.app) show the architecture, results and limitations of each project.

**Stack:** Python, scikit-learn, PyTorch, Hugging Face, Qdrant, LangChain, LangGraph, FastAPI, Docker, GitHub Actions, MLflow, AWS.
