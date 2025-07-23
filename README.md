 💳 Credit Card Default Prediction — Machine Learning Project

This project aims to predict whether a credit card customer is likely to default on their payment in the upcoming month. It includes comprehensive data preprocessing, exploratory data analysis, feature engineering, and the application of various classification algorithms to assess and manage credit risk effectively.

Developed by **Sowmya** using Python and Scikit-learn.

---

## 🔍 Problem Overview

Credit card companies aim to mitigate financial risk by identifying customers likely to default on their payments. Using customer demographic and transaction history, this project applies supervised machine learning techniques to predict the `default.payment.next.month` variable.

---

## 📊 Dataset Summary

- **Source**: UCI Machine Learning Repository  
- **Dataset Size**: 30,000 observations  
- **Target Variable**: `default.payment.next.month`  
  - `1`: Default  
  - `0`: No Default

### Selected Features:

| Feature         | Description                                       |
|-----------------|---------------------------------------------------|
| `LIMIT_BAL`     | Credit limit (in NT dollars)                      |
| `SEX`           | Gender (1 = Male, 2 = Female)                     |
| `EDUCATION`     | Education level (1 = Graduate, 2 = University...) |
| `MARRIAGE`      | Marital status                                    |
| `AGE`           | Age of the customer                               |
| `PAY_0` to `PAY_6` | Repayment status over the past 6 months       |
| `BILL_AMT1`–`BILL_AMT6` | Monthly bill statements                |
| `PAY_AMT1`–`PAY_AMT6`   | Monthly payments made                   |

---

## 🎯 Project Objectives

- Perform exploratory data analysis to uncover trends and correlations
- Apply data preprocessing techniques such as scaling and encoding
- Train multiple classification models to predict payment default
- Evaluate models using industry-standard metrics

---

## ⚙️ Tech Stack

- **Language**: Python 3.x  
- **Data Manipulation**: Pandas, NumPy  
- **Visualization**: Matplotlib, Seaborn  
- **Modeling**: Scikit-learn  
- **Environment**: Google Colab / Jupyter Notebook  

---

## 🤖 Machine Learning Models Implemented

- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  
- Support Vector Machine (SVM)  
- (Optional) XGBoost Classifier

---

## 📊 Model Evaluation Metrics

- Accuracy  
- Precision, Recall, F1-Score  
- Confusion Matrix  
- ROC-AUC Score  

---

## 📈 Sample Results (replace with actual scores)

| Model               | Accuracy | Precision | Recall | F1-Score |
|---------------------|----------|-----------|--------|----------|
| Logistic Regression | 0.81     | 0.79      | 0.71   | 0.75     |
| Random Forest       | 0.85     | 0.83      | 0.76   | 0.79     |
| SVM                 | 0.82     | 0.80      | 0.72   | 0.76     |

---

## 🗂️ Project Structure

```
Default-Of-Credit/
├── data/                # Dataset files
├── sowmya.ipynb          # Main notebook with code and analysis
├── README.md            # Project overview (this file)
└── requirements.txt     # (Optional) Environment dependencies
```

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/ksowmyasri10/Default-Of-Credit.git
cd Default-Of-Credit
```

2. Open `sowmya.ipynb` in Jupyter Notebook or Google Colab.

---

## 📬 Contact

For questions, issues, or collaboration, visit the project repository:  
🔗 [https://github.com/ksowmyasri10/Default-Of-Credit](https://github.com/ksowmyasri10/Default-Of-Credit)

---
