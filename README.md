# Predicting-Unmet-Need-For-Family-Planning-
Code for predicting unmet need for family planning in Bangladesh using BDHS 2022 data.
# Predicting Unmet Need for Family Planning in Bangladesh (BDHS 2022)

This repository contains all author-generated code used in the manuscript:

**Predicting Unmet Need for Family Planning in Bangladesh Using Machine Learning Approaches**

## Data
Data were obtained from the Bangladesh Demographic and Health Survey (BDHS) 2022.
Due to DHS data sharing restrictions, raw data are not publicly available.
Researchers can request access via: https://dhsprogram.com

## Analysis workflow
1. Data preprocessing and variable construction
2. Multinomial logistic regression
3. Random Forest and XGBoost models
4. SHAP based analysis
5. Panel analysis for Multinomial logistic regression and forest plots


R version 4.5.2 (2025-10-31 ucrt)
Platform: x86_64-w64-mingw32/x64
Running under: Windows 11 x64 (build 26100)

Key packages:
caret, randomForest, xgboost, Boruta, shapviz, ggplot2

## Reproducibility
All scripts are numbered and can be executed sequentially after placing the BDHS dataset in the `/data` directory.
