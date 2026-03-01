# Loan-Approval-Prediction-with-Credit-Line-Determination

This repository provides an end-to-end machine learning solution designed to automate the loan underwriting process. By leveraging historical financial data, the system predicts the likelihood of loan approval and calculates an appropriate credit limit for approved applicants.

##Project Overview
Financial institutions require robust systems to minimize default risk while maximizing lending efficiency. This project implements a dual-stage predictive pipeline:
-Classification: Determines whether a loan should be approved or rejected based on applicant risk profiles.
-Regression: Estimates a sustainable credit line for approved candidates using predictive modeling.

##🛠 Features
-Automated Risk Assessment: Replaces manual screening with high-accuracy classification models.
-Dynamic Credit Scoring: Utilizes regression techniques to determine creditworthiness.
-Data-Driven Insights: Includes comprehensive Exploratory Data Analysis (EDA) to identify key predictors of default.
-Scalable Pipeline: Structured code for preprocessing, feature engineering, and model evaluation.

##🗂 Repository Structure
-Loan_Approval_Prediction.ipynb: The primary Jupyter Notebook containing data cleaning, visualization, model training, and performance metrics.
-data/: Directory containing the datasets used for training and testing.
-models/: (If applicable) Saved model weights or serialized objects for deployment.

##🚀 Getting Started
Prerequisites:
Ensure you have Python 3.8+ installed. You will need the following libraries:
-Pandas & NumPy (Data Manipulation)
-Scikit-Learn (Machine Learning Algorithms)
-Matplotlib & Seaborn (Visualization)
-XGBoost or LightGBM (High-performance Modeling)

##📊 Methodology
-Preprocessing: Handling missing values, encoding categorical variables, and feature scaling.
-Feature Engineering: Deriving debt-to-income ratios and credit utilization metrics.
-Model Selection: Comparison of Logistic Regression, Random Forests, and Gradient Boosting machines.
-Evaluation: Models are assessed using Precision-Recall curves, F1-Score, and Mean Absolute Error (MAE) for credit line predictions.
###🤝 Contributing
Contributions are welcome. Please fork the repository and submit a pull request for any enhancements or bug fixes.
