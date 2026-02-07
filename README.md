# HR-ANALYTICS-ML-PROJECT
Predictive HR Analytics project combining attrition modeling, employee segmentation, explainable AI, and risk scoring to support data-driven retention strategy.

📊 HR Analytics ML Project — Attrition Prediction & Employee Segmentation
🚀 Project Overview
This project builds an end-to-end HR Analytics machine learning framework to predict employee attrition risk and segment the workforce using behavioral and tenure features.
The solution combines predictive modeling + clustering + explainable AI + risk scoring + dashboard deployment to move HR analytics from descriptive reporting to decision-ready intelligence.
📌 Built using a public dataset for portfolio and learning purposes only.

🎯 Business Problem
Employee attrition is costly and often detected too late.
Traditional HR reports are descriptive, not predictive.
This project answers:
Who is at risk of leaving?
What factors drive attrition?
What employee segments exist?
How can HR act proactively?

🧠 Solution Approach
The project is built in four analytical layers:

  🔍 1️⃣ Exploratory HR Analytics
Performed HR-focused EDA to uncover attrition patterns across:
Overtime behavior
Compensation levels
Job & environment satisfaction
Employee tenure
Work-life balance
Key finding: Attrition is strongly linked to workload, satisfaction, and pay factors.

  🤖 2️⃣ Attrition Prediction (Supervised ML)
Built classification models:
Logistic Regression (baseline)
Random Forest (primary model)
Enhancements:
Class imbalance handling (class_weight="balanced")
Confusion matrix & classification metrics
ROC-AUC evaluation

  🧠 3️⃣ Explainable AI (SHAP)
Applied SHAP explainability to interpret model predictions.
SHAP enables:
Feature-level impact visualization
Individual employee risk explanation
Transparent HR decision support
This converts the model from a black box → interpretable system.

  👥 4️⃣ Employee Segmentation (Unsupervised ML)
Used KMeans clustering on scaled HR features:
Income (log transformed)
Tenure
Satisfaction
Experience
Work-life balance
Validation methods:
  Elbow method
  Silhouette score
PCA visualization
Result: Distinct workforce segments with different attrition risk profiles.

  📈 5️⃣ HR Risk Scoring System
Converted model probabilities into HR-usable categories:
Probability	Risk Level
Low	< 0.30
Medium	0.30–0.60
High	> 0.60
Enables prioritization of retention interventions.

🛠️ Tech Stack
Python
Pandas, NumPy
SHAP
KMeans Clustering
PCA
Matplotlib, Seaborn

📊 Key Insights
-- Overtime is a major attrition risk signal
-- Lower income bands show higher exit probability
-- Satisfaction metrics act as early warning indicators
-- Early-tenure employees are more vulnerable
-- Workforce divides into behavior-based segments
-- Prediction + segmentation together improves HR targeting

💼 Business Impact
-- This framework enables HR teams to:
-- Detect attrition risk early
-- Understand key drivers behind exits
-- Segment employees by behavior patterns
-- Apply targeted retention strategies
-- Move toward predictive HR decision-making
