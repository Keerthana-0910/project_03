# project_03

"SmartPremium: Predicting Insurance Costs with Machine Learning"

📌 Project Overview

This project focuses on predicting insurance premium amounts using machine learning techniques based on customer demographic, lifestyle, and financial attributes.
The system integrates data preprocessing, model training, evaluation, and deployment using a Streamlit web application for real-time premium prediction.

🏫 Domain

Data Science / Machine Learning

❓ Problem Statement

Insurance companies face challenges in accurately estimating premium amounts due to multiple influencing factors such as age, income, health habits, and policy details.
A predictive, data-driven system is required to automate premium calculation, reduce manual effort, and improve pricing consistency.

💼 Business Use Cases

Predict insurance premium for new customers
Identify high-risk customers based on input features
Assist insurance agents in decision-making
Improve transparency in premium calculation
Enable quick what-if analysis for customers

📊 Dataset Description

Dataset used: Insurance customer dataset (processed for ML modeling)

| Column Name          | Description                         |
| -------------------- | ----------------------------------- |
| Age                  | Customer age                        |
| Gender               | Male / Female                       |
| Annual Income        | Yearly income of customer           |
| Marital Status       | Single / Married                    |
| Number of Dependents | Count of dependents                 |
| Education Level      | Educational qualification           |
| Smoker Status        | Smoker / Non-smoker                 |
| Policy Type          | Insurance policy category           |
| Premium Amount       | Target variable (Insurance Premium) |

🔍 Approach

Data cleaning and preprocessing
Handling missing values using Median & Mode
Encoding categorical features
Model training using:
1. Linear Regression
2. Decision Tree
3. Random Forest
4. XGBoost
Model evaluation using MAE, RMSE, and R² score
Selection of best-performing model
Pipeline creation and saving
Deployment using Streamlit web application
Feature scaling using StandardScaler

📈 Skills Learned

Exploratory Data Analysis (EDA)
Feature engineering & preprocessing pipelines
Machine Learning model comparison
Model evaluation and interpretation
Streamlit application development
End-to-end ML deployment workflow

🧰 Technology Stack

Category	Tools

| Category             | Tools                                  |
| -------------------- | -------------------------------------- |
| Programming Language | Python                                 |
| Data Handling        | Pandas, NumPy                          |
| Visualization        | Matplotlib, Seaborn                    |
| Machine Learning     | Scikit-learn, XGBoost                  |
| Model Serialization  | Pickle                                 |
| Web Application      | Streamlit                              |
| Concepts             | EDA, Regression, Pipelines, Deployment |

🌐 Application Deployment

Streamlit web app deployed locally
User-friendly interface for entering customer details
Real-time insurance premium prediction

📦 Project Deliverables

Python source code (ML & preprocessing pipeline)

Trained model pipeline (smartpremium_pipeline.pkl)

Streamlit application script

Model evaluation results

requirements.txt

Project documentation (README.md)
