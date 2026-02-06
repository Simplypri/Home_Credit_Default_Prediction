Home Credit Default Risk Prediction
1. Project Overview

Home Credit aims to expand financial inclusion by providing loans to individuals with limited or no credit history. This project addresses the Home Credit Default Risk problem by building machine learning models to predict the probability of loan default using applicant demographic, financial, and credit history data.

The objective is to improve credit risk assessment while minimizing bias and maximizing predictive performance.

2. Objectives

Perform exploratory data analysis on structured financial data

Engineer meaningful features from raw applicant information

Train and evaluate machine learning models for default prediction

Compare model performance using robust classification metrics

Identify key drivers influencing loan default risk

3. Dataset Description

Source: Home Credit Default Risk dataset (Kaggle)

Target Variable:

TARGET = 1 ? Client with payment difficulties

TARGET = 0 ? Client with no payment difficulties

Key Feature Categories:

Applicant demographics (age, gender, family status)

Financial indicators (income, credit amount, annuity)

Employment and housing information

Credit history indicators

Data Preprocessing

Missing value handling

Categorical variable encoding

Feature scaling for numerical attributes

Removal of highly correlated or low-importance features

4. Methodology
4.1. Exploratory Data Analysis (EDA)

Distribution analysis of income, credit amount, and age

Default rate comparison across demographic groups

Correlation analysis to identify influential predictors

4.2. Feature Engineering

Derived financial ratios (e.g., credit-to-income)

Binning of continuous variables

Encoding categorical variables for ML compatibility

4.3. Machine Learning Models

The following models were implemented and compared:

Logistic Regression

Random Forest Classifier

Gradient Boosting / Ensemble Models

Hyperparameter tuning was applied to improve performance.

5. Evaluation Metrics

Models were evaluated using:

Accuracy

Precision

Recall

F1-score

ROC–AUC

Emphasis was placed on recall and ROC–AUC, as false negatives are costly in credit risk assessment.

6. Key Insights

Income, credit amount, and employment duration are strong predictors of default risk

Ensemble models outperform linear baselines

Feature engineering significantly improves model performance

Class imbalance impacts prediction and must be handled carefully

7.Tech Stack

Programming Language: Python

Libraries:

NumPy

Pandas

Scikit-learn

Matplotlib

Seaborn

Environment: Jupyter Notebook