# Employee Attrition Prediction using Machine Learning

## 📌 Project Overview

Employee attrition is a critical challenge for organizations as it impacts productivity, recruitment costs, and overall business performance. This project uses Machine Learning techniques to predict employee attrition and identify the key factors that influence employee turnover.

The goal is to help HR teams make proactive decisions and improve employee retention strategies through data-driven insights.

---

## 🎯 Objectives

* Analyze employee data and understand attrition patterns.
* Perform data cleaning and preprocessing.
* Explore factors affecting employee turnover.
* Build and compare multiple machine learning models.
* Identify employees at risk of leaving.
* Generate actionable HR recommendations.

---

## 📊 Dataset

**Dataset:** IBM HR Analytics Employee Attrition Dataset

The dataset contains employee-related information such as:

* Age
* Department
* Job Role
* Monthly Income
* Education
* Overtime Status
* Business Travel
* Years at Company
* Job Satisfaction
* Attrition Status

Target Variable:

**Attrition**

* Yes = Employee Left
* No = Employee Stayed

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📈 Exploratory Data Analysis

The following analyses were performed:

* Attrition distribution analysis
* Department-wise attrition comparison
* Job Role attrition analysis
* Monthly income distribution
* Work-life balance analysis
* Years at company analysis

Key observations were documented throughout the notebook.

---

## 🤖 Machine Learning Models

The following models were trained and evaluated:

1. Logistic Regression
2. Random Forest Classifier
3. Gradient Boosting Classifier

---

## 📋 Model Evaluation

Models were compared using:

* Precision
* Recall
* F1-Score
* ROC-AUC Score
* Confusion Matrix

### Best Performing Model

**Logistic Regression**

Reason:

* Highest Recall Score
* Strong ROC-AUC Performance
* Better identification of employees at risk of attrition

---

## 🔍 Key Findings

The analysis identified several important factors contributing to employee attrition:

* Overtime work
* Frequent business travel
* Laboratory Technician roles
* Sales-related positions
* Delayed promotions
* Job level
* Total working experience

These factors showed the strongest relationship with employee turnover.

---

## 💡 HR Recommendations

* Reduce excessive overtime.
* Improve work-life balance initiatives.
* Review business travel requirements.
* Strengthen career development programs.
* Implement targeted retention strategies for high-risk roles.
* Use predictive analytics for proactive employee retention.

---

## 📂 Project Structure

```text
Employee-Attrition-Prediction/
│
├── analysis.ipynb
├── summary.pdf
├── WA_Fn-UseC_-HR-Employee-Attrition.csv
├── charts/
│   ├── confusion_matrix.png
│   ├── feature_importance.png
│   └── roc_curve.png
└── README.md
```

## 🚀 Future Improvements

* Implement XGBoost and LightGBM models.
* Address class imbalance using SMOTE.
* Build an interactive HR dashboard.
* Deploy the model as a web application.
* Continuously retrain using updated employee data.

---

## 👩‍💻 Author

**Kumkum Pandey**

B.Tech CSE | Graphic Era Hill University

Passionate about Data Analytics, Machine Learning, and AI-driven solutions.
