# LEAD SCORE CASE STUDY

This project builds a machine learning model to predict lead conversion probability
for an online education company, helping sales teams focus on high-value leads.

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## Problem Statement
X Education receives thousands of leads daily, but only a small fraction converts.
The goal is to identify leads most likely to convert using historical data.

## Key Highlights
- Cleaned and processed ~9,200 lead records
- Performed EDA and feature engineering
- Selected 17 key features using RFE with Logistic Regression
- Achieved ~80% test accuracy and 0.89 ROC-AUC
- Implemented probability-based lead scoring with a 0.37 cutoff
  
## Model Performance
| Metric | Train | Test |
|------|------|------|
| Accuracy | 81.41% | 80.13% |
| ROC-AUC | 0.89 | 0.89 |

## Approach
- Data cleaning and outlier handling
- Univariate & bivariate analysis
- Feature selection using RFE
- Logistic Regression model training and evaluation

## Business Impact
The model helps sales teams prioritize high-conversion leads, improving efficiency
and allowing flexible targeting using adjustable probability thresholds.






