# 📊 Telecom Customer Churn Prediction

This project predicts *customer churn* for a telecom company using *Machine Learning*. Churn prediction helps telecom providers identify customers at risk of leaving and take proactive retention measures.

---

## 🚀 Project Workflow
1. *Data Loading*  
   - Dataset: telecom_churn_data.csv
   - Features: Customer usage patterns, subscription details, customer service calls.
   - Target: Churn (Yes/No)

2. *Data Preprocessing*
   - Removed irrelevant columns (e.g., Phone number).
   - Encoded categorical variables (International Plan, VMail Plan, Churn).
   - Converted numeric features and handled missing values.
   - Dropped redundant variables like derived charges.

3. *Exploratory Data Analysis (EDA)*
   - Distribution plots for call minutes, service calls, etc.
   - Correlation analysis between features and churn.
   - Found higher churn among customers with frequent service calls.

4. *Model Development*
   - Algorithms used:
     - Logistic Regression
     - Random Forest
     - XGBoost
   - Hyperparameter tuning with GridSearchCV
   - Evaluated using Accuracy, Precision, Recall, F1-score, ROC-AUC

5. *Results*
   - Logistic Regression → Good baseline
   - Random Forest → Higher recall
   - XGBoost → Best performing model with ~85–90% accuracy and highest ROC-AUC

---

## 📂 Project Structure
├── Telecom_Customer_Churn_Prediction.ipynb # Jupyter Notebook
├── telecom_churn_data.csv # Dataset (not included in repo)
├── requirements.txt # Dependencies
└── README.md # Documentation
