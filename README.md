# 🏠 House Price Prediction using Linear Regression

A Machine Learning project built using **Python** and **Scikit-learn** to predict California house prices based on various housing characteristics.

---

## 📌 Project Overview

This project uses **Multiple Linear Regression** to estimate house prices using features such as location, income, population, number of rooms, and proximity to the ocean.

The objective of this project is to understand how regression models work on real-world datasets and how to evaluate their performance using appropriate regression metrics.

---

## 🎯 Problem Statement

House prices depend on several factors such as location, income levels, population density, and housing characteristics.

The goal of this project is to build a machine learning model that can predict the **median house value** of a district using the available housing features.

---

## 📂 Dataset Information

This project uses the **California Housing Dataset**.

### Dataset Characteristics

* **Total Records:** 20,640
* **Features:** 9 original features
* **Target Variable:** `median_house_value`

### Features Used

| Feature            | Description                |
| ------------------ | -------------------------- |
| longitude          | Geographic longitude       |
| latitude           | Geographic latitude        |
| housing_median_age | Median age of houses       |
| total_rooms        | Total number of rooms      |
| total_bedrooms     | Total number of bedrooms   |
| population         | Population in the district |
| households         | Number of households       |
| median_income      | Median income of residents |
| ocean_proximity    | Distance from the ocean    |

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook

---

## 🧠 Machine Learning Concepts Used

* Multiple Linear Regression
* Missing Value Handling
* One-Hot Encoding
* Train-Test Split
* Regression Model Evaluation

---

## ⚙️ Data Preprocessing

### 1. Missing Value Handling

The `total_bedrooms` column contained missing values.

These values were filled using the **median** of the column.

### 2. Encoding Categorical Variables

The `ocean_proximity` feature was converted into numerical format using **One-Hot Encoding**.

This allowed the regression model to process categorical information effectively.

---

## 🚀 Project Workflow

```text
Load Dataset
      ↓
Understand Dataset
      ↓
Handle Missing Values
      ↓
One-Hot Encoding
      ↓
Define Features and Target
      ↓
Train-Test Split
      ↓
Train Linear Regression Model
      ↓
Make Predictions
      ↓
Evaluate Model Performance
```

---

## 🤖 Algorithm Used

### Multiple Linear Regression

Linear Regression models the relationship between the target variable and multiple independent variables using a linear equation.

The model attempts to find the best-fitting line (or hyperplane) that minimizes prediction errors.

---

## 📊 Model Performance

| Metric                         | Value            |
| ------------------------------ | ---------------- |
| Mean Absolute Error (MAE)      | 50,670.74        |
| Mean Squared Error (MSE)       | 4,908,476,721.16 |
| Root Mean Squared Error (RMSE) | 70,060.52        |
| R² Score                       | 0.6254           |

---

## 📈 Result Interpretation

* The model's predictions differ from the actual house prices by approximately **$50,671 on average**.
* The model explains approximately **62.54% of the variation** in house prices.
* Considering the complexity of real-world housing markets, this serves as a solid baseline regression model.

---

## 📚 What I Learned

Through this project, I learned:

* The fundamentals of Multiple Linear Regression
* How to handle missing values in real datasets
* Why One-Hot Encoding is important for categorical variables
* The difference between classification and regression evaluation metrics
* How to evaluate regression models using:

  * MAE
  * MSE
  * RMSE
  * R² Score

---

## 🔮 Future Improvements

* Apply Feature Scaling
* Perform Residual Analysis
* Experiment with Polynomial Regression
* Compare performance with Decision Tree Regressor
* Compare performance with Random Forest Regressor
* Tune model parameters to improve predictive performance

---

## 📁 Project Structure

```text
house-price-prediction/
│
├── House_Price_Prediction.ipynb
├── housing.csv
├── README.md
└── requirements.txt
```

---

## 👨‍💻 Author

**Banty Kumar**

Electrical Engineering Undergraduate at NIT Patna

Currently learning Machine Learning through practical projects and hands-on implementation.

---

## ⭐ Acknowledgement

This project was developed as part of my Machine Learning learning journey to strengthen my understanding of regression techniques and real-world data preprocessing.

If you found this project helpful, feel free to explore the code and provide suggestions for improvement.
