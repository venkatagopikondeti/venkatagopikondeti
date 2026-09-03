# Venkata Gopi Kondeti

**AI/ML Engineer** — LLM applications, MLOps, and forecasting systems.

I build the parts of machine learning that have to keep working after the demo: retrieval
pipelines that can be measured, models that fail loudly instead of silently, and forecasts
that are honest about what they can't predict.

Currently at **NVIDIA**, working on LLM applications with Azure OpenAI and LangChain.
Previously **Fractal**, on demand forecasting and generative AI workflows on AWS.
MS in Information Technology Management, Webster University.

---

## Projects

| Project | What it is | Result |
|---|---|---|
| **[rag-doc-assistant](https://github.com/venkatagopikondeti/rag-doc-assistant)** | RAG question answering over your own documents — chunking, embeddings, vector index, FastAPI service | 100% hit@3, MRR 1.00 on a labelled eval set |
| **[mlops-churn-pipeline](https://github.com/venkatagopikondeti/mlops-churn-pipeline)** | Train → quality-gate → serve → monitor for drift, end to end | ROC AUC 0.743, PSI drift monitor catching shifts at 0.30 |
| **[demand-forecasting](https://github.com/venkatagopikondeti/demand-forecasting)** | Daily demand forecasting with leakage-free features and rolling-origin backtesting | **MASE 0.60** vs 1.06 for the seasonal-naive baseline |

Each repo runs its tests on Python 3.10/3.11/3.12 in CI, with the linter and the
evaluation step gating every push. 58 tests, no network required.

### Three ideas they share

**Measure the thing that actually decides quality.** In the RAG project, retrieval is
scored on its own — hit-rate@k and MRR — because answer quality is bounded by it. In the
forecasting project, every model runs against a seasonal-naive baseline over identical
folds, because a forecast without a baseline is a number without a meaning.

**Fail loudly.** The churn pipeline's quality gate exits non-zero when test ROC AUC drops
below its floor, so a regression stops the build instead of quietly shipping.

**Make it testable without the vendor.** Embeddings, vector index and LLM all sit behind
small interfaces with offline defaults, so the logic that matters is unit-tested in CI
without a single external call — then swapped for the real models in production.

---

## Toolbox

**Languages** Python · SQL · PySpark · R

**ML** scikit-learn · PyTorch · TensorFlow · XGBoost · LightGBM · Prophet · Hugging Face Transformers

**LLM & RAG** Azure OpenAI · LangChain · LangGraph · FAISS · Pinecone · ChromaDB · sentence-transformers · Amazon Bedrock

**MLOps** MLflow · Docker · Kubernetes / AKS · GitHub Actions · Azure DevOps · drift monitoring · model registry

**Cloud** Azure (ML, Databricks, Functions, Data Lake Gen2, Cosmos DB) · AWS (SageMaker, Glue, Lambda, Kinesis, Step Functions, S3)

**Data** Spark · Databricks · Airflow · ETL/ELT pipelines · feature engineering · real-time inference

**Serving & BI** FastAPI · Flask · REST APIs · Power BI · Tableau

---

## Contact

📧 venkatagopikondeti307@gmail.com

Open to AI/ML engineering roles. Happy to walk through any of the projects above.
