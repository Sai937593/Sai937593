# Hi, I'm Sai Nivas Kalicherla 👋

AI/ML Engineer focused on agentic RAG systems, real-time MLOps, and production LLM pipelines. I build systems that are grounded, observable, and reliable — not just demos.

- **Now:** Agentic retrieval systems, hybrid vector search, real-time data pipelines
- **Strengths:** LangGraph agent design, hybrid retrieval (BGE-M3 + ColBERT), observability-first MLOps, responsible AI
- **Looking for:** AI Engineer, ML Engineer, and MLOps roles

---

## 🧠 Core Skills

**Languages:** Python, SQL

**Generative AI & Retrieval:** Agentic RAG · LangGraph · LlamaIndex · LangChain · BGE-M3 · ColBERT · Qdrant · FAISS · Transformers · Prompt Engineering · RLHF

**ML & DL:** Scikit-learn · XGBoost · TensorFlow · PyTorch · Keras · SHAP · A/B Testing · Statistical Modeling

**MLOps & Infra:** GCP (Pub/Sub, Cloud Run, BigQuery) · Docker · FastAPI · Redis · Grafana · LangSmith · ETL

**Learning:** Apache Spark · Apache Airflow · GANs · VAEs · RNNs

---

## 🚀 Projects

### [Intelligent Compliance Q&A — Agentic RAG for Regulatory Documents](https://github.com/Sai937593/Intelligent-Compliance-Q-A-System-for-an-NBFC)
Agentic RAG system for an NBFC compliance team. Replaces 5–7 hours/day of manual RBI/SEBI circular research with cited answers in under 30 seconds.

- 7-node LangGraph ReAct agent — conditional edges for refusal, re-retrieval, and adversarial premise contradiction. Full trace via LangSmith.
- Hybrid BGE-M3 retrieval (dense + sparse) with ColBERT MaxSim reranker (top-50 → top-10) — handles exact regulatory terms (CRAR, NPA, NBFC-ND-SI) that pure semantic search misses
- HierarchicalNodeParser (LlamaIndex) for parent-child chunk indexing — citations resolve to exact circular number + clause
- Two-stage refusal: ColBERT score pre-filter + LLM relevance judge (confidence 0–10)
- **Eval: 9/9 in-scope queries answered with citations · 1/1 OOS query correctly refused**
- Stack: `LangGraph` `LlamaIndex` `BGE-M3` `ColBERT` `Qdrant` `LiteLLM` `FastAPI SSE` `pymupdf4llm`

---

### [Real-Time Fraud Detection System — MLOps on GCP](https://github.com/Sai937593/fraud-detection-mlops)
End-to-end streaming fraud detection pipeline with full MLOps instrumentation.

- 50K+ transactions/min · sub-2s detection latency via stateful FastAPI + Redis inference service
- Pub/Sub → BigQuery streaming for continuous model retraining and real-time alerts
- Grafana dashboard tracking fraud rates, model drift, and pipeline throughput
- Stack: `GCP` `Pub/Sub` `BigQuery` `Cloud Run` `FastAPI` `Redis` `Docker` `Grafana`

---

### [Responsible AI — Bias Audit & Mitigation in Loan Approvals](https://github.com/Sai937593/Fairness-in-Lending-Audit)
Fairness audit on historical loan approval data with quantified mitigation.

- Identified 31.6% approval rate disparity across demographic groups
- SHAP analysis traced bias to socio-economic features in training data — not explicit discrimination
- Reweighing mitigation cut fairness gap by 65% with only 3.3% accuracy tradeoff
- Stack: `XGBoost` `SHAP` `Scikit-learn` `Pandas` `Matplotlib`

---

## 🏢 Experience

**Generalist Ops (Contract) · Deccan AI** — Dec 2025 – Present
Quality control of RLHF annotation outputs for production LLM training pipelines. Hands-on exposure to annotation QC processes and LLM fine-tuning data workflows at scale.

**Data Scientist Intern · Shiash Solutions** — Jan 2023 – May 2023
XGBoost fraud model (ROC-AUC 0.87, +15% recall via SMOTE + Optuna). Automated feature engineering pipeline cutting iteration time by 30%. Stakeholder dashboards for model KPIs.

---

## 🎓 Education & Development

B.Tech, Computer Science · Vellore Institute of Technology (VIT)

Data Science Program · Odin School · Self-study: Agentic RAG, LangGraph, LlamaIndex, Transformers, GANs, VAEs, RNNs · Currently learning: Apache Spark, Apache Airflow

---

## 📬 Connect

[LinkedIn](https://www.linkedin.com/in/sai-nivas-kalicherla-067477301/) · [GitHub](https://github.com/Sai937593) · sainivaskalicherla@gmail.com
