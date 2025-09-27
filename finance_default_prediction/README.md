# Credit Card Default Risk Prediction

## Project Overview
Financial institutions often face challenges in predicting whether a customer will default on their credit card payments.  
This project applies **data analytics and machine learning** to build a **default risk prediction model**, enabling companies to reduce financial losses and make better credit decisions.

## Dataset
- Source: [Kaggle - Default of Credit Card Clients](https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset)  
- Records: 30,000 customers  
- Features: Customer demographics, credit history, payment behavior  
- Target: `default.payment.next.month` → 1 = Default, 0 = No Default  

## Business Goals
- **Risk Management** → Identify high-risk customers before default occurs.  
- **Decision Support** → Help financial analysts in approving or rejecting credit applications.  
- **Cost Reduction** → Minimize losses from unpaid credit card balances.  

## Project Workflow
1. **Data Cleaning & Preprocessing**  
   Handle missing values, outliers, and categorical encoding.  
2. **Exploratory Data Analysis (EDA)**  
   Profile customers and identify default patterns.  
3. **Feature Engineering**  
   Create new features (e.g., utilization rate, payment ratio).  
4. **Model Development**  
   - Baseline: Logistic Regression  
   - Advanced: Random Forest, XGBoost, LightGBM  
5. **Model Evaluation**  
   Compare models using AUC, Precision, Recall, and F1-score.  
6. **Model Interpretation**  
   Use SHAP values to explain key drivers of default.  
7. **Dashboard**  
   Build an interactive Streamlit dashboard for stakeholders.  

## Project Structure
finance_default_prediction/
├── data/ # dataset
├── notebooks/ # Jupyter notebooks (EDA, modeling, results)
├── src/ # source code modules
├── README.md # project documentation
└── requirements.txt # dependencies

## Tools & Tech
- **Python**: pandas, numpy, scikit-learn, xgboost, lightgbm  
- **Visualization**: matplotlib, seaborn, plotly  
- **Model Explainability**: SHAP  
- **Dashboard**: Streamlit  
- **Version Control**: GitHub  

## Key Outcomes
- Built a predictive model with >80% AUC score.  
- Identified **top 5 features influencing credit default** (e.g., payment history, credit utilization).  
- Developed an interactive dashboard for non-technical stakeholders.  

## Author
Syarifa Anastasya Putri  
(Mathematics Student | Focus on Financial Data Analytics & Risk Modeling)
