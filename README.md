# 🔥 Forest Fire Prediction Web Application

## 📌 Project Overview
This project is an end-to-end Machine Learning application that predicts the **Fire Weather Index (FWI)** using meteorological data.  
It includes data preprocessing, exploratory data analysis (EDA), model training, and deployment using Flask.

The goal is to help identify fire risk based on environmental conditions such as temperature, humidity, wind speed, and rainfall.

---

## 🚀 Features
- 🔹 Data Cleaning & Preprocessing
- 🔹 Exploratory Data Analysis (EDA)
- 🔹 Multiple ML Models (Linear, Ridge, Lasso)
- 🔹 Model Evaluation (R², MAE)
- 🔹 Flask Web Application
- 🔹 REST API (`/predict_api`)
- 🔹 Animated UI (Fire, Smoke, Particles)
- 🔹 Real-time Prediction

---

## 🧠 Machine Learning Workflow
1. Data Cleaning
2. Feature Engineering
3. Exploratory Data Analysis
4. Model Training
5. Model Evaluation
6. Model Selection (Ridge Regression)
7. Deployment using Flask

---

## 📊 Dataset Information
The dataset contains weather and fire-related features:

- Temperature
- Relative Humidity (RH)
- Wind Speed (WS)
- Rain
- FFMC (Fine Fuel Moisture Code)
- DMC (Duff Moisture Code)
- ISI (Initial Spread Index)
- Classes (Fire / Not Fire)
- Region

---

## 🤖 Model Used
**Ridge Regression**

✔ Chosen because:
- Handles multicollinearity  
- Improves generalization  
- Reduces overfitting  

---

## 📈 Model Evaluation
- **R² Score** → Measures accuracy  
- **Mean Absolute Error (MAE)** → Measures average error  

---

## 🖥️ Web Application

### 🔹 Input Page
Users enter environmental conditions.

### 🔹 Output Page
Displays predicted Fire Weather Index.

---

{
  "data": [Temperature, RH, WS, Rain, FFMC, DMC, ISI, Classes, Region]
}
