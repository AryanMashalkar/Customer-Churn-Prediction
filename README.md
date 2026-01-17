# Customer Churn Prediction

## 📌 Project Overview
This project predicts whether a customer will churn (leave a service) based on customer demographics, service usage, and account information.

## 📊 Dataset
- Telco Customer Churn Dataset
- Target variable: `Churn` (Yes / No)

## ⚙️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## 🔍 Workflow
- Data cleaning and preprocessing
- Handling missing values
- Encoding categorical variables
- Train-test split with stratification
- Logistic Regression model
- Model evaluation using accuracy, precision, recall

## 📈 Results
- Achieved ~80% accuracy
- Identified key churn drivers such as contract type, tenure, and monthly charges

## 💡 Business Insight
Customers with month-to-month contracts and higher monthly charges are more likely to churn.

## 📂 How to Run
```bash
pip install -r requirements.txt
