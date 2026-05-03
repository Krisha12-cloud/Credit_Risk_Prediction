# Credit_Risk_Prediction
Developed a credit risk prediction model for MSMEs using ensemble methods like XGBoost, CatBoost, and Random Forest. Applied data preprocessing, imputation, and imbalance handling techniques, and used SHAP analysis to identify key risk factors and improve model interpretability.

# Objective
Classify businesses as default / non-default
Handle real-world challenges like missing data and class imbalance
Provide interpretable insights for credit decision-making
# Workflow
Data Preprocessing : 
Handled skewed features using log transformation

Applied imputation techniques after introducing controlled missingness

Feature Engineering : 
Created features capturing financial and legal trends

Converted categorical/text data into numerical format

Imbalance Handling : 
Addressed 94:6 class imbalance using resampling techniques

Model Training : 
Trained and compared multiple ML models

Selected best-performing model based on evaluation metrics

Evaluation & Explainability : 
Evaluated using AUC, F1-score, and confusion matrix

Used SHAP to identify key risk factors

# Tech Stack
### Language: Python

### Libraries: Scikit-learn, XGBoost, CatBoost

### Data Processing: Pandas, NumPy

### Imputation: MICE, KNN

### Imbalance Handling: SMOTE-Tomek, ADASYN

### Explainability: SHAP

# How to execute

#### git clone <repo-link>

#### cd <repo-name>

#### pip install -r requirements.txt

