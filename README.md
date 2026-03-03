# 🍷 What Makes a Wine Good?  
## Red Wine Quality - Exploratory Data Analysis (EDA)

An in-depth exploratory data analysis of the Red Wine Quality dataset to understand the key physicochemical properties that influence wine quality ratings.

---

## 📌 Project Overview

Wine quality is influenced by multiple chemical characteristics such as acidity, alcohol content, sulfur compounds, and density.

In this project, we analyze how these physicochemical properties relate to expert-rated wine quality scores. The focus of this notebook is purely analytical exploration and insight generation rather than predictive modeling.

---

## 🎯 Objectives

- Understand the distribution of wine quality ratings  
- Identify class imbalance in the dataset  
- Analyze feature distributions and detect outliers  
- Examine correlations between chemical properties and quality  
- Compare high-quality vs low-quality wines  
- Extract meaningful domain-driven insights  

---

## 📊 Dataset Information

- **Source:** UCI Machine Learning Repository  
- **Samples:** 1599 red wine samples  
- **Features:** 11 physicochemical properties  
- **Target Variable:** Quality score (0–10)  

### Input Features

- Fixed Acidity  
- Volatile Acidity  
- Citric Acid  
- Residual Sugar  
- Chlorides  
- Free Sulfur Dioxide  
- Total Sulfur Dioxide  
- Density  
- pH  
- Sulphates  
- Alcohol  

### Target

- Quality (expert sensory score)

Additionally, a binary classification variable was created:
- Quality ≥ 7 → Good Wine  
- Quality < 7 → Not Good Wine  

---

## 🔍 Key Insights

- **Alcohol** is the strongest positive driver of wine quality.
- **Volatile Acidity** is the strongest negative contributor.
- The dataset is highly imbalanced (~86% not-good wines).
- Moderate relationships exist between acidity-related variables and pH.
- Chemical relationships observed in the data are logically consistent.

---

## 🛠 Tech Stack

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## 📎 Kaggle Notebook

You can view the complete interactive notebook on Kaggle here:

🔗 https://www.kaggle.com/code/netramfaran/what-makes-a-wine-good-eda

---

## 🚀 Future Work

- Build classification models (Logistic Regression, Random Forest)
- Evaluate using ROC-AUC and F1-score
- Perform feature importance analysis
- Address class imbalance using resampling techniques

---
