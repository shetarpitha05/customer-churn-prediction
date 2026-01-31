# customer-churn-prediction
End-to-end machine learning project to predict customer churn using EDA, feature engineering, classification models, and performance evaluation.

# Customer Churn Prediction

End-to-end Machine Learning project to predict customer churn using Telco Customer Churn dataset.  
Includes data cleaning, exploratory data analysis (EDA), feature engineering, model training, and evaluation.

## Project Highlights
- Cleaned and preprocessed real-world churn dataset
- Performed EDA to understand churn patterns
- Built ML models:
  - Logistic Regression
  - Random Forest Classifier
- Evaluated using Classification Report, Confusion Matrix, and ROC-AUC score
- Extracted top important features from Random Forest model

## Tech Stack
- Python
- Pandas, NumPy, Matplotlib
- Scikit-learn

## Dataset
Telco Customer Churn dataset (Kaggle / IBM sample dataset)

## Workflow
1. Data loading & cleaning (`TotalCharges` handling, missing values)
2. EDA (churn distribution, churn vs contract, monthly charges analysis)
3. Preprocessing using OneHotEncoding
4. Model training (Logistic Regression + Random Forest)
5. Evaluation & comparison using ROC-AUC
6. Feature importance analysis

## Results
- Compared model performance using ROC-AUC score
- Random Forest produced better performance and feature importance insights

## How to Run
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt

