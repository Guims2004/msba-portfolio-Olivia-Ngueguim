Business Problem 

Customer churn directly impacts revenue, marketing efficiency, and long-term growth.
The goal of this project is to analyze historical customer data to identify key drivers of churn and build a predictive model that flags customers at high risk of leaving.

3 key results

Month-to-month contracts show the highest churn rates, significantly higher than longer-term contracts.
Pricing and product configuration (e.g., monthly fee, add-ons, internet technology) are strong drivers of churn behavior.
An XGBoost classification model outperformed baseline approaches in cross-validation, providing a reliable framework for churn prediction and feature importance analysis.

How to Run the Code

Clone or download this repository.
Ensure retentiondata_case.csv is placed in the same directory as the notebooks.
Create and activate a virtual environment (optional but recommended).
Install required packages: pip install pandas numpy scikit-learn xgboost shap matplotlib seaborn
Run the EDA notebook first to explore and validate the dataset.

Limitation
If pricing strategy, product offerings, or market conditions change, model performance may degrade over time. 
Regular retraining and monitoring are recommended to maintain predictive accuracy.
