<h1 align="center">💳 Credit Card Fraud Detection </h1>

<p align="center">
  <img src="https://github.com/Sangeetha-K-04/CodsoftTask3/blob/main/credit%20image.jpg?raw=true" alt="Fraud Detection" width="600"/>
</p>

<p align="center">
  <b>Detecting fraudulent transactions using data science and machine learning algorithms</b><br>
  🔍 Data Preprocessing | 📊 EDA | 🤖 Model Training & Evaluation | 📉 Imbalanced Classification
</p>

---

## 📌 Project Overview

Credit card fraud poses a serious threat in today's digital world. This project focuses on building a robust and intelligent machine learning system to identify **fraudulent credit card transactions** from a large dataset of real-world transactions.

With imbalanced data and limited features, this challenge goes beyond simple classification — it requires a **strategic approach to data handling, evaluation, and model tuning**.

---

## 🎯 Objective

- Analyze and visualize transaction data to uncover patterns.
- Handle severe **class imbalance** between fraudulent and normal transactions.
- Apply machine learning algorithms to predict fraud effectively.
- Compare model performances using key metrics like accuracy, recall, precision, and F1-score.

---

## 📁 Dataset Information

- 📦 **Source**: [Kaggle Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- 📊 Contains **284,807** transactions with only **492 fraud cases**.
- Features include Time, Amount, and anonymized V1 to V28.
- The target column is Class (0: normal, 1: fraud).

---

## 🔍 Exploratory Data Analysis (EDA)

- Checked for null values and data imbalance.
- Observed massive skew: ~99.8% non-fraud vs. ~0.17% fraud.
- Used **correlation heatmaps** and **distribution plots** to find relationships.
- Analyzed transaction Amount, Time, and class distribution.

---

## 🧪 Techniques & Tools Used

| Tool/Library       | Role                                |
|--------------------|-------------------------------------|
| Python             | Core language                       |
| Pandas, NumPy      | Data manipulation                   |
| Matplotlib, Seaborn| Data visualization                  |
| Scikit-learn       | Machine learning models & metrics   |
| Jupyter Notebook   | Interactive analysis & development  |

---

## 🛠️ Machine Learning Models Implemented

- **Logistic Regression**
- **Random Forest Classifier**

> Evaluated using:
> - **Confusion Matrix**
> - **Classification Report**
> - **Accuracy, Precision, Recall, F1-Score**

Random Forest performed significantly better due to its ability to handle unbalanced datasets with decision trees.

---

## 📉 Handling Class Imbalance

As fraud cases are extremely rare, we took care to:

- Use **stratified splitting** for train-test sets.
- Analyze performance based not just on accuracy, but **recall** and **precision** (important for fraud detection).

---

## 💻 How to Run the Project

### 🔹 1. Clone the Repository

```bash
git clone https://github.com/Sangeetha-K-04/CodsoftTask3.git
cd CodsoftTask3
```

### 🔹 2. Install Required Libraries

Ensure Python 3.7+ is installed, then:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 🔹 3. Launch the Jupyter Notebook
```bash
jupyter notebook CreditFraudDetection.ipynb
```





