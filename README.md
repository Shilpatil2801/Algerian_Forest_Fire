# Algerian_Forest_Fire
# 🔥 Algerian Forest Fires Prediction

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![ML](https://img.shields.io/badge/Machine%20Learning-Classification-green)
![Status](https://img.shields.io/badge/Status-Active-success)

---

## 📌 Project Overview
This project focuses on predicting the occurrence of forest fires using the **Algerian Forest Fires Dataset**. The dataset contains meteorological and Fire Weather Index (FWI) features collected from two regions in Algeria.

The goal is to build a **robust classification model** that can distinguish between:
- 🔥 Fire  
- ✅ Not Fire  

---

## 📊 Dataset Summary
- **Total Samples:** 244  
- **Regions:**
  - Bejaia (Northeast Algeria)
  - Sidi Bel-Abbes (Northwest Algeria)
- **Time Period:** June 2012 – September 2012  
- **Target Classes:**
  - Fire (138)
  - Not Fire (106)

---

## 📁 Dataset Features

### 🌦️ Weather Data
- Temperature (Temp)
- Relative Humidity (RH)
- Wind Speed (Ws)
- Rain

### 🔥 Fire Weather Index (FWI) Components
- FFMC
- DMC
- DC
- ISI
- BUI
- FWI

---

## 🧠 Problem Statement
Build a **machine learning classification model** that predicts whether a forest fire will occur based on environmental and weather conditions.

---

## ⚙️ Tech Stack
- **Language:** Python  
- **Libraries:**
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn  

---

## 🚀 Project Workflow
1. Data Collection  
2. Data Cleaning & Preprocessing  
3. Exploratory Data Analysis (EDA)  
4. Feature Engineering  
5. Model Training  
6. Model Evaluation  
7. Prediction  

---

## 📈 Model Performance

| Model                | MAE     | R² Score |
|---------------------|--------|----------|
| Linear Regression   | 0.5468 | 0.9848   |
| Lasso Regression    | 0.6200 | 0.9821   |
| Ridge Regression    | 0.5642 | 0.9843   |
| ElasticNet          | 0.6576 | 0.9814   |

> *Metrics used: Mean Absolute Error (MAE) and R² Score*

> *Note: Performance may vary based on preprocessing and tuning.*

---

## 🧹 Data Preprocessing
- Handled missing values  
- Encoded categorical variables  
- Feature scaling (Standardization)  
- Date feature extraction  

---

## 📊 Future Improvements
- Hyperparameter tuning (GridSearchCV)  
- Deployment using Flask / FastAPI  
- Real-time prediction system  
- Integration with IoT weather sensors  

---

## 🤝 Contributing
Contributions are welcome! Feel free to fork the repo and submit a pull request.

---


## ⭐ Acknowledgements
- Dataset source: UCI Machine Learning Repository  
- Fire Weather Index (FWI) system  

---

## 📬 Contact
- GitHub: Shilpatil2801  
- LinkedIn: www.linkedin.com/in/shilpa-patil-709870290
