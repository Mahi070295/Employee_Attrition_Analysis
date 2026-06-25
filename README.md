
# Employee Attrition Analysis & Prediction

## Overview
Analysis of IBM HR Analytics dataset (1,470 employees) to identify key drivers 
of employee attrition and build a predictive model to flag at-risk employees.

## Key Findings
- Overall attrition rate: ~16%
- OverTime is the strongest single driver — 30.5% attrition vs 10.4% for non-overtime employees
- Tenure/seniority strongly protective — newer employees at higher risk
- Sales Representative and Lab Technician roles show elevated attrition risk

## Methodology
- Exploratory data analysis (Python: Pandas, Matplotlib, Seaborn)
- Correlation analysis on numeric features
- Predictive modeling: Logistic Regression vs Random Forest (scikit-learn)
- Final model: Logistic Regression (70% recall on attrition class, 
  outperforming Random Forest's 6% recall despite higher overall accuracy)

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, scikit-learn

## Dataset
IBM HR Analytics Employee Attrition & Performance (Kaggle)
