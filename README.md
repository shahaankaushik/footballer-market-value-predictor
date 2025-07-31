# ⚽ Footballers' Market Value Prediction (Machine Learning)

This project predicts the **market value (€)** of professional footballers using player performance stats and attributes. It leverages machine learning models to estimate player value and determine the most influential factors.

---


📊 Project Highlights
🔍 Business Use Case: Estimate player market value to support clubs in scouting, pricing, and contract decisions.

🧠 Model Used: Random Forest Regressor

📈 Tech Stack: Python, Pandas, Scikit-learn, Matplotlib, Seaborn

📊 Visualization: Actual vs Predicted values, Top 15 important features

💡 Insights: Identified key factors influencing a footballer's market price such as overall rating, international reputation, and skill moves.

---

## 📊 Dataset

- CSV file with data on football players, including:
  - Player attributes (pace, shooting, passing, etc.)
  - Age, nationality, club, contract length
  - Target: `Market Value (€)`

---

## 🔍 Features

- Data cleaning and preprocessing
- Feature selection and encoding
- Model comparison: **Linear Regression** vs **Random Forest**
- Visualizations for feature importance and model evaluation

---

## 🧠 Modeling

- Baseline model: **Linear Regression**
- Advanced model: **Random Forest Regressor**
- Evaluated using:
  - R² Score
  - Mean Absolute Error (MAE)
- Visualized prediction accuracy with scatter plot

---

## 📈 Results

- **Random Forest** outperformed Linear Regression significantly.
- Key influential features included:
  - Overall rating
  - Age
  - International reputation
  - Skill stats (e.g., dribbling, passing, pace)

---

## 📷 Actual vs Predicted Plot
![Actual vs Predicted](actual_vs_predicted.png)

## 🔥 Top Features Impacting Market Value
![Feature Importance](feature_importance.png)
