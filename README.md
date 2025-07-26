# Project-05-Generative-AI-Driven-Credit-Risk-Copilot
An end-to-end Generative AI–driven Credit Risk Copilot combining Basel III/IFRS-9 scorecards with a Retrieval-Augmented Generation assistant for explainable underwriting.

---

# Credit Risk Copilot

**An end-to-end Generative AI–Driven Credit Risk Copilot**  
Combines classical credit risk analytics (PD, EAD, LGD) with a Retrieval-Augmented Generation (RAG) layer to deliver explainable, source-cited underwriting decisions and automate the full model lifecycle on AWS.

---

## 1. Project Overview

The Credit Risk Copilot is designed for risk analysts and underwriters at banks, fintechs, and hedge funds. It integrates:

- **Regulatory Scorecards:** Implements Basel III credit metrics (Probability of Default, Exposure at Default, Loss Given Default) and IFRS-9 expected credit loss staging.  
- **Generative-AI Assistant:** A conversational interface powered by large language models (e.g., OpenAI GPT) with document retrieval (FAISS/Pinecone) to answer policy questions, justify risk decisions with citations, and surface supporting scorecard outputs.  
- **Full MLOps Pipeline:** Real-time ETL (Kafka → PySpark → Snowflake), feature engineering, model training, experiment tracking (MLflow), governance gates, drift monitoring, and serverless deployment (AWS Lambda/ECS).  
- **Explainability & Reporting:** SHAP/LIME dashboards and audit trails for regulators, delivered via Tableau or a BI interface.

### Objectives & Scope

- Automate borrower credit assessments while maintaining full interpretability and auditability.  
- Reduce underwriting cycle time from days to minutes with AI-driven recommendations.  
- Ensure compliance with Basel III, IFRS-9, and CECL through embedded scorecard logic and explainability.  
- Deploy on cloud with robust security (IAM, KMS, VPC) and governance controls.

### Success Metrics

- Average decision turnaround time ≤ 5 minutes  
- Scorecard accuracy: PD/AUC ≥ 0.75  
- RAG response precision ≥ 90% on policy queries  
- Zero critical security or compliance violations in audit reviews

---

## 2. Key Features

- **Real-Time Data Ingestion:** Kafka-driven pipelines for loan origination and transactions.  
- **Hybrid Scoring Engine:** Combines statistical scorecards with AI explanations.  
- **Interactive Chat UI:** Web interface for analysts to query and review decisions.  
- **Automated Retraining:** Airflow-scheduled batch retraining with drift alerts.  
- **Governance Dashboards:** SHAP value visualisations and regulatory reporting logs.

---



