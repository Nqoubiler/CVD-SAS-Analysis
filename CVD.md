# Cardiovascular Disease (CVD) Risk Factor Analysis using SAS

## Overview

This project involved a full statistical analysis of cardiovascular disease (CVD) patient data to identify the most important factors associated with disease risk and support evidence-based medical decision-making. Using SAS, I applied inferential statistics, predictive modelling, and model diagnostics to convert clinical data into meaningful insights.

The study was completed as part of the STAT305 final project at the University of KwaZulu-Natal.

---

## Business / Clinical Objective

The objective of this analysis was to determine:

- Which patient characteristics significantly increase CVD risk
- Which variables remain important after adjustment for other factors
- How accurately CVD outcomes can be predicted using logistic regression
- Which variables healthcare professionals should prioritise for monitoring and early intervention

---

## Dataset Summary

- **Observations:** 299 patients
- **Variables:** 11 total (1 response + 10 predictors)

### Predictors Included:

- Age  
- Anaemia  
- High Blood Pressure  
- Diabetes  
- Gender  
- Smoking  
- Creatinine Phosphokinase  
- Ejection Fraction  
- Platelets  
- Serum Sodium  

### Response Variable:

- Presence of Cardiovascular Disease Event

---

## Tools & Technologies Used

- **SAS**
- PROC FREQ
- PROC LOGISTIC
- PROC UNIVARIATE
- PROC SGPLOT

---

## Analytical Methods Applied

### Exploratory Data Analysis

Used summary statistics and visualizations to understand variable distributions, identify unusual values, and assess data quality.

### Association Testing

Used Chi-square tests to examine relationships between categorical risk factors and CVD outcomes.

### Predictive Modelling

Built multiple logistic regression models to estimate the probability of CVD occurrence.

### Model Selection

Compared four candidate models using **Akaike Information Criterion (AIC)** to identify the most efficient model balancing fit and complexity.

### Model Diagnostics

Assessed:

- Hosmer-Lemeshow Goodness-of-Fit
- Deviance / Pearson statistics
- Influential observations using DFBETAs

---

## Key Results

### Final Best Performing Model Included:

- Age
- Ejection Fraction
- Serum Sodium

### Significant Predictors

| Variable | Insight |
|---------|---------|
| Age | Older patients had higher CVD risk |
| Ejection Fraction | Lower heart pumping efficiency strongly increased risk |
| Serum Sodium | Lower sodium levels were associated with increased risk |

### Variables Not Statistically Significant After Adjustment

- Smoking
- Anaemia
- High Blood Pressure
- Diabetes
- Gender

This indicates that while some factors may appear important individually, they were less predictive once stronger clinical variables were included.

---

## Model Performance Insights

- Lowest AIC selected as final model
- Good calibration based on Hosmer-Lemeshow test (p > 0.05)
- No evidence of overdispersion
- Influential observation checks showed model stability

This suggests the model was statistically reliable and suitable for interpretation.

---

## Practical Recommendations

Healthcare teams could use these findings to prioritise:

- Earlier screening for older patients
- Immediate monitoring of patients with reduced ejection fraction
- Close management of abnormal sodium levels
- Data-driven triage for high-risk cardiac patients

This can support improved treatment planning and more efficient allocation of medical resources.

---

## Skills Demonstrated

- Statistical Modelling
- Logistic Regression
- Healthcare Analytics
- Hypothesis Testing
- Model Diagnostics
- Data Interpretation
- SAS Programming
- Predictive Analytics
- Evidence-Based Reporting

---

## Why This Project Matters

This project demonstrates my ability to work with real-world health datasets, apply advanced statistical methods, validate predictive models, and communicate findings clearly for decision-making environments such as healthcare, insurance, research, and analytics.

---

## Author

Nqobile Sithole  
BSc Data Science Graduate  
Statistics & Computer Science  
University of KwaZulu-Natal
