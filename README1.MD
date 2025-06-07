# 📉 Telco Customer Churn Prediction (Logistic Regression)

This project uses a real-world Telco dataset to predict customer churn using logistic regression.  
It identifies key churn-driving factors and provides business actions for retention strategies.

---

## 📊 Project Objectives

- Clean and prepare a real-world churn dataset
- Encode categorical features and scale numeric columns
- Train a logistic regression model to classify churn
- Interpret feature importance to drive business action

---

## 📁 Dataset Summary

- 📦 Rows: 7,000+ customer records  
- 🧩 Columns: Contract type, monthly charges, services used, tenure, etc.  
- 🎯 Target: `Churn` (Yes/No → 1/0)

---

## 🧪 Model Performance

| Metric            | Score     |
|-------------------|-----------|
| Accuracy          | **80.4%** |
| Precision (Churn) | 0.65      |
| Recall (Churn)    | 0.57      |
| F1-Score (Churn)  | 0.61      |

✅ Model performs well on non-churners, with balanced performance on churners.  
Ideal for use in CRM systems to trigger **preventive churn strategies**.

---

## 📈 Feature Importance

**Top Positive Predictors (increase churn risk):**
- Fiber optic internet
- High total charges
- Streaming services
- Month-to-month contracts
- Electronic check payment

**Top Negative Predictors (reduce churn risk):**
- Two-year contract
- Longer tenure
- Tech support
- Paperless billing
- Online security

---

## 💡 Business Recommendations

- 📩 Promote **annual/biannual contracts** with discount incentives
- 🎁 Offer **tech support or streaming add-ons** to high-risk customers
- ⚠️ Monitor customers with **month-to-month contracts + fiber internet**
- 🔔 Use this model in marketing to trigger **retention offers** in advance

---

## 🧰 Tools Used

- Python, Pandas, NumPy
- scikit-learn (Logistic Regression, preprocessing, evaluation)
- Matplotlib, Seaborn

---

## 📁 Files Included

- `telco_churn.csv` – Cleaned dataset  
- `churn_prediction.ipynb` – Jupyter notebook  
- `README.md` – This file

---

## 🧠 Skills Demonstrated

- Binary classification with logistic regression  
- Feature encoding & scaling  
- Model evaluation & interpretation  
- Business insight communication
