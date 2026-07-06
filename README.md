# 💳 Credit Scoring Model

A Machine Learning project that predicts whether a customer is a **Good** or **Bad** credit risk using multiple classification algorithms.

---

## 📌 Project Overview

Credit scoring is an important application of machine learning in the banking and finance industry. This project analyzes customer financial data and predicts credit risk by training and comparing different machine learning models.

---

## 🎯 Objectives

- Analyze customer credit data
- Perform data cleaning and preprocessing
- Explore the dataset using visualizations
- Train multiple machine learning models
- Compare model performance
- Save the best-performing model

---

## 📊 Dataset

**Dataset:** German Credit Risk Dataset

### Features

- Age
- Sex
- Job
- Housing
- Saving Accounts
- Checking Account
- Credit Amount
- Duration
- Purpose
- Risk (Target Variable)

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## 📈 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Age Distribution
- Gender Distribution
- Housing Distribution
- Purpose Distribution
- Credit Amount Distribution
- Loan Duration Distribution
- Risk Distribution
- Correlation Heatmap

---

## ⚙️ Data Preprocessing

- Removed unnecessary columns
- Checked duplicate records
- Handled missing values
- Applied One-Hot Encoding
- Selected input features and target variable
- Split the dataset into training and testing sets

---

## 🤖 Machine Learning Models

The following models were trained:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

## 📊 Model Performance

| Model | Accuracy |
|--------|---------:|
| Logistic Regression | 0.750 |
| Decision Tree | 0.675 |
| Random Forest | 0.745 |

🏆 **Best Model:** Logistic Regression

---

## 💾 Saved Model

The trained model was saved using Joblib.

```
credit_scoring_model.pkl
```

---

## 📂 Project Structure

```
Credit-Scoring-Model
│
├── Credit_Scoring_Model.ipynb
├── credit_scoring_model.pkl
├── german_credit_data.csv
└── README.md
```

---

## 🚀 Project Workflow

```
Load Dataset
      ↓
Data Cleaning
      ↓
Exploratory Data Analysis
      ↓
Data Preprocessing
      ↓
Feature Selection
      ↓
Train-Test Split
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Model Comparison
      ↓
Save Model
```

---

## 🔮 Future Improvements

- Hyperparameter tuning
- Cross-validation
- Feature engineering
- Deploy the model using Flask or Streamlit

---

## 👩‍💻 Author

**Vanshika Soni**


