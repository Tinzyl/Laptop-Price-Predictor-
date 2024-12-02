# 💻 Laptop Price Predictor 💰

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)  
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Random%20Forest-orange.svg)  
![Status](https://img.shields.io/badge/Status-Complete-brightgreen.svg)  

---

## **Project Description** 📜
This project predicts laptop prices based on their specifications using machine learning techniques. The dataset includes features like brand, RAM, screen resolution, and weight, providing valuable insights for consumers and retailers.

---

## **Features** ✨
- **Data Preprocessing**:
  - Removed duplicates and converted categorical and string data into numeric formats.
  - Engineered features such as `TouchScreen` and `IPS Panel` for enhanced modeling.

- **Exploratory Data Analysis (EDA)**:
  - Visualized the distribution of prices and relationships with key features like brand, type, and RAM.

- **Modeling**:
  - Trained a **Random Forest Regressor** for price prediction.
  - Used GridSearchCV for hyperparameter tuning.

- **Evaluation**:
  - Metrics: Mean Absolute Error (MAE), Mean Squared Error (MSE), R².
  - Achieved **R² = 0.91**, demonstrating high predictive accuracy.

