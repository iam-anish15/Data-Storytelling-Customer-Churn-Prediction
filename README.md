# Data Storytelling: Customer Churn Prediction

### 📌 Project Overview
This project analyzes a **telecommunications customer dataset** to predict **customer churn**. Using **Exploratory Data Analysis (EDA)**, **feature engineering**, and machine learning models, we uncover the key factors influencing churn and build predictive models to identify at-risk customers.

---

### 📊 Key Insights from Analysis
- **Dataset**: 7043 customers, 21 variables  
- **Demographics & Churn**: Age, gender, and senior citizen status provide moderate signals  
- **Service Usage & Churn**: Customers with fewer subscribed services or shorter tenure are more likely to churn  
- **Engineered Features**: `tenure_group`, `num_add_services`, and `monthly_charge_ratio` improved predictive performance  
- **Model Insights**:  
  - Logistic Regression with engineered features improved F1-score for churn from 0.60 → 0.61  
  - Random Forest highlighted `tenure`, `MonthlyCharges`, and `Contract` as top predictors  
  - SHAP analysis provided explainable insights for customer-level churn

---

### 📂 Repository Contents
- `Customer-Churn-EDA.ipynb` → Full exploratory data analysis and feature engineering workflow  
- `Customer-Churn-Prediction.ipynb` → Modeling, evaluation, feature importance, and hyperparameter tuning  
- Visualizations and comparison tables for model performance

---

### 🔮 Next Steps
Further analysis and improvements may include:  
- Testing additional feature engineering techniques (e.g., polynomial features, interaction terms)  
- Trying alternative models like XGBoost or LightGBM  
- Hyperparameter tuning for optimized model performance  
- Using SHAP for deeper explainable AI insights to guide retention strategies
