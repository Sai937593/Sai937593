# Hi, I'm Sai Nivas 👋

AI/ML Engineer. I build systems that are grounded, observable, and production-ready — not demos.

**Now:** Actively seeking AI Engineer · ML Engineer · MLOps roles  
**Background:** Agentic RAG · Real-time data pipelines · LLM quality  
**Status:** Immediate joiner · Bangalore

---

## 🚀 Projects

### [Intelligent Compliance Q&A — Agentic RAG for Regulatory Documents](https://github.com/Sai937593/Intelligent-Compliance-Q-A-System-for-an-NBFC)
Replaces 5–7 hours/day of manual RBI/SEBI circular research for an NBFC compliance team. Answers in under 30 seconds with citations to exact circular + clause.

- 7-node LangGraph ReAct agent with conditional edges for refusal, re-retrieval, and adversarial premise contradiction
- Hybrid BGE-M3 retrieval (dense + sparse) + ColBERT MaxSim reranker (top-50 → top-10) — handles exact regulatory terms pure semantic search misses
- HierarchicalNodeParser (LlamaIndex) for parent-child chunk indexing; two-stage refusal via ColBERT pre-filter + LLM relevance judge
- **Eval: 9/9 in-scope queries answered with citations · 1/1 OOS query correctly refused**
- `LangGraph` `LlamaIndex` `BGE-M3` `ColBERT` `Qdrant` `LiteLLM` `FastAPI SSE`

---

### [Real-Time E-Commerce Lakehouse](https://github.com/Sai937593/realtime-lakehouse-ecommerce)
End-to-end streaming lakehouse for e-commerce analytics — Kafka through Bronze/Silver/Gold with strict data quality contracts throughout.

- Spark Structured Streaming + Delta Lake; Silver layer enforces hard dedup by `event_id`, late-event diagnostics, and automated quarantine for invalid records
- Gold layer produces campaign performance, product performance, hourly revenue, and funnel metrics
- Observability layer tracks pipeline runs, batch metrics, and data-quality outcomes across all layers
- SQL validation suite with failure-row semantics + Docker-backed Spark checks; read-only Streamlit dashboard
- `Kafka` `Spark Structured Streaming` `Delta Lake` `Docker` `Streamlit`

---

### [Real-Time Fraud Detection — MLOps on GCP](https://github.com/Sai937593/fraud-detection-mlops)
End-to-end streaming fraud detection pipeline with full MLOps instrumentation.

- 50K+ transactions/min · sub-2s detection latency via stateful FastAPI + Redis inference service
- Pub/Sub → BigQuery for continuous model retraining and real-time alerts
- Grafana dashboard tracking fraud rates, model drift, and pipeline throughput
- `GCP` `Pub/Sub` `BigQuery` `Cloud Run` `FastAPI` `Redis` `Docker` `Grafana`

---

### [Responsible AI — Bias Audit & Mitigation in Loan Approvals](https://github.com/Sai937593/Fairness-in-Lending-Audit)
Fairness audit on historical loan approval data with quantified mitigation.

- Identified 31.6% approval rate disparity across demographic groups
- SHAP traced bias to socio-economic features in training data
- Reweighing mitigation cut the fairness gap by 65% with a 3.3% accuracy tradeoff
- `XGBoost` `SHAP` `Scikit-learn` `Pandas`

---

## 🧠 Skills

| Domain | Tools |
|---|---|
| **Languages** | Python, SQL |
| **Generative AI & Retrieval** | Agentic RAG · LangGraph · LlamaIndex · LangChain · BGE-M3 · ColBERT · Qdrant · FAISS · Transformers · Prompt Engineering · RLHF |
| **Data Engineering** | Apache Spark · Kafka · Delta Lake · ETL |
| **MLOps & Infra** | GCP (Pub/Sub, Cloud Run, BigQuery) · Docker · FastAPI · Redis · Grafana · LangSmith |
| **ML & DL** | Scikit-learn · XGBoost · TensorFlow · PyTorch · Keras · SHAP · A/B Testing |
| **Exploring** | Apache Airflow · GANs · VAEs · RNNs |

---

## 🏢 Experience

**RLHF Annotation Quality Analyst  · Deccan AI** — Dec 2025 – May 2026  
QC of RLHF annotation outputs for production LLM training pipelines. Structured feedback loops to improve annotation quality across fine-tuning datasets.

**Data Scientist Intern · Shiash Solutions** — Jan 2023 – May 2023  
XGBoost fraud model (ROC-AUC 0.87, +15% recall via SMOTE + Optuna). Automated feature engineering pipeline; stakeholder dashboards for model KPIs.

---

## 🎓 Education

B.Tech, Computer Science · Vellore Institute of Technology (VIT)  
Data Science Program · Odin School

---

## 📬 Connect

[LinkedIn](https://www.linkedin.com/in/sai-nivas-kalicherla-067477301/) · [GitHub](https://github.com/Sai937593) · sainivaskalicherla@gmail.com
