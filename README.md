# cvd-sas-analysis
# Cardiovascular Disease (CVD) Risk Factor Analysis using SAS
 Logistic Regression and CVD Risk Factors
 
This project explores risk factors associated with cardiovascular disease (CVD) using statistical methods in SAS. It was completed as part of the STAT305 final project at the University of KwaZulu-Natal.

## Dataset

The dataset includes 299 patients and 10 predictors:
- Age, Anaemia, High Blood Pressure, Diabetes, Gender, Smoking
- Creatinine Phosphokinase, Ejection Fraction, Platelets, Serum Sodium

## Goals

- Identify significant risk factors for CVD
- Explore association between categorical variables and CVD status using Chi-square tests
- Fit logistic regression models and compare using AIC
- Assess model fit using goodness-of-fit tests and influential observation analysis

## Tools & Techniques

- **SAS Procedures**: `PROC FREQ`, `PROC UNIVARIATE`, `PROC LOGISTIC`, `PROC SGPLOT`
- **Statistical Tests**: Chi-square, Logistic regression, Hosmer-Lemeshow test, DFBETAs
- **Model Selection**: AIC-based model comparison across four logistic models

## Key Findings

- **Significant predictors**: Age, Ejection Fraction, Serum Sodium
- **Not significant**: Smoking, Anaemia, Diabetes, Gender, High Blood Pressure (after adjustment)
- Final model fits well with no overdispersion and identifies older age and low ejection fraction/sodium as key risk factors.

## License

This project is for academic purposes. Do not distribute without permission.

