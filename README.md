# 🚀 Loan Prediction using Logistic Regression & Regularization

## 📌 Overview
This project predicts whether a customer will accept a personal loan using machine learning.

We perform:
- Data preprocessing  
- Exploratory Data Analysis (EDA)  
- Logistic Regression  
- L1 (Lasso) & L2 (Ridge) Regularization  

The goal is to build a model that performs well on unseen data and avoids overfitting.

---

## 📂 Dataset Description
The dataset includes:

- Age  
- Experience  
- Income  
- Family  
- CCAvg  
- Education  
- Mortgage  
- Securities Account  
- CD Account  
- Online Banking  
- Credit Card  

🎯 **Target Variable:** `Personal.Loan`  
- 0 → No Loan  
- 1 → Loan Accepted  

---

## 🧹 Data Preprocessing
- Removed `ID`, `ZIP.Code`  
- Checked missing values  
- Feature scaling using **StandardScaler**  
- Train-test split  

---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 Correlation Heatmap
![Heatmap](l1%20%26%20l2%20Regularization%20png/heatmap.png)
### 🔹 Income vs Loan (Boxplot)
![Boxplot](l1%20%26%20l2%20Regularization%20png/boxplot.png)

🔍 **Insights:**
- Higher income → higher chance of loan  
- High CCAvg users take more loans  
- CD account holders are strong predictors  

---

## 🤖 Models Implemented

### 🔹 1. Linear Regression (Baseline)
- Not suitable for classification  

✅ **Accuracy:** `0.925`

---

### 🔹 2. Logistic Regression
- Best for binary classification  

✅ **Accuracy:** `0.95`

---

### 🔹 3. L1 Regularization (Lasso)
- Performs feature selection  

✅ **Accuracy:** `0.95`

---

### 🔹 4. L2 Regularization (Ridge)
- Prevents overfitting  

✅ **Accuracy:** `0.95`

---

## 📊 Model Comparison

| Model                | Accuracy |
|---------------------|----------|
| Linear Regression   | 92%      |
| Logistic Regression | 95%      |
| L1 Regularization   | 95%      |
| L2 Regularization   | 95%      |

---

## 🧠 Key Insights
- Income & CCAvg are strong predictors  
- CD Account has high impact  
- Logistic Regression > Linear Regression  
- Regularization improves performance  

---

## ✅ Conclusion
Logistic Regression with both **L1 (Lasso)** and **L2 (Ridge) Regularization** performed well, providing stable and reliable predictions while reducing overfitting.

---

## 🔮 Future Improvements
- SMOTE for imbalance  
- Random Forest / XGBoost  
- Hyperparameter tuning  
- ROC-AUC evaluation  

---

## 🛠️ Tech Stack
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
