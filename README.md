Credit Risk Prediction & Analysis
This repository contains a comprehensive data science project focused on Credit Risk Modeling. The goal is to analyze borrower data and build a predictive model to determine the likelihood of loan default, helping financial institutions mitigate risk.

 Project Structure
1.ipynb: The primary Jupyter Notebook containing the end-to-end workflow, including data cleaning, visualization, and machine learning model implementation.

1.csv: The dataset containing borrower information such as age, income, home ownership, employment length, loan intent, and credit history.

1.png / 1 (2).png: Visualizations and performance charts generated during the analysis.

 Dataset Overview
The analysis is performed on a credit dataset with the following key features:

Demographics: Age, Income, Home Ownership status.

Loan Details: Amount, Intent (e.g., Education, Medical, Venture), Interest Rate, and Grade.

Risk Factors: Historical default data and credit history length.

 Tech Stack
Language: Python

Libraries: * pandas & numpy for data manipulation.

matplotlib & seaborn for Exploratory Data Analysis (EDA).

scikit-learn for predictive modeling.

 Key Features
Data Preprocessing: Handling outliers in employment length and filling missing interest rate values.

Exploratory Data Analysis: Visualizing the correlation between loan-to-income ratios and default rates.

Modeling: Training classification models to predict the loan_status (Default vs. Non-Default).

Evaluation: Assessing model performance through accuracy, precision-recall, and confusion matrices.
