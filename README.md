# 🐎 Horse Race Prediction

This project aims to **predict the winning probability of horses** in a race using machine learning models. The analysis is performed on historical horse racing data and includes extensive feature engineering, model building, evaluation, and insights for future predictions.

## 📌 Project Objective

The objective of this project is to:
- Understand the key features that influence the outcome of a horse race.
- Build a predictive model that estimates the probability of a horse winning.
- Evaluate model performance using metrics like Accuracy, ROC-AUC, and F1 Score.

---

## 📂 Dataset

- The dataset contains information about previous horse races, including:
  - Horse details
  - Jockey and trainer stats
  - Race conditions (track, distance, going)
  - Race outcome (win or not)

---

## 🧰 Tools and Technologies

| Tool / Library       | Purpose                         |
|----------------------|----------------------------------|
| Python               | Programming Language            |
| Pandas, NumPy        | Data Wrangling                  |
| Matplotlib, Seaborn  | Data Visualization              |
| Scikit-learn         | Model Building & Evaluation     |
| XGBoost              | Advanced Model Implementation   |
| Streamlit (Optional) | UI for model demo               |

---

## ⚙️ ML Models Used

- Logistic Regression
- Random Forest
- XGBoost Classifier

Best performing model: **XGBoost Classifier**  
**Achieved Accuracy: 87.32%**  
**AUC Score: 0.91**

---

## 📊 Exploratory Data Analysis (EDA)

- Visualized win distribution
- Correlation matrix of features
- Analyzed jockey and trainer win rates
- Evaluated race characteristics impact (track type, horse age, etc.)

---

## 🔍 Feature Engineering

- Created new features: win percentage, horse form index, jockey-trainer synergy
- Handled categorical variables using encoding techniques
- Scaled numerical values for model efficiency

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/psairam12p/Horse-Race-Prediction.git
   cd Horse-Race-Prediction
