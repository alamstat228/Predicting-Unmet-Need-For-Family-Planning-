# Predicting Unmet Need for Family Planning (BDHS 2022)

This repository contains all author-generated scripts used to reproduce the analysis and results reported in:

**Alam et al. (2026). Predicting Unmet Need for Family Planning in Bangladesh Using Machine Learning Approaches: Insights from BDHS 2022 Dataset**  
*Submitted to PLOS Global Public Health*

---

## 📦 Overview

This project uses machine learning and traditional statistical methods to **predict unmet need for family planning** in Bangladesh using the **Bangladesh Demographic and Health Survey (BDHS) 2022**.

The analysis includes:
- Data preprocessing
- Feature selection (Boruta)
- Multinomial logistic regression
- Random Forest and XGBoost
- SHAP (Shapley Additive exPlanations) for model interpretation

---

## 📁 Repository Structure


---

## 🧠 Data Access

The raw BDHS 2022 dataset is **not included** in this repository due to data use restrictions.

To obtain the dataset:

1. Register at **The DHS Program**: https://dhsprogram.com  
2. Request access to *Bangladesh DHS 2022 (IR file)*  
3. After approval, download the data to your local machine

Place the downloaded dataset in the `/data/` folder (not committed here).

---

## 🛠 Dependencies & Software

This analysis was performed in **R**. The required packages include (but are not limited to):


- caret  
- randomForest  
- xgboost  
- Boruta  
- shapviz  
- ggplot2  
- haven  
- dplyr

To install dependencies:

```r
install.packages(c("caret","randomForest","xgboost","Boruta","shapviz","ggplot2","haven","dplyr"))

