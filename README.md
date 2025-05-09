# Customer-Churn-Prediction
# 📉 Customer Churn Prediction

This project predicts customer churn in a telecom dataset using machine learning techniques. It helps businesses proactively identify and retain customers who are likely to stop using their services.

---

## 🎯 Objective

To develop classification models (Logistic Regression & Random Forest) that predict whether a customer will churn based on demographic, account, and service usage features.

---

## 🧾 Dataset

Source: [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

- 7,043 records
- 21 features: demographics, contract type, service usage
- Target column: `Churn` (Yes/No)

---

## 🧠 Features Used

- `tenure`, `MonthlyCharges`, `TotalCharges`
- `Contract`, `PaymentMethod`, `InternetService`
- `PhoneService`, `StreamingTV`, etc.

---

## 🧼 Preprocessing

- Converted `TotalCharges` to float
- Encoded categorical variables (Label Encoding & Binary Mapping)
- Dropped irrelevant `customerID` field

---

## 📊 Model Performance

| Model               | Accuracy | AUC    |
|--------------------|----------|--------|
| Logistic Regression| 79.7%    | 0.8415 |
| Random Forest       | 79.2%    | 0.8225 |

✅ Logistic Regression slightly outperforms Random Forest in AUC.

---

## 💼 Business Impact

> “Using churn prediction, we can proactively target high-risk customers and retain up to 80% accuracy, potentially reducing churn-related revenue loss by 25%.”

---

## 🛠️ Tech Stack

- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Scikit-learn (LogisticRegression, RandomForest, metrics)
- Jupyter Notebook

---

## ▶️ Run Locally

```bash
pip install -r requirements.txt
jupyter notebook customer_churn_prediction.ipynb
```

Place the dataset file in the same directory as the notebook:
```
WA_Fn-UseC_-Telco-Customer-Churn.csv
```

---

## ✨ Author

**Arkajyoti Sarkar**  
B.Tech in CSE (Data Science), MAKAUT  
LinkedIn: [@arkajyoti-sarkar](https://www.linkedin.com/in/arkajyoti-sarkar/)
