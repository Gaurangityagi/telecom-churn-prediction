# Telecom Customer Churn Prediction

## Business Problem
26% of telecom customers are churning. This project builds a 
predictive model to identify high-risk customers before they leave,
enabling proactive retention interventions.

## Dataset
- IBM Telco Customer Churn (Kaggle)
- 7,043 customers, 21 features
- Target: Churn (Yes/No) — 26% positive class

## Approach
1. EDA — identified key churn drivers
2. Preprocessing — encoding, scaling, train/test split
3. Modeled with Logistic Regression, Random Forest, XGBoost
4. Evaluated with AUC-ROC, Precision, Recall, F1

## Results
| Model | AUC |
|---|---|
| Logistic Regression | 0.84 |
| Random Forest | 0.82 |
| XGBoost | 0.86 ← best |

## Key Findings
- Tenure is the strongest predictor — customers churning mostly 
  in first 12 months
- Month-to-month contracts have 3x higher churn than annual
- High monthly charges significantly increase churn probability

## Tools
Python (pandas, scikit-learn, XGBoost, matplotlib, seaborn)
```


  seaborn, Jupyter Notebook
