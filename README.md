# Customer-Churn-Prediction
# Customer Churn Prediction using Machine Learning

## Project Overview

Customer churn is one of the biggest challenges faced by subscription-based businesses such as telecom, banking, and SaaS companies. This project predicts whether a customer is likely to discontinue a service using machine learning techniques. The project covers the complete machine learning workflow, including data cleaning, exploratory data analysis (EDA), preprocessing, model building, evaluation, and business recommendations.

---

## Problem Statement

Customer retention is more cost-effective than acquiring new customers. Identifying customers who are likely to churn enables businesses to take proactive measures and improve customer satisfaction.

---

## Objectives

* Perform data cleaning and preprocessing.
* Explore customer behavior using Exploratory Data Analysis (EDA).
* Build customer churn prediction models.
* Compare multiple classification algorithms.
* Evaluate model performance using Accuracy, Precision, Recall, F1-Score, and ROC-AUC.
* Identify the most important factors contributing to customer churn.
* Provide business recommendations based on the findings.

---

## Dataset

**IBM Telco Customer Churn Dataset**

The dataset contains customer demographic information, account details, service subscriptions, billing information, and whether a customer has churned.

### Target Variable

* **Churn**

  * Yes
  * No

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Joblib

---

## Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Understanding
4. Data Cleaning
5. Exploratory Data Analysis (EDA)
6. Data Preprocessing
7. Feature Selection
8. Train-Test Split
9. Logistic Regression
10. Random Forest
11. XGBoost
12. Model Evaluation
13. Feature Importance
14. Save Best Model
15. Business Conclusion

---

## Exploratory Data Analysis (EDA)

The following analyses were performed:

* Churn Distribution
* Gender vs Churn
* Senior Citizen vs Churn
* Partner vs Churn
* Dependents vs Churn
* Contract Type vs Churn
* Internet Service vs Churn
* Payment Method vs Churn
* Monthly Charges vs Churn
* Tenure vs Churn
* Correlation Heatmap

These visualizations helped identify important churn patterns and supported the feature selection process.

---

## Machine Learning Models

The following classification models were trained and evaluated:

* Logistic Regression
* Random Forest
* XGBoost

---

## Evaluation Metrics

Model performance was evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC
* Confusion Matrix
* ROC Curve

---

## Project Structure

```text
Customer-Churn-Prediction/
│
├── data/
│   ├── WA_Fn-UseC_-Telco-Customer-Churn.csv
│   └── cleaned_customer_churn.csv
│
├── notebooks/
│   └── Customer_Churn_Prediction.ipynb
│
├── models/
│   └── best_model.pkl
│
├── images/
│   ├── churn_distribution.png
│   ├── contract_vs_churn.png
│   ├── payment_method_vs_churn.png
│   ├── tenure_distribution.png
│   ├── heatmap.png
│   ├── feature_importance.png
│   ├── confusion_matrix_lr.png
│   ├── confusion_matrix_rf.png
│   ├── confusion_matrix_xgb.png
│   ├── roc_curve.png
│   └── model_comparison.png
│
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

---

## Key Findings

* Customers with month-to-month contracts are more likely to churn.
* Customers with shorter tenure have a higher probability of leaving the service.
* Higher monthly charges are associated with increased churn.
* Contract type, tenure, and monthly charges are among the most influential features for churn prediction.
* The best-performing model was selected based on Accuracy, Recall, and ROC-AUC.

---

## Business Recommendations

* Encourage customers to switch to long-term contracts.
* Identify high-risk customers using the prediction model and provide personalized retention offers.
* Reward loyal customers with discounts or exclusive benefits.
* Review pricing strategies for customers with high monthly charges.
* Monitor customer behavior regularly and retrain the model with updated data.

---

## Future Improvements

* Perform hyperparameter tuning to improve model performance.
* Experiment with additional ensemble learning algorithms.
* Build a web application using Streamlit or Flask for real-time churn prediction.
* Test the model on other telecom or banking churn datasets.

---

## How to Run the Project

1. Clone the repository.
2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook:

```bash
jupyter notebook
```

4. Run the notebook cells sequentially to reproduce the analysis and model results.

---

## Author

**Anmol Rana**

Computer Science Engineering Graduate specializing in Data Analytics with hands-on experience in Python, SQL, Power BI, and Machine Learning.
