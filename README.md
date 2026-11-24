# Salary Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting employee salaries using Machine Learning techniques based on various professional and employment-related factors.

The model analyzes information such as job title, years of experience, education level, industry, company size, and location to estimate salaries.

The objective is to understand the relationship between employee characteristics and salary levels and build a regression model that can predict salaries using historical data.

## 🎯 Project Objectives

- Analyze salary-related data.
- Understand the factors influencing employee salaries.
- Perform data cleaning and preprocessing.
- Apply feature encoding and feature scaling.
- Build a Machine Learning regression model.
- Predict salaries based on professional characteristics.
- Evaluate model performance using regression metrics.

## 📊 Dataset Information

The dataset contains 250,000 records and 10 columns.

Important features include:

| Feature | Description |
|---|---|
| job_title | Employee job designation |
| experience_years | Years of professional experience |
| education_level | Educational qualification |
| skills_count | Number of skills |
| industry | Industry category |
| company_size | Size of the company |
| location | Employee location |
| remote_work | Remote work arrangement |
| certifications | Number of certifications |
| salary | Target variable |

## ⚙️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 🔍 Project Workflow

1. Data Loading
2. Data Exploration
3. Data Cleaning
4. Feature Selection
5. Categorical Encoding using One-Hot Encoding
6. Train-Test Split
7. Feature Scaling using StandardScaler
8. Model Building using K-Nearest Neighbors (KNN) Regressor
9. Salary Prediction
10. Model Evaluation

## 🤖 Machine Learning Algorithm

**K-Nearest Neighbors (KNN) Regression**

KNN Regression is a supervised Machine Learning algorithm that predicts continuous values based on the nearest data points.

In this project, KNN Regression is used to estimate employee salaries based on the selected employment and professional features.

## 📈 Model Evaluation

The model is evaluated using the following regression metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared (R²)
- Adjusted R-squared

These metrics help assess the prediction errors and the model's ability to explain salary variations.

## 📂 Project Structure

```text
Salary-Prediction-using-ML/
│
├── Salary Prediction - Regression(1).ipynb
├── salary_prediction_dataset.csv
└── README.md
```

## 🚀 Future Enhancements

- Compare multiple regression algorithms.
- Perform hyperparameter tuning.
- Improve model performance.
- Develop an interactive salary prediction application.
- Deploy the trained model.

## 📝 Conclusion

This project demonstrates the application of Machine Learning in salary prediction using regression techniques.

By analyzing professional and employment-related factors, the project aims to estimate employee salaries and provide insights into salary patterns.

It provides practical experience in data preprocessing, feature engineering, regression modeling, and model evaluation.

---

**Project Domain:** Machine Learning | Regression | Salary Prediction

**Algorithm:** K-Nearest Neighbors Regression

**Language:** Python
