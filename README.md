# Medical-Insurance-Costs-prediction-Using-Machine-Learning
A machine learning project to predict individual medical insurance charges based on demographic and health-related factors such as age, BMI, smoking status, and region. The project explores data analysis, correlation insights, and model building using Linear Regression, Decision Tree, and Random Forest algorithms.
Absolutely! Below is a complete, well-structured `README.md` file you can use for your GitHub repository. You can copy and paste this directly into a `README.md` file in your project root.

---

````markdown
# 🩺 Medical Insurance Cost Prediction

A machine learning project to predict individual medical insurance charges based on demographic and health-related factors such as age, BMI, smoking status, and region. The project explores data analysis, correlation insights, and model building using Linear Regression, Decision Tree, and Random Forest algorithms.

---

## 📊 Dataset Overview

- **Source**: [Kaggle - Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)
- **Size**: 1,338 records, 7 features
- **Features**:
  - `age`: Age of the individual
  - `sex`: Gender (male/female)
  - `bmi`: Body Mass Index
  - `children`: Number of children covered by insurance
  - `smoker`: Smoking status (yes/no)
  - `region`: Residential region in the US
  - `charges`: Medical insurance cost (target variable)

---

## 🎯 Project Aim

To build and evaluate machine learning models that can accurately predict medical insurance costs based on individual features.

---

## 🎯 Objectives

- Perform exploratory data analysis (EDA) and correlation analysis
- Preprocess the dataset (check for nulls, duplicates, encode categorical variables)
- Split the data into training and testing sets
- Train and evaluate multiple regression models:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
- Compare model performance using metrics like:
  - R² (R-squared)
  - RMSE (Root Mean Squared Error)
  - MAPE (Mean Absolute Percentage Error)

---

## 📌 Summary of the Data

- **Age**: 18–64 years (mean = 39.2)
- **BMI**: 15.96–53.13 (mean = 30.66)
- **Children**: 0–5 (mean = 1.1)
- **Charges**: \$1,121.87 – \$63,770.43 (mean = \$13,270.42)
- **Most common profile**: Non-smoking male from Southeast

---

## 🔍 Correlation Insights

- `smoker` has the **strongest positive correlation** with `charges` (0.79)
- `age` (0.30) and `bmi` (0.20) have moderate correlation
- `sex` and `children` show weak correlations

---

## 🛠️ Tech Stack & Tools

- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 🤖 Model Performance

| Model                 | R² Score | RMSE      | MAPE   |
|----------------------|----------|-----------|--------|
| Linear Regression     | 0.77     | 5,538.74  | 41.79% |
| Decision Tree Regressor | 0.69  | 6,350.63  | 34.39% |
| Random Forest Regressor | **0.85** | **4,467.10** | 34.90% |

✅ **Best Model**: Random Forest Regressor (highest accuracy and lowest error)

 Future Improvements

* Hyperparameter tuning (GridSearchCV, RandomizedSearchCV)
* Advanced models like XGBoost or Gradient Boosting
* Deploy the model using Flask or Streamlit
* Incorporate additional healthcare-related features if available



```
