
# 💻 Laptop Price Predictor

This is a web app that predicts the price of a laptop based on its specifications — built using **Streamlit** and trained on real-world laptop data.

[![Deployed on Render](https://img.shields.io/badge/Live%20Demo-Click%20Here-brightgreen)](https://laptop-price-predictor-0mz6.onrender.com)  
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
   ```

2. **(Optional) Create virtual environment:**
   ```bash
   python -m venv venv
   venv\Scripts\activate  # On Windows
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the app:**
   ```bash
   streamlit run app.py
   ```

---

## 📁 Folder Structure

```
├── app.py               # Streamlit frontend
├── df.pkl               # Cleaned dataset (optional – ignored in .gitignore)
├── pipe.pkl             # Trained model pipeline
├── requirements.txt     # All required Python packages
└── README.md            # You're reading this
```

---

## 🧠 Future Improvements

- Add visualizations (feature importance, model comparison)
- Add batch prediction (upload CSV)
- Improve UI with Streamlit extras

---

## 🤝 Contributing

PRs and suggestions are welcome! If you find bugs or want to improve the UI/model — feel free to open an issue or fork and raise a pull request.

---
