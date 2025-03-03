# Employee Attrition Analysis

## Overview
This project analyzes employee attrition using data-driven techniques. The goal is to identify key factors influencing employee turnover and provide insights to improve retention strategies.

## Features
- **Data Preprocessing**: Cleans and preprocesses employee data for analysis.
- **Exploratory Data Analysis (EDA)**: Provides insights through visualizations and statistical summaries.
- **Machine Learning Models**: Applies classification models to predict employee attrition.
- **Model Evaluation**: Assesses model performance using accuracy, precision, recall, and other metrics.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-Learn

## Usage
- Run the notebook step by step to preprocess data, perform EDA, and train models.
- Modify hyperparameters to improve model performance.
- Use visualizations to derive insights from the data.
- Conclusions

## Model Conclusion
Both Decision Tree and Random Forest classifiers were effective in predicting which employees were most likely to leave the company, each offering distinct advantages. The Decision Tree model excels in interpretability and has high recall for identifying employees at risk of leaving. Meanwhile, Random Forest provides more robust generalizability with a slightly reduced feature set. For this project, Random Forest is the better option due to its scalability and efficiency.

Random Forest has consistently performed better.

## Project Outcomes
Supervisor Engagement: The ML model analysis highlighted SupervisorReview as a top feature influencing whether employees stay or leave. Higher supervisor ratings were associated with greater retention, emphasizing the importance of positive supervisory relationships.

Stress Management: StressLevel emerged as a significant predictor in both models. Employees with higher stress levels were more likely to leave, indicating a need for stress management strategies to improve retention.

Salary and Growth: Salary and Salary_Percentage_Increase were among the most influential features in predicting turnover. Lower salary increases correlated with higher turnover, supporting the importance of competitive pay progression.

Department-Specific Retention Efforts: DepartmentCode was another critical feature, with some departments exhibiting significantly lower turnover rates. Identifying and replicating high-retention department strategies can improve overall employee retention.

Employee Wellbeing: The engineered feature JobMentalWellbeing, which combines satisfaction, engagement, and peer feedback scores, strongly influenced retention. Focusing on mental wellbeing can significantly reduce turnover rates.
