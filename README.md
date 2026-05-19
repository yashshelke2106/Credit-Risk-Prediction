# Credit Risk Prediction System

A machine learning-powered web application that predicts whether a loan applicant is likely to default or not using financial and demographic data.

Built using **Python**, **Streamlit**, and **Scikit-learn**, this project provides interactive data analysis and real-time credit risk prediction.

---

# 📌 Features

* Interactive Streamlit dashboard
* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Real-time credit risk prediction
* Machine Learning model integration
* Correlation analysis and visualizations
* User-friendly interface

---

# 🛠️ Technologies Used

* Python
* Streamlit
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

# 📂 Project Structure

```bash id="zbd5c3"
Credit-Risk-Prediction/
│
├── app1.py
├── clean_data.csv
├── credit_risk_dataset.csv
├── EDA.ipynb
├── README.md
└── requirements.txt
```

---

# 📊 Dataset Information

The dataset includes:

* Applicant age
* Income
* Employment length
* Home ownership
* Loan amount
* Loan intent
* Interest rate
* Credit history length
* Previous default history

### Target Variable

* `loan_status`

  * `0` → Non-default
  * `1` → Default

---

# ⚙️ Machine Learning Workflow

### Data Preprocessing

* Missing value handling
* Numerical scaling
* Categorical encoding

### Exploratory Data Analysis

* Distribution plots
* Count plots
* Correlation heatmaps
* Loan analysis visualizations

### Model Used

* Random Forest Classifier

Additional imported models:

* Logistic Regression
* KNN
* Decision Tree
* SVM

---

# ▶️ How to Run the Project

## Clone Repository

```bash id="b0eg4z"
git clone https://github.com/your-username/credit-risk-prediction.git
cd credit-risk-prediction
```

## Install Dependencies

```bash id="8wshzt"
pip install -r requirements.txt
```

## Run Streamlit App

```bash id="55a4jh"
streamlit run app1.py
```

---

# 📈 Application Modules

## Home

Project introduction and overview.

## Data Overview

* Dataset shape
* Missing values
* Data preview

## EDA

* Univariate Analysis
* Bivariate Analysis
* Correlation Analysis

## Predict Risk

Predicts whether the applicant is:

* ✅ Low Risk
* ❌ High Risk

---

# 📌 Future Improvements

* Add XGBoost and LightGBM
* Improve model accuracy
* Deploy on cloud
* Add model explainability
* Add authentication system

---

# 👨‍💻 Author

**Yash Shelke**

Project source based on uploaded application file 
