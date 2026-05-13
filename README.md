![alt text](https://github.com/fadlinur/Final-Project/blob/main/streamlit%20smote/download.png?raw=true)


# HIRESIGHTS – Data-Driven Recruitment System

Optimizing Biased Talent Acquisition Through Data-Driven HR Analytics

---

## 👥 Team Members

| Name | Role |
|---|---|
| Fadli Nurrizky | PM & Engineering |
| Irfan Aulia Rahman | Analyst & Scientist |
| Shan Ramadhan | Analyst & Scientist |

---

# 📑 Final Presentation

[Download Presentation](./Final%20Presentation.pptx)

---

# 📌 Project Overview

HIRESIGHTS is a machine learning-based recruitment system designed to optimize hiring decisions using HR analytics and predictive modeling.

The system transforms conventional recruitment processes into objective and data-driven decision-making systems.

---

# 🧠 CRISP-DM Workflow

## Stage 0 – Business Understanding
Business understanding, problem identification, goals, and objectives.

## Stage 1 – Data Understanding
Exploratory Data Analysis (EDA), descriptive statistics, and feature analysis.

## Stage 2 – Data Preparation
Data cleaning, preprocessing, encoding, feature engineering, and SMOTE balancing.

## Stage 3 – Modeling
Machine learning model training and hyperparameter tuning.

## Stage 4 – Evaluation & Deployment
Model evaluation, fairness analysis, business impact analysis, and Streamlit deployment.

---

# 📂 Project Structure

📊 Dataset Information
Information	Value
Rows	1,500
Features	11
Numerical Features	7
Categorical Features	3
Target	HiringDecision
🧹 Data Preprocessing
Feature Scaling
StandardScaler
Feature Encoding
One Hot Encoding
Ordinal Encoding
Data Balancing
SMOTE

SMOTE is used to solve imbalanced data problems by generating synthetic minority class samples.

🤖 Machine Learning Models
Model	F1-Score	ROC-AUC
Logistic Regression	72.3%	88.6%
Random Forest	81.6%	91.0%
XGBoost	84.7%	91.3%
Decision Tree	70.1%	80.1%
KNN	45.3%	62.5%
🏆 Best Model – XGBoost
Metric	Score
Accuracy	91.3%
Precision	85.7%
Recall	83.7%
F1-Score	84.7%
ROC-AUC	91.3%
📊 Insight Visualization
Feature Importance
<img src="picture/Feature Importance.png" width="800">
Confusion Matrix
<img src="picture/Confusion Matrix.png" width="800">
Interview Score Analysis
<img src="picture/InterviewScore.png" width="800">
Skill Score Analysis
<img src="picture/SkillScore.png" width="800">
Personality Score Analysis
<img src="picture/PersonalityScore.png" width="800">
Education Level Analysis
<img src="picture/EducationLevel is significant to HiringDecision.png" width="800">
Experience Level Analysis
<img src="picture/ExperienceLevel is significant to HiringDecision.png" width="800">
Recruitment Strategy Analysis
<img src="picture/RecruitmentStrategy is significant to HiringDecision.png" width="800">
⚖ Fairness & Bias Analysis

Key findings:

Internal recruitment strategy strongly affects hiring prediction.
Higher education level increases hiring probability.
Age and demographic factors have minimal influence.
💰 Business Impact
Scenario	Total Cost
Without Model	Rp 4.950.000.000
With Model	Rp 1.386.000.000
Result
Cost Saving: Rp 3.564 Billion
Efficiency Improvement: 72%
📈 Dashboard Preview
<img src="picture/dashboard.png" width="800"> <img src="picture/dashboard1.png" width="800">
🛠 Technologies Used
Python
Pandas
NumPy
Scikit-learn
XGBoost
SMOTE
Streamlit
Matplotlib
👨‍💻 Author

Fadli Nurrizky
🙏 Thank You
