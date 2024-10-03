# Telco-Churn-Analysis

## Conclusion from analysis 

### Observation:
-  Model performance:
    - Logistic Regression:
        - Accuracy: 0.79
        - AUC: 0.88
    - Random Forest:
        - Accuracy: 0.82
        - AUC: 0.89
    - Both Logistic regression and Random Forest models perform well after handling class imbalance and feature selection.
	- Random Forest typically has higher accuracy and better ability to capture complex patterns.
- key predictors of Churn:
    - Tenure: Lower tenure increases the likelihood of churn.
	- Contract_Type: Short-term contracts are associated with higher churn.
	- MonthlyCharges: Higher charges are linked to increased churn.


### Recommendations:
- Customer Retention Strategies:
  - Tenure
    - Implement loyalty programs targeting new customers to increase tenure.
  - Contract
	- Encourage customers to switch to long-term contracts through incentives.
	- Provide discounts for customers who switch to longer-term contracts.
	- Create attractive packages that encourage customers to opt for longer contracts.
  - Monthly Chargers
	- Re-evaluate pricing models to ensure competitiveness.
