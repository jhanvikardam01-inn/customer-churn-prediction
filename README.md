# 📊 Customer Churn Prediction

## 📌 Project Overview

Customer churn is one of the biggest challenges for subscription-based businesses. This project uses Machine Learning to predict whether a customer is likely to leave a telecom company based on customer demographics, account details, and service usage.

The goal is to help businesses identify at-risk customers and improve customer retention strategies.

---

## 🚀 Features

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Encoding
- Machine Learning Model Training
- Model Evaluation
- Feature Importance Analysis

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📂 Project Structure

```
customer-churn-prediction/
│
├── Dataset/
│   └── Telco_Customer_Churn.csv
│
├── Notebook/
│   └── Customer_Churn_Prediction.ipynb
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 📊 Dataset

The dataset contains customer information such as:

- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Phone Service
- Internet Service
- Contract Type
- Monthly Charges
- Total Charges
- Payment Method

**Target Variable:**
- Churn (Yes/No)

---

## 🔄 Project Workflow

1. Import Dataset
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Data Preprocessing
5. Feature Engineering
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Feature Importance

---

## 🤖 Machine Learning Models

- Logistic Regression
- Random Forest Classifier

---

## 📈 Model Performance

The Random Forest model achieved good performance in predicting customer churn.

**Important Features:**

| Feature | Importance |
|----------|------------|
| MonthlyCharges | 0.1765 |
| Tenure | 0.1750 |
| TotalCharges | 0.1677 |
| Contract | 0.0820 |
| PaymentMethod | 0.0512 |
| OnlineSecurity | 0.0480 |
| TechSupport | 0.0431 |

---

## 💡 Key Insights

- Customers with higher monthly charges are more likely to churn.
- Customers with shorter tenure have a higher churn rate.
- Contract type significantly impacts customer retention.
- Online Security and Tech Support services reduce churn.

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/jhanvikardam01-inn/customer-churn-prediction.git
```

Go to the project folder:

```bash
cd customer-churn-prediction
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Run the Jupyter Notebook:

```bash
jupyter notebook
```

---

## 📌 Future Improvements

- Hyperparameter Tuning
- Deploy using Streamlit
- Try XGBoost and LightGBM
- Improve Model Accuracy

---

## 👩‍💻 Author

**Jhanvi Kardam**

- GitHub: https://github.com/jhanvikardam01-inn

---

⭐ If you found this project helpful, please consider giving it a star!
