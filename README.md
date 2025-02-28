# Predicting Employee Attrition Using Machine Learning

## Project Overview
This project aims to predict employee departures using machine learning. The dataset consists of 300,000 employee records, including features such as gender, distance to the office, salary changes, and performance reviews. The analysis includes data visualization, feature selection, and model training.

## Dataset
- Source: [Dataset Link](https://raw.githubusercontent.com/msaricaumbc/DS_data/master/ds602/midterm/employee_departure_dataset.csv)
- Contains employee demographics, salary trends, and review ratings.
- The target variable is "Left" (1 = Employee Left, 0 = Employee Stayed).

## Features
- **Gender**: Male or Female
- **Distance**: Distance from home to the office
- **YearsWorked**: Total years an employee has worked
- **Previous Salary & Current Salary**: Compensation trends
- **Reviews**: Employee and supervisor feedback scores

## Steps in the Project
1. Data Cleaning and Preprocessing
2. Exploratory Data Analysis (EDA)
3. Handling Imbalanced Data
4. Feature Engineering
5. Model Selection and Training
6. Model Evaluation and Performance Metrics

## Technologies Used
- Python (Pandas, NumPy, Scikit-Learn, Matplotlib)
- Jupyter Notebook
- Machine Learning (Logistic Regression, Decision Trees, Random Forest)

## Results & Insights
- Significant impact of **distance to the office** on employee retention.
- Imbalanced dataset: More employees stay than leave.
- Initial model evaluation determines whether categorical variables need encoding.
