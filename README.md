# 🏦 Loan Approval Prediction Web App

An end-to-end Machine Learning web application built with Python, scikit-learn, and Streamlit. This app predicts whether a loan applicant meets bank eligibility criteria based on personal details, income, loan specifics, credit score, and financial assets.

## 🚀 Live Demo
*(Once deployed on Streamlit Cloud, paste your live web app link here!)*

---

## 📌 Features
- **Interactive UI:** Built using Streamlit for instant predictions based on user inputs.
- **Machine Learning Model:** Uses a `RandomForestClassifier` trained on historical loan application data.
- **Data Preprocessing:** Handles numerical and categorical feature mappings for real-time model evaluation.

---

## 🛠️ Project Structure
```text
classifier_one/
│
├── app.py                     # Streamlit frontend web interface
├── train_loan_model.py        # Data cleaning & model training script
├── loan_approval_dataset.csv  # Kaggle loan dataset
├── loan_model.pkl             # Trained & serialized scikit-learn model
├── requirements.txt           # Project dependencies for deployment
└── README.md                  # Project documentation

