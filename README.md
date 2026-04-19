# Alzheimer's Disease Risk Factor Analysis (Python Project)

This project explores risk factors associated with Alzheimer’s Disease (AD) using statistical analysis and machine learning techniques. The goal is to identify significant predictors and understand how demographic, lifestyle, and cognitive variables relate to AD diagnosis.

---

## Overview

Alzheimer’s Disease is a growing global health concern characterized by progressive cognitive decline. This project analyzes a publicly available dataset to investigate potential risk factors and their association with AD diagnosis.

The analysis combines exploratory data analysis (EDA), statistical testing, and logistic regression modeling to identify meaningful relationships while maintaining interpretability.

---

## Dataset

- Source: Kaggle dataset  
- Total Records: 2,149 patients  
- Features: 35 variables  

### Key Variables:
- **Target Variable:** AD Diagnosis (0 = No AD, 1 = AD)  
- **Demographics:** Age, Gender, Education  
- **Lifestyle:** BMI, Smoking, Alcohol  
- **Medical History:** Diabetes, Hypertension, Depression  
- **Cognitive Measures:** MMSE Score, Memory Complaints  

---

## Data Preprocessing

- Handled missing values using imputation  
- Removed rows with excessive missing data  
- Encoded categorical variables  
- Verified data consistency and quality  

---

## Analysis Performed

### Exploratory Data Analysis (EDA)
- Distribution analysis  
- Outlier detection  
- Histograms and box plots  

### Statistical Testing
- **T-Test:** Compared MMSE scores between AD and non-AD groups  

### Logistic Regression
- Modeled probability of AD diagnosis  
- Evaluated predictor significance  

---

## Key Findings

- **MMSE Score** was the strongest predictor of Alzheimer’s Disease  
- Lower cognitive scores significantly increased likelihood of AD  
- Education showed a potential protective effect  
- Other variables (age, lifestyle, medical conditions) were not statistically significant in this dataset  

These findings align with established research highlighting cognitive decline as a major indicator of AD :contentReference[oaicite:0]{index=0}  

---

## Limitations

- Cross-sectional dataset (no causal inference)  
- Self-reported data may introduce bias  
- Lack of biomarker and imaging data  
- Dataset-specific limitations  

---

## Tools & Technologies

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---


## Author

Tarique Bagalkot
