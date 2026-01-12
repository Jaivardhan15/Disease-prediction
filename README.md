# 🩺 Multi-Disease Prediction System using Machine Learning

An end-to-end Machine Learning web application that predicts the likelihood of Diabetes, Heart Disease, and Parkinson’s Disease based on user-provided medical parameters.
The application is built using Streamlit for an interactive UI and scikit-learn for ML model inference.

## 📌 Project Overview

Early detection of diseases can significantly improve treatment outcomes.
This project uses pre-trained machine learning models to assist in predicting multiple diseases through a single, user-friendly web interface.

Supported Predictions

🩸 Diabetes

❤️ Heart Disease

🧠 Parkinson’s Disease

## 🚀 Key Features

Single platform for multiple disease predictions

Clean and interactive Streamlit UI

Pre-trained Machine Learning models

Real-time prediction results

Input validation using numeric controls

Easy to deploy on Streamlit Cloud

## 🧠 Machine Learning Models
Disease	Algorithm Used

Diabetes	Logistic Regression / SVM

Heart Disease	Logistic Regression

Parkinson’s	Support Vector Machine (SVM)

(Models trained using publicly available medical datasets)

## 🗂️ Project Structure
```
Multi-Disease-Prediction-System/
│── app.py
│── requirements.txt
│── saved_models/
│   ├── diabetes_model.sav
│   ├── heart_disease_model.sav
│   └── parkinsons_model.sav
│── README.md
```

## 🛠️ Tech Stack

### Programming Language

– Python

### Libraries & Frameworks

– Streamlit

– scikit-learn

– NumPy

– SciPy

– Pickle

### Tools

– VS Code

– Git & GitHub

## ⚙️ Installation & Setup

1️⃣ Clone the repository
```bash
git clone https://github.com/jaivardha15/Multi-Disease-Prediction-System.git
cd Multi-Disease-Prediction-System
```
2️⃣ Create a virtual environment (optional but recommended)
```bash
python -m venv venv
source venv/bin/activate   # Linux / Mac
venv\Scripts\activate      # Windows
```
3️⃣ Install dependencies
```bash
pip install -r requirements.txt
```
4️⃣ Run the application
```bash
streamlit run app.py
```

## 📊 How It Works

User selects a disease from the sidebar

Inputs required medical parameters

Data is passed to the corresponding ML model

Model predicts the result

Output is displayed instantly

## ☁️ Deployment

This app can be deployed easily on:

Streamlit Cloud

Render

Hugging Face Spaces

## Streamlit Cloud Steps:

Push code to GitHub

Connect repository to Streamlit Cloud

Set app.py as entry point

Deploy 🚀
