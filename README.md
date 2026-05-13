![alt text](https://github.com/fadlinur/Final-Project/blob/main/streamlit%20smote/download.png?raw=true)


# HIRESIGHTS – Data-Driven Recruitment System

Optimizing Biased Talent Acquisition Through Data-Driven HR Analytics

---


## 📑 Presentation

[Download Presentation](./Final_Presentation.pptx)

---

# 📌 Project Overview

HIRESIGHTS is a data-driven recruitment system designed to optimize talent acquisition using machine learning and HR analytics.

The project transforms traditional subjective recruitment processes into objective decision-making systems through predictive analytics and automated candidate evaluation.

---

# 🎯 Business Problem

Traditional recruitment processes often suffer from:
- Subjective hiring bias
- High operational cost
- Poor hiring decisions
- Low scalability in candidate screening

According to Harvard Business Review:
- 80% employee turnover is caused by poor hiring decisions.
- A bad hire can cost companies up to 200% of annual salary.

---

# 🚀 Goals & Objectives

## Goals
- Improve hiring accuracy
- Reduce recruitment bias
- Increase operational efficiency

## Objectives
- Build predictive recruitment model
- Conduct fairness & bias analysis
- Automate candidate screening
- Improve HR decision-making

---

# 🧠 Machine Learning Workflow

## CRISP-DM Workflow

1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modeling
5. Evaluation
6. Deployment

---

# 📊 Dataset Information

| Information | Value |
|---|---|
| Rows | 1,500 |
| Features | 11 |
| Numerical Features | 7 |
| Categorical Features | 3 |
| Target | HiringDecision |

---

# 🔍 Feature Engineering

## ExperienceLevel
Transforms ExperienceYears into:
- Junior
- Medior
- Senior

---

# 🧹 Data Preprocessing

## Feature Scaling
- StandardScaler

## Feature Encoding
- One Hot Encoding
- Ordinal Encoding

## Data Balancing
- SMOTE

SMOTE was used to handle imbalanced data by generating synthetic minority samples.

---

# 🤖 Models Used

| Model | F1 Score | ROC-AUC |
|---|---|---|
| Logistic Regression | 72.3% | 88.6% |
| Random Forest | 81.6% | 91.0% |
| XGBoost | 84.7% | 91.3% |
| Decision Tree | 70.1% | 80.1% |
| KNN | 45.3% | 62.5% |

---

# 🏆 Best Model – XGBoost

## Performance

| Metric | Score |
|---|---|
| Accuracy | 91.3% |
| Precision | 85.7% |
| Recall | 83.7% |
| F1-Score | 84.7% |
| ROC-AUC | 91.3% |

## Best Hyperparameters

| Hyperparameter | Value |
|---|---|
| n_estimators | 300 |
| max_depth | 6 |
| learning_rate | 0.1 |
| gamma | 0.2 |
| reg_lambda | 50 |

---

# ⚖ Fairness & Bias Analysis

The project includes fairness evaluation to reduce recruitment bias.

## Key Findings
- Internal recruitment strategy strongly influences hiring predictions.
- Higher education levels increase hiring probability.
- Demographic variables like age have minimal impact.

---

# 💰 Business Impact

## Cost Efficiency

| Scenario | Total Cost |
|---|---|
| Without Model | Rp 4.950.000.000 |
| With Model | Rp 1.386.000.000 |

## Result
- Cost Saving: Rp 3.564 Billion
- Efficiency Improvement: 72%

---

# 📈 Dashboard Implementation

The system includes an interactive Streamlit dashboard:
- Real-time candidate prediction
- Dynamic parameter adjustment
- Automated hiring recommendation

---

# 🖼 Dashboard Preview

<img src="slide/dashboard.png" width="800">

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- SMOTE
- Streamlit
- Matplotlib
- Seaborn

---

# 📌 Key Features

- Automated Candidate Screening
- HR Analytics Dashboard
- Bias Detection
- Fairness Evaluation
- Predictive Recruitment Modeling
- Cost Efficiency Analysis

---


# 🙏 Thank You
