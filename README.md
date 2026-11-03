# Hi, I'm Deep Bendale

**I'm an engineer who builds ML and data systems end to end: credit risk models, RAG pipelines and analytics APIs, shipped with tests, docs and honest evaluation.**

Open to freelance projects and full-time roles in ML, data and AI engineering.
**deepbendale231@gmail.com** · [LinkedIn](https://www.linkedin.com/in/deepbendale/)

---

## Selected work

### [Credit Decisioning Engine](https://github.com/deepbendale231/credit-decisioning-engine)
Eligibility rules, then a calibrated, monotone XGBoost default-risk model, then an approve / refer / decline policy with SHAP reason codes. FastAPI decision API, Streamlit demo, CI, Docker.
- Trained on 307K applications and 1.67M prior applications (Kaggle Home Credit)
- ROC-AUC **0.763** on a held-out test split, with bootstrap confidence intervals
- Approves **3.84 pts more applicants** than the best tuned rules-only policy at the same default rate
- Includes a model card, fairness audit, drift monitor and runbook

### [Digital Lending Journey Teardown](https://github.com/deepbendale231/lending-journey-teardown)
A product teardown of a digital lending flow: friction log, RBI digital-lending checklist, RICE prioritisation, user stories, PRD, A/B test plan and metrics tree.

### [Pollution Analytics](https://github.com/deepbendale231/Pollution-Analytics)
Air-quality analysis and AQI prediction across Indian cities: 3,400+ readings, a Random Forest model (R² 0.91, MAE 7.8 µg/m³), FastAPI backend and Streamlit dashboard.

### [RAG Teaching Assistant](https://github.com/deepbendale231/RAG-BASED-Teaching-LLM)
Turns video lectures into a searchable knowledge base (transcribe, chunk, embed, retrieve) and answers questions with a local LLM.

### [HouseIQ](https://github.com/deepbendale231/House-Prediction-ML-Model-)
House-price prediction with scikit-learn pipelines, a FastAPI service, a Next.js frontend and Supabase.

---

## Stack

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-EB5E28)
![SHAP](https://img.shields.io/badge/SHAP-6C63FF)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

---

## How I work

- **Measure honestly.** Baselines first, held-out test sets, confidence intervals, and a benchmark that is not a strawman.
- **Ship the whole thing.** API, UI, tests, CI, a model card and a runbook, not just a notebook.
- **Write down the decisions.** Each project explains what was chosen, what was cut and why.
