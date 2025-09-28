# Debt Default Prediction using Machine Learning  

## Description  
This project predicts the likelihood of a country defaulting on its external debt using machine learning techniques. Data is fetched using the **World Bank API** and processed to create a robust predictive model. Key steps include data preprocessing, feature engineering, hyperparameter tuning, and model evaluation.  

The project leverages LightGBM for its efficiency and accuracy, achieving **99% accuracy** and **97% macro-average F1-score** on imbalanced data.  

---

## Features  
- Data extraction via **World Bank API**  
- Handles **imbalanced datasets** using ADASYN  
- Implements **feature engineering** and **correlation analysis**
- Hyperparameter tuning for model optimization.
- Tested multiple models; LightGBM selected for optimal performance 
- Cross-validation to ensure generalizability

The following machine learning models were tested:

 - Logistic Regression
 - Random Forest
 - XGBoost
 - LightGBM (selected for best performance)
 - Techniques applied:

Following methods were used for improving and fine tuning the model:
- Correlation analysis for feature selection
- Handling imbalanced datasets using ADASYN and class weighting 
- Cross-validation for performance evaluation
- Hyperparameter tuning using Optuna improving the accuracy by 20 percent (especiallly for the minority class)

## Data Sources 
- World Bank API: [Defaulted Countries List](https://thedocs.worldbank.org/en/doc/4d4081ea0fd5642318a373701a296a61-0050022024/original/Mallucci-Sovereign-defaults-at-home-and-abroad.pdf)
- World Bank API: [GDP Indicators](https://pypi.org/project/wbgapi/)
