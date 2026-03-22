Sales Prediction & Customer Analysis
📖 Overview

This project analyzes customer data and builds machine learning models to predict car purchase amounts. It combines exploratory data analysis (EDA) with predictive modeling to uncover patterns and support data-driven business decisions.

🎯 Business Objective
Identify key factors influencing customer purchasing behavior
Predict car purchase amounts accurately
Compare multiple machine learning models
Provide actionable insights to improve sales performance

📂 Dataset Description
The dataset includes customer attributes such as:
Age
Gender
Annual Income
Credit Card Debt
Net Worth
Car Purchase Amount (Target Variable)

🛠️ Tools & Technologies
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
XGBoost
Exploratory Data Analysis
Data cleaning and preprocessing
Handling missing values and duplicates
Outlier detection and treatment
Correlation analysis to identify key relationships
🤖 Machine Learning Models

The following regression models were implemented and evaluated:

Linear Regression
Baseline model
Performs well when relationships are linear
Random Forest Regressor
Ensemble learning method
Captures non-linear relationships
XGBoost Regressor
Advanced boosting algorithm
Optimized for performance and accuracy

📊 Model Performance Comparison
Model	R² Score	MAE
Linear Regression	1.00	280.10
Random Forest	0.95	1650.10
XGBoost	0.95	1683.04

👉 Best Performing Model: Linear Regression

🧠 Model Insights
Linear Regression achieved near-perfect performance, indicating a strong linear relationship between features and the target variable
Random Forest and XGBoost performed slightly worse, suggesting that complex models are not necessary for this dataset
Key features such as annual income and net worth strongly influence purchase amount

📊 Key Insights
💰 Annual income is the strongest predictor of car purchase amount
📈 Net worth significantly impacts purchasing behavior
🎯 High-value customers contribute the most to revenue
⚙️ Customer behavior in this dataset follows a largely linear pattern

📈 Business Recommendations
Target high-income and high-net-worth customers with premium products
Use predictive models to identify high-value customers
Implement data-driven marketing strategies
Provide financing options to attract mid-income segments

📌 Conclusion

The project demonstrates that simple models like Linear Regression can outperform more complex models when the data exhibits strong linear relationships. The insights derived can help businesses improve targeting, optimize marketing strategies, and increase revenue.
