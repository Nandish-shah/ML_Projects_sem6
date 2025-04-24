# Brain_Stroke_Prediction
# 🧠 Brain Stroke Prediction System

## 📋 Overview

The Brain Stroke Prediction project is a Machine Learning-based web app that helps users predict the likelihood of a brain stroke using key health indicators. The app aims to provide early warnings for high-risk individuals by analyzing data such as age, BMI, glucose level, and more.

Built using **Python**, **Streamlit** (or similar UI framework), and **a trained ML model**, this tool provides a simple and intuitive interface for real-time stroke risk analysis.

## 🚀 Features

- 📊 Input Form for:
  - Age
  - Hypertension
  - Heart Disease
  - Marital Status
  - Work Type
  - Residence Type
  - Average Glucose Level
  - BMI
  - Smoking Status
  - Gender

- 🧠 Backend ML Model:
  - Trained on real-world healthcare dataset
  - Predicts `stroke` or `no stroke` based on user input

- 🖼️ Responsive UI:
  - Clean interface with labeled inputs
  - Real-time prediction on button click
  - Result displayed with styled visual (YES/NO)

## 🛠️ Tech Stack

- **Frontend**: Streamlit / HTML-CSS (based on screenshots)
- **Backend**: Python
- **ML Libraries**: 
  - Pandas
  - Scikit-learn
  - NumPy
- **Model Used**: (e.g., Random Forest / Logistic Regression / XGBoost)  
  *(Please specify if needed)*

## 📷 Screenshots

### 1. Home Page
- Project title: *Brain Stroke Prediction System*
- Attractive layout and welcome message

### 2. Input Form
- Dropdowns, sliders, and text fields for user data input
- All health factors gathered cleanly

### 3. Output Page
- Predict button
- Output clearly stating: `Prediction: STROKE / NO STROKE`

## 📂 Dataset Source

Dataset used: **[Kaggle - Stroke Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)**  
> Contains health data and stroke occurrences across thousands of patients.

## ⚙️ How to Run

1. Clone the repo  
```bash
git clone https://github.com/Nandish-shah/ML_Projects_sem6
cd stroke-prediction
pip install -r requirements.txt
streamlit run app.py

