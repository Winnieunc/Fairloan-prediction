# FairLoan Prediction: Mitigating Bias in Mortgage Approvals

This project investigates how machine learning models, even when technically fair, can reinforce historical bias in home loan approvals due to redlining's legacy.

We use the 2018 HMDA dataset focused on Wake County, NC to explore:
- Racial disparity in application approvals
- The effects of reweighing and threshold tuning
- Model interpretability with SHAP

## Contents
- `fairloan_analysis.ipynb`: Main analysis notebook with modeling, fairness checks, and mitigation.
- `images/`: Visualizations of bias metrics and SHAP output.

## Methods
- **Models:** Logistic Regression, Random Forest Classifier
- **Bias Metrics:** Disparate Impact, Equal Opportunity Difference, Accuracy by Race
- **Mitigation:** Reweighing, Threshold Tuning
- **Interpretability:** SHAP Value Plots

## Data Access
- HMDA 2018 (Wake County): [Download CSV](https://drive.usercontent.google.com/u/0/uc?id=1pDqazBinw3E3-1OyqzfACq5SrBqwYs_4&export=download)

## Key Insights
- Historical exclusion still affects who appears in the data
- Even when models are fair, they operate on incomplete histories
- Reweighing and threshold tuning can reduce disparate impact but do not solve pre-denial bias

## Tools Used
Python, pandas, scikit-learn, SHAP, matplotlib, seaborn, Fairlearn


---

*By Winnie Ekwegh | Master of Data Science, UNC Chapel Hill*
