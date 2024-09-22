# Capstone Project Module 03 - Telco Customer Churn

---

## Background
WirelessUS is facing challenges in retaining customers amidst a highly competitive telecommunications industry. The high churn rate indicates the need for better retention strategies. Currently, the company uses a simple rule-based method to identify at-risk customers, but this method is not effective in detecting complex churn patterns. Therefore, this project aims to build a more accurate machine learning-based churn prediction model to identify customers at risk of leaving, allowing the company to take more effective preventive measures.

## Problem Statement
1. How can WirelessUS more accurately predict which customers will churn compared to the currently used rule-based method?
2. How can the new prediction model help WirelessUS identify key factors influencing churn and improve customer retention strategies?

## Goals
1. Develop a machine learning-based churn prediction model that outperforms the previous rule-based method.
2. Identify key variables influencing customer churn to support better decision-making.

## Analytic Approach
- Utilize machine learning algorithms such as RandomForestClassifier, DecisionTreeClassifier, XGBClassifier, CatBoostClassifier, GradientBoostingClassifier, LGBMClassifier, KNeighborsClassifier, and PassiveAggressiveClassifier to build the churn prediction model.
- Conduct exploratory data analysis on customer data to identify factors contributing to churn.
- Apply feature engineering and data preprocessing techniques to maximize model performance.

## Metric Evaluation
- **F2-Score (Primary Focus):** F2-Score is chosen as the primary metric because it emphasizes recall, aiming to identify as many at-risk customers as possible. This is crucial since the cost of acquiring new customers is much higher than the cost incurred due to false positives. By prioritizing recall, the company can minimize the loss of customers who are actually at risk of churning.
- **F1-Score:** An additional metric to ensure a balance between precision and recall. While F1-Score is important, the primary focus remains on F2-Score to maximize the detection of at-risk customers.
- **AUC-ROC:** Used as a supporting metric to measure the model's ability to distinguish between churn and non-churn customers overall.

By focusing on the F2-Score, WirelessUS can ensure that its customer retention strategy is more effective and targeted, reducing churn and retaining customers more efficiently.

## How to Use
1. Clone this repository.
2. Install the necessary dependencies listed in `requirements.txt`.
3. Run the Jupyter Notebook to reproduce the analysis and model.
4. Modify the notebook as needed for your use case.

## Requirements
- Python 3.8+
- Pandas
- Scikit-Learn
- XGBoost
- CatBoost
- LightGBM
- Matplotlib
- Seaborn

Install dependencies using:

```bash
pip install 
```

## Contact
For any questions or feedback, please contact:

- **Faizal Lutfi Yoga Triadi**
- [Email](mailto:faizal2jz@gmail.com)

---
