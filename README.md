# 💳 Credit Card Fraud Detection using Machine Learning

A Machine Learning project that detects fraudulent credit card transactions using multiple classification algorithms and imbalanced data handling techniques.

---

# 🚀 Project Overview

This project focuses on identifying fraudulent credit card transactions using Machine Learning models.

The dataset used in this project is highly imbalanced, so SMOTE (Synthetic Minority Oversampling Technique) was used to balance fraud and non-fraud transactions before model training.

The project compares the performance of multiple classification algorithms to determine the best fraud detection model.

---

# 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Jupyter Notebook

---

# 📂 Project Structure

```text
credit-card-fraud-detection/
│
├── credit_card_fraud_detection.ipynb
├── credit_card_fraud_detection.py
├── README.md
├── requirements.txt
├── .gitignore
```

---

# 📊 Features

✅ Data Cleaning  
✅ Exploratory Data Analysis  
✅ Feature Scaling  
✅ Imbalanced Dataset Handling using SMOTE  
✅ Logistic Regression Model  
✅ Decision Tree Model  
✅ Random Forest Model  
✅ Support Vector Machine (SVM)  
✅ Model Evaluation and Comparison  
✅ Fraud Prediction System  

---

# 📈 Machine Learning Models Used

## 1️⃣ Logistic Regression
- Simple baseline classification model
- Good recall performance
- Higher false positives

---

## 2️⃣ Decision Tree
- Captures non-linear relationships
- Better fraud detection performance

---

## 3️⃣ Random Forest
- Best performing model in this project
- Better precision and recall balance
- Reduced overfitting

---

## 4️⃣ Support Vector Machine (SVM)
- Used with RBF kernel
- Handles complex patterns effectively

---

# ⚖️ Handling Imbalanced Dataset

Fraud datasets contain:
- Very few fraud transactions
- Large number of normal transactions

To solve this problem, SMOTE was used to balance the dataset before training the models.

---

# 📊 Evaluation Metrics

The following metrics were used:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

# 🔍 Key Insight

In fraud detection:
- Recall is very important
- Missing fraudulent transactions can cause financial loss

Random Forest achieved the best overall performance in this project.

---

# 📌 Dataset Access

The dataset used in this project is too large to upload directly to GitHub.

Download the dataset from Kaggle:

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

After downloading:

1. Extract the dataset file
2. Place `creditcard.csv` inside the project folder

Updated Project Structure:

```text
credit-card-fraud-detection/
│
├── credit_card_fraud_detection.ipynb
├── credit_card_fraud_detection.py
├── creditcard.csv
├── README.md
├── requirements.txt
├── .gitignore
```

---

# ▶️ How to Run the Project

## 1️⃣ Clone Repository

```bash
git clone https://github.com/dishakataria15/credit-card-fraud-detection.git
```

---

## 2️⃣ Install Requirements

```bash
pip install -r requirements.txt
```

---

## 3️⃣ Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
credit_card_fraud_detection.ipynb
```

---

# 📷 Visualizations Included

- Fraud vs Non-Fraud Distribution
- Correlation Matrix
- Confusion Matrix
- Model Performance Comparison

---

# 👩‍💻 Author

Disha Kataria

---

# ⭐ If You Like This Project

Give this repository a star ⭐ on GitHub.
