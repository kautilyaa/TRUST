# T.R.U.S.T (Targeted Risk Understanding & Scoring Technology)
TRUST: Targeted Risk Understanding &amp; Scoring Technology aims to predict loan defaults using the Home Credit Default Risk dataset. By employing data science methodologies, we identify key risk factors and develop a machine learning model to help lenders make informed decisions, minimize financial losses, and enhance credit risk assessment.

Targeted Risk Understanding & Scoring Technology (TRUST)
Course: Data 602 - Principles of Data Science


Authors: Arunbh Yashaswi, Swattik Matti, Eniyan Ezhilan , Ajaykumar Balakannan , Ritik Singh

# Introduction

In today's sophisticated financial environment, assessing a borrower’s ability to repay loans is crucial to risk management for lending institutions. As the credit market continues to grow, financial institutions face challenges in making well-informed decisions about loan approvals while efficiently managing the risk of defaults.

This project addresses that challenge by developing a predictive model using the Home Credit Default Risk dataset. This dataset contains detailed information about clients’ loan applications, credit histories, and socio-economic factors. Our primary goal is to build a model that evaluates, with high precision, the probability of a given applicant defaulting on a loan. This will help lenders make more informed credit decisions and minimize losses due to defaults, contributing to a more robust loan assessment process.

# Why Did We Choose This Project?

Loan default is a major issue for financial institutions, impacting profitability and credit capacity. Our project aims to apply data science techniques to predict the likelihood of loan defaults, helping institutions assess the risk efficiently.

The Home Credit Default Risk dataset offers a rich variety of features, including demographics, credit history, and repayment behavior, allowing for deep analysis and improved credit risk assessment.

# Problem We Are Solving

The key problem we address is identifying applicants who are at higher risk of defaulting on loans. With vast amounts of customer data, manually assessing risk becomes challenging. Our machine learning model will automate this prediction process, increasing the efficiency of financial institutions in determining defaulters.

Specifically, our project will:

Identify key factors that contribute to the probability of default.
Categorize applicants into different risk levels.
Provide insights into which customer profiles are more likely to default and which are likely to repay.
Dataset Source
The dataset used is from the Home Credit Default Risk challenge on Kaggle, consisting of various customer and loan data, including credit history, repayment behavior, and demographics.

# Why This Dataset?

The Home Credit Default Risk dataset is highly feature-rich, allowing for a multi-dimensional analysis of applicants' financial behavior. By incorporating external credit history, repayment trends, and loan application records, we can develop a highly accurate prediction model for loan defaults. This dataset enables us to evaluate applicants far beyond simple credit scores, identifying nuanced risk factors.

Dataset Details
application_train.csv / application_test.csv: The primary dataset containing loan applications. The training set includes a target variable indicating default.

bureau.csv: Previous credits from other institutions reported to the Credit Bureau.

bureau_balance.csv: Monthly balances for previous credits from the Credit Bureau.

POS_CASH_balance.csv: Monthly balances for POS and cash loans.

credit_card_balance.csv: Monthly balances for credit cards.

previous_application.csv: Details of previous loan applications.

installments_payments.csv: Repayment history for previous loans.

HomeCredit_columns_description.csv: Column descriptions for each dataset.


![home_credit](https://github.com/user-attachments/assets/7b53c443-7b00-4804-b28b-e086bed65ce8)

# Methodologies

We will follow the Data Science Lifecycle to predict loan defaults:

Data Collection:

We will work with the datasets provided, including application_train.csv, bureau.csv, and other relevant files from the Home Credit Default Risk dataset.

Data Processing:

Preprocessing steps include handling missing data, detecting outliers, encoding categorical variables, and normalizing numerical features to prepare the dataset for analysis.

Exploratory Data Analysis (EDA) & Visualization:

EDA will help us understand patterns and correlations between variables like loan amount, income, and credit history. Visualization tools such as heatmaps and correlation matrices will reveal the key features influencing loan default.

Analysis & Hypothesis Testing:

We will analyze relationships between variables and test hypotheses regarding the factors that lead to loan default, such as the relationship between credit history and default risk.

Machine Learning Models:

We will apply machine learning models, including Logistic Regression, Decision Trees, and Gradient Boosting, to predict default risks. Model performance will be evaluated using metrics like accuracy, precision, recall, and ROC-AUC.

Insights & Policy Decisions:

The final stage will involve deriving actionable insights from the model. These insights will help lenders assess credit risk more effectively, minimize losses, and develop responsible lending policies.

Expected Outcomes

We aim to develop a robust model with strong predictive power for loan defaults. By the end of the project, we will provide insights into key risk factors and offer financial institutions a tool to better assess applicant profiles, ultimately reducing uncertainty in loan approvals and minimizing financial risk.
