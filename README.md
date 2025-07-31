# Customer-Churn-Prediction
Objective: Predict churn, provide actionable business insights, and automate interventions to retain customers.

 1. Define the Business Problem
“A telecom company is experiencing rising customer churn and wants to proactively identify customers who are likely to leave, understand why, and recommend how to retain them.”


# 🧠 Customer Churn Prediction & Retention Dashboard

> End-to-end AI system to predict customer churn, understand why customers are leaving, and recommend tailored actions to retain them — complete with a live Streamlit dashboard and automated retraining pipeline.

---

## 📌 Project Overview

This project aims to solve a core business problem: **retaining customers** in a competitive market.  
Using historical data, behavioral segmentation, and advanced ML models, we predict churn and suggest **custom retention actions** through a recommendation engine.

---

## 🎯 Objectives

- Predict the probability of customer churn with high accuracy
- Understand churn drivers using explainability techniques
- Segment customers into actionable behavioral personas
- Recommend nudging strategies based on predicted risk
- Visualize KPIs in an interactive dashboard for stakeholders

---

## 🧩 Key Features

- ✅ ML-powered churn prediction (XGBoost, SHAP explainability)
- 🔍 Auto-updating customer personas (KMeans + UMAP)
- 🧠 Nudging Engine to recommend retention actions (email, call, discount)
- 📊 Streamlit dashboard with filters, charts, and churn risk analysis
- 🔁 Automated weekly retraining pipeline (Airflow / Prefect)


## 📂 Project Structure


📦 customer-churn-retention-ai
├── data/                  # Raw & processed data
├── notebooks/             # Jupyter notebooks (EDA, ML, NLP)
├── scripts/               # Reusable Python scripts for modeling
├── dashboard/             # Streamlit dashboard code
├── models/                # Saved models
├── outputs/               # Visuals, metrics, reports
├── retraining/            # Automation scripts
├── utils/                 # Helper functions & configs
├── requirements.txt       # Dependencies
└── README.md              # You're here!

 Machine Learning Models Used :
Exploratory Data Analysis – Pandas, Seaborn
Supervised Learning – Logistic Regression, Random Forest, XGBoost
Unsupervised Learning – KMeans Clustering + UMAP
Explainability – SHAP
Recommendation Engine – Decision Trees for rule-based nudges

📊 Dashboard Preview
Module	Description
Churn Analysis	
Persona Viewer	
Nudging Actions	
KPI Impact

🔄 Automation & Deployment
Retraining Scheduler – Weekly updates using Airflow/Python scripts

MLflow – Experiment tracking & model versioning

Deployment – Hosted with Streamlit on Render / Heroku

🛠️ Tech Stack
Category	Tools
Languages	Python, SQL
ML Libraries	scikit-learn, XGBoost, SHAP, UMAP
Dashboard	Streamlit, Plotly
Data Handling	Pandas, NumPy, SQLAlchemy
Automation	Airflow / Prefect
Deployment	Render / Heroku / AWS
Tracking	MLflow, GitHub Projects

💡 Future Improvements
Integrate LLMs (GPT) to personalize churn message tone using support ticket text
Add multivariate time-series analysis for usage trends
Real-time Slack/Email alerts when churn risk spikes

📬 Contact
Built by Vaishnavi Desai – Data Scientist
🔗 LinkedIn: https://www.linkedin.com/in/vaishnavidesai-20ds
📧 Email:desaivaishnavi04@gmail.com
