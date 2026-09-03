# Venkata Gopi Kondeti

### AI/ML Engineer — LLM Applications · MLOps · Forecasting

**5 years** building and shipping machine learning systems · **US — open to relocation** · **Open to new roles**

📧 **venkatagopikondeti307@gmail.com**

---

## At a glance

| | |
|---|---|
| **Current** | AI/ML Engineer @ NVIDIA — LLM applications with Azure OpenAI and LangChain |
| **Previously** | Machine Learning Engineer @ Fractal — demand forecasting and generative AI on AWS |
| **Education** | MS, Information Technology Management — Webster University (CGPA 3.92) |
| **Core** | Python · LLMs & RAG · MLflow · FastAPI · Azure ML · AWS SageMaker · Docker · Kubernetes |
| **Looking for** | AI/ML Engineer, ML Platform, or MLOps roles |

---

## What I've delivered

- **35% faster** employee query resolution — LLM applications built with Azure OpenAI and LangChain
- **25% fewer** irrelevant search results — retrieval-augmented generation using FAISS, Pinecone and Azure AI Search
- **40% fewer** release incidents — model deployment on MLflow, Docker and Azure Kubernetes Service
- **10M+ records daily** — PySpark data pipelines on Azure Databricks and Data Lake Storage Gen2
- **40% faster** data processing — automated pipelines with AWS Glue, Lambda and Kinesis
- **12% better** forecasting accuracy — feature engineering and hyperparameter tuning with XGBoost and Prophet

---

## Featured projects

Three production-shaped repositories. Every number below is reproducible by running the code.

### 🔍 [rag-doc-assistant](https://github.com/venkatagopikondeti/rag-doc-assistant)
Retrieval-augmented question answering over your own documents — chunking, embeddings, vector index, and a FastAPI service.
**Result: 100% hit@3, MRR 1.00** on a six-question retrieval smoke test.
`Python` `FastAPI` `FAISS` `sentence-transformers` `Azure OpenAI` `Docker`

### ⚙️ [mlops-churn-pipeline](https://github.com/venkatagopikondeti/mlops-churn-pipeline)
End-to-end MLOps: train → quality gate → serve → monitor for drift. The build fails if model quality regresses.
**Result: ROC AUC 0.743**, PSI drift monitor flagging population shifts before labels arrive.
`scikit-learn` `MLflow` `FastAPI` `Docker` `GitHub Actions` `drift detection`

### 📈 [demand-forecasting](https://github.com/venkatagopikondeti/demand-forecasting)
Daily demand forecasting with leakage-free features and rolling-origin backtesting.
**Result: MASE 0.63** — 37% below the seasonal-naive scale it's measured against.
`XGBoost` `scikit-learn` `pandas` `time series` `backtesting`

> All three run their test suites on Python 3.10 / 3.11 / 3.12 in CI, with linting and evaluation gating every push. **64 tests, no network required.**

---

## Technical skills

**Languages** Python · SQL · PySpark · R

**Machine learning** scikit-learn · PyTorch · TensorFlow · XGBoost · LightGBM · Prophet · Hugging Face Transformers

**LLM & GenAI** Azure OpenAI · LangChain · LangGraph · RAG · Amazon Bedrock · FAISS · Pinecone · ChromaDB · sentence-transformers · prompt engineering · semantic search

**MLOps** MLflow · Docker · Kubernetes / AKS · GitHub Actions · Azure DevOps · CI/CD · model registry · model monitoring · drift detection · retraining

**Azure** Azure ML · Azure AI Studio · Databricks · Functions · Event Hubs · Data Lake Storage Gen2 · Cosmos DB · AKS

**AWS** SageMaker (Endpoints, Feature Store, Model Monitor) · Bedrock · Glue · Lambda · Kinesis · Step Functions · S3 · API Gateway · IAM

**Data engineering** Apache Spark · Databricks · Airflow · ETL/ELT · feature engineering · real-time inference · data validation

**Serving & BI** FastAPI · Flask · REST APIs · Power BI · Tableau

---

## How I work

**Measure what actually decides quality.** Retrieval is scored on its own — answer quality is bounded by it. Every forecast is measured against a baseline, because a forecast without one is a number without a meaning.

**Fail loudly, not silently.** Quality gates exit non-zero on regression. Drift is detected from inputs alone, so problems surface weeks before labels arrive.

**Build it so it can be tested.** Embeddings, vector stores and LLMs sit behind small interfaces with offline defaults — the logic that matters is verified in CI without a single external call, then swapped for real models in production.

---

📧 **venkatagopikondeti307@gmail.com** — happy to walk through any project above.
