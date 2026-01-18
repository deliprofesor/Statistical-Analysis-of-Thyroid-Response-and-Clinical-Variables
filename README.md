# Statistical-Analysis-of-Thyroid-Response-and-Clinical-Variables

## Thyroid Cancer Recurrence & Treatment Response Analysis

This project performs a comprehensive clinical data analysis and predictive modeling on a thyroid cancer dataset. The goal is to identify key clinical predictors of treatment success and build machine learning models to forecast disease recurrence.

##  Project Overview

The study is structured into three main phases:
1.  **Statistical Inference:** Conducting hypothesis tests (Chi-Square, ANOVA) to determine which clinical variables (Age, Risk Group, Stage, etc.) significantly impact patient outcomes ($p < 0.05$).
2.  **Exploratory Data Analysis (EDA):** Visualizing complex relationships between TNM staging, pathology, and treatment response.
3.  **Predictive Modeling:** Developing classification algorithms to predict the likelihood of cancer recurrence (`Recurred`) based on pre-operative and post-operative data.

##  Repository Structure

```text
thyroid-cancer-analysis/
├── data/
│   ├── Thyroid_Diff.csv       # Original dataset
├── notebooks/
│   ├── 01_EDA_Statistical_Tests.ipynb    # Data profiling and statistical analysis
│   ├── 02_Model_Training.ipynb           # ML training, tuning, and evaluation
├── reports/
│   └── figures/               # Generated charts and confusion matrices
├── requirements.txt           # Python dependencies
└── README.md                  # Project documentation
