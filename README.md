# 🚢 Titanic Data Preprocessing Pipeline

An end-to-end machine learning preprocessing pipeline built using **Scikit-learn's Pipeline** and **ColumnTransformer**. This project automates data cleaning and feature transformation while following best practices to prevent data leakage.

> **Status:** ✅ Preprocessing Completed  
> 🔄 Future updates will include model training, evaluation, and deployment.

---

## 📖 Overview

Real-world datasets often contain:
- Missing values
- Categorical features
- Numerical features with different scales

This project builds reusable preprocessing pipelines that automatically prepare the Titanic dataset for machine learning.

---

## ✨ Features

- ✅ Train-Test Split
- ✅ Automatic detection of numerical and categorical columns
- ✅ Missing value imputation
- ✅ Min-Max Scaling
- ✅ One-Hot Encoding
- ✅ ColumnTransformer
- ✅ Scikit-learn Pipelines
- ✅ Data Leakage Prevention
- ✅ Processing of unseen Kaggle Test Dataset
- ✅ Saving the trained preprocessor using Joblib

---

## 🛠 Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## 📂 Project Structure

```text
Titanic-Preprocessing-Pipeline/
│
├── assets/
├── data/
├── models/
│   └── preprocessor.pkl
├── notebook/
│   └── Titanic_Preprocessing_Pipeline.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

## ⚙️ Workflow
---

# 📸 Project Screenshots

## 1. Preprocessing Pipeline

![Pipeline](assets/pipeline.png)

---

## 2. Processed Training Data

![Processed Training Data](assets/processed_train_data.png)

---

## 3. Generated Feature Names

![Feature Names](assets/feature_names.png)

---

## 4. Unseen Kaggle Test Dataset

![Kaggle Test](assets/kaggle_test.png)
```text
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
 ├───────────────────────┐
 │                       │
 ▼                       ▼
Numerical Pipeline   Categorical Pipeline
 │                       │
 ▼                       ▼
SimpleImputer       SimpleImputer
 │                       │
 ▼                       ▼
MinMaxScaler       OneHotEncoder
        │
        ▼
Processed Dataset
        │
        ▼
Saved as preprocessor.pkl
```

---

## 🧠 Key Concepts Demonstrated

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
- Hyperparameter tuning
- Save the complete preprocessing + model pipeline
- Deploy using Streamlit

---

## 👨‍💻 Author

**Atshay Budki**

B.Tech CSE (AI) | Machine Learning Enthusiast
