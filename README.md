# 💻 Laptop Price Predictor

This is a web app that predicts the price of a laptop based on its specifications — built using **Streamlit** and trained on real-world laptop data.

[![Deploy to Render](https://img.shields.io/badge/Deployed%20on-Render-blue)](https://laptop-price-predictor-0mz6.onrender.com)  
🔗 **Live App:** [Click here to try it](https://laptop-price-predictor-0mz6.onrender.com)

---

## 🚀 Features

- Predicts laptop prices using:
  - Brand
  - Processor
  - RAM, Storage (HDD/SSD)
  - Screen features (Touchscreen, IPS, Resolution)
  - Operating System
- Clean, interactive UI built with Streamlit
- Trained on real-world dataset using:
  - Scikit-learn
  - XGBoost
  - Pipeline + OneHotEncoder

---

## 📊 Model Details

- Final model: **StackingRegressor**
- Uses:
  - XGBoost
  - Gradient Boosting
  - Random Forest
  - Ridge Regression (as meta-model)
- Target variable: `log(Price)` for better regression performance

---

## 🛠️ Tech Stack

- Python 3.10
- Pandas, NumPy, Scikit-learn, XGBoost
- Streamlit for UI
- Render for deployment

---

## 🧪 Run Locally

1. **Clone the repo:**
   ```bash
   git clone https://github.com/Infrazor/Laptop-Price-Predictor.git
   cd Laptop-Price-Predictor
