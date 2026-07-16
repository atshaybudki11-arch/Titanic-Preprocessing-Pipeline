> **Note:** This repository currently focuses on the preprocessing stage of the machine learning workflow. Model training and evaluation will be added in future updates.

# 🚢 Titanic Data Preprocessing Pipeline

An end-to-end data preprocessing pipeline built using **Scikit-learn's Pipeline** and **ColumnTransformer**. The project automates data cleaning and feature transformation, producing a machine-learning-ready dataset while following best practices to prevent data leakage.

---

## 📌 Project Overview

The Titanic dataset contains:

- Missing values
- Numerical features
- Categorical features
- Features with different scales

This project builds reusable preprocessing pipelines that automatically clean and transform the data before it is used for machine learning.

---

## ✨ Features

- Train-Test Split
- Automatic detection of numerical and categorical columns
- Missing value imputation
- Min-Max Scaling
- One-Hot Encoding
- ColumnTransformer
- Pipeline
- Data leakage prevention
- Processing of unseen Kaggle test data
- Saving the trained preprocessor using Joblib

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## 📂 Project Structure

```
Titanic-Preprocessing-Pipeline/
│
├── data/
│   ├── train.csv
│   └── test.csv
│
├── notebook/
│   └── Titanic_Preprocessing_Pipeline.ipynb
│
├── models/
│   └── preprocessor.pkl
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## ⚙️ Workflow

```
Raw Dataset
     │
     ▼
Drop Unnecessary Columns
     │
     ▼
Train-Test Split
     │
     ▼
Automatic Column Detection
     │
     ▼
ColumnTransformer
 ┌───────────────┬────────────────┐
 │               │                │
 ▼               ▼
Numerical      Categorical
Pipeline        Pipeline
 │               │
 ▼               ▼
Imputer        Imputer
 │               │
 ▼               ▼
MinMaxScaler   OneHotEncoder
        │
        ▼
Processed Dataset
```

---

## 📚 Concepts Demonstrated

- Data Preprocessing
- Feature Engineering
- Pipeline
- ColumnTransformer
- SimpleImputer
- MinMaxScaler
- OneHotEncoder
- Joblib
- Data Leakage Prevention

---

## 🚀 Future Improvements

- Train a Logistic Regression model
- Compare multiple machine learning algorithms
- Evaluate model performance
- Generate Kaggle submission
- Deploy the complete machine learning pipeline

---

## 👨‍💻 Author

**Atshay Budki**

B.Tech CSE (AI) | Machine Learning Enthusiast