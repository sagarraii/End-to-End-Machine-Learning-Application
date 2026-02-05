# 🔥 Algerian Forest Fire Prediction – Flask ML App

This project is an end-to-end Machine Learning application built using the **Algerian Forest Fire dataset**.  
It covers the complete ML pipeline—from data analysis to model deployment using **Flask**.

---

## 📌 Project Overview

The goal of this project is to predict fire-related outcomes based on environmental and meteorological features using regression models. After evaluating multiple algorithms, **Ridge Regression** was selected as the final model due to its stable and reliable performance.

---

## 📊 Dataset & Analysis

- Dataset: **Algerian Forest Fire Dataset**
- Performed:
  - Exploratory Data Analysis (EDA)
  - Feature Engineering (FE)
  - Data cleaning
  - Feature normalization using `StandardScaler`
  - Fire-related pattern analysis

---

## 🧠 Models Trained

The following regression algorithms were trained and evaluated:

- Linear Regression  
- Lasso Regression  
- Ridge Regression ✅ *(Selected)*
- ElasticNet Regression  

Each model was:
- Trained separately
- Evaluated using **Cross-Validation**
- Compared using:
  - **MAE (Mean Absolute Error)**
  - **R² Score**

### ✅ Final Model Choice
**Ridge Regression** was chosen as the final model based on better generalization and consistent performance.

---

## 💾 Model Artifacts

The following files are saved and used in deployment:

- `Models/ridge.pkl` → Trained Ridge Regression model  
- `Models/scaler.pkl` → Fitted `StandardScaler`

Both are loaded in the Flask application for prediction.

---

## 🚀 Tech Stack

- Python
- NumPy
- Pandas
- Scikit-learn
- Flask
- HTML (Jinja Templates)

---

## ▶️ How to Run the Application Locally

### 1️⃣ Clone the repository
```bash
git clone <your-repo-url>
cd End-to-End-Project
