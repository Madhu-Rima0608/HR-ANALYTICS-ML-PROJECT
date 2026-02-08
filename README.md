# 📊 HR Analytics ML Project — Predicting Employee Attrition

## 🚀 Project Overview

Employee attrition creates significant business challenges including replacement costs, productivity loss, and knowledge leakage. This project builds a People Analytics machine learning framework to **predict employee attrition risk** and translate HR data into actionable retention insights.

The project combines exploratory data analysis, classification modeling, risk-focused evaluation, clustering-based segmentation, and SHAP explainability to create a decision-support approach for proactive HR strategy.

> ⚠️ This is a personal learning project built using public/sample HR data. It is not connected to any proprietary organizational dataset.

---

## 🎯 Business Objective

**Goal:** Identify employees with high attrition risk early so HR teams can take proactive retention actions instead of reactive replacement hiring.

**Key Questions Addressed:**

* Which factors most influence employee attrition?
* Can attrition risk be predicted using ML models?
* How can model outputs be translated into HR decision signals?
* Which employee segments show higher risk patterns?

---

## 🗂 Dataset Description

The dataset contains employee-level HR attributes including:

* Demographics
* Job role & department
* Compensation features
* Overtime exposure
* Satisfaction & engagement indicators
* Performance & tenure variables

**Target Variable:** Attrition (Yes/No)

---

## 🧠 Analytical Workflow

### 1️⃣ Data Preparation

* Data cleaning and preprocessing
* Categorical encoding
* Feature selection
* Outlier and consistency checks

### 2️⃣ Exploratory Data Analysis (EDA)

* Attrition distribution analysis
* Overtime vs attrition patterns
* Satisfaction vs retention trends
* Behavioral driver exploration

### 3️⃣ Modeling Approach

Two-model strategy used:

**Logistic Regression**

* High interpretability
* Coefficient-level impact understanding

**Random Forest**

* Captures non-linear relationships
* Stronger predictive performance

### 4️⃣ Class Imbalance Handling

* Addressed imbalance in attrition classes before model training
* Prevented biased predictions toward majority class

### 5️⃣ Risk-Focused Evaluation

* Confusion matrix driven evaluation
* Priority: **reduce false negatives** (missing high-risk employees)
* Business-aligned metric interpretation

### 6️⃣ Explainable AI (SHAP)

* SHAP values used for feature-level explainability
* Identified top drivers influencing attrition predictions
* Improved model transparency for HR decision context

### 7️⃣ Employee Segmentation (Clustering)

* Behavioral clustering applied
* Identified workforce segments with differing attrition risk patterns

---

## 💡 Key Insights

* Employees with **higher overtime exposure** show elevated attrition probability
* **Low job satisfaction** strongly correlates with exit likelihood
* Engagement and workload variables act as early warning signals
* Risk scoring approach supports proactive retention strategy

---

## 🛠 Tools & Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* SHAP
* Jupyter Notebook

---

## ▶️ How to Run This Project

### Step 1 — Clone the Repository

```
git clone https://github.com/Madhu-Rima0608/HR-ANALYTICS-ML-PROJECT.git
```

### Step 2 — Install Dependencies

```
pip install -r requirements.txt
```

### Step 3 — Open Notebook

Open the Jupyter notebook file and run all cells sequentially.

---

## 📈 Project Outputs

* Attrition prediction models
* Feature importance analysis
* SHAP explainability plots
* Risk-focused evaluation metrics
* Workforce segmentation insights
* Business-oriented PPT summary

---

## 📌 Business Value

This framework demonstrates how HR data can be transformed into:

* Early attrition warning signals
* Risk-based employee prioritization
* Data-driven retention strategy inputs
* Explainable ML for HR decision support

---

## 👩‍💻 Author

**Madhurima Roy**
Data Analytics & People Analytics Enthusiast

LinkedIn: [https://www.linkedin.com/in/madhurima-roy-a48009249](https://www.linkedin.com/in/madhurima-roy-a48009249)
GitHub: [https://github.com/Madhu-Rima0608](https://github.com/Madhu-Rima0608)

---

## ⭐ If You Found This Useful

Consider starring the repository and sharing feedback or suggestions for improvement.
