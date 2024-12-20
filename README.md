# Project Overview

This project focuses on leveraging data analysis and machine learning techniques to predict customer eligibility for loan acceptance and provide actionable insights to optimize marketing strategies. By understanding customer profiles and the factors influencing loan approval, the project aims to enhance financial decision-making and customer targeting.

# Objectives

Predict Loan Acceptance: Develop models to predict whether a customer is likely to accept a loan offer based on their profile.

Understand Influential Factors: Identify key features that influence loan acceptance decisions.

Optimize Marketing Strategies: Provide data-driven recommendations to improve the appeal and acceptance rate of loan proposals.

# Data Description

The dataset includes customer demographic, financial, and behavioral attributes such as:

ID: Customer ID

Age: Customer's age in completed years

Experience: No. of years of professional experience

Income: Annual income of the customer ($ 000)

ZIP Code: Home Address Zip Code

Family: Family size of the customer (1-4)

CCAvg: Avg. Spending on Credit Card per year ($ 000)

Education: Education Level (1: Undergrad; 2: Graduate; 3: Advanced/Professional)

Mortgage: Value of house mortgage if any ($000)

Personal Loan: Did this customer accept the personal loan offered in the last campaign?

Securities Account: Does the customer have a securities account with the bank?

CD Account: Does the customer have a certificate of deposit (CD) account with the bank?

Online: Does the customer use internet banking facilities?

Credit Card: Does the customer use a credit card issued by this bank?

# Data Preprocessing

Checked data shape, types, and frequencies.

Identified and handled missing values, duplicates, and outliers.

Transformed CCAvg from monthly to yearly spending.

Converted negative Experience values to positive.

Normalized numerical features and handled categorical data.

Described the dataset to ensure readiness for modeling.

# Models Implemented

Logistic Regression:

Baseline model to assess linear relationships.

Decision Tree:

Visualized decision-making pathways for customer eligibility.

Random Forest:

Employed for feature importance analysis and robust predictions.

K-Nearest Neighbors (KNN):

Used for instance-based learning and classification.

Support Vector Classifier (SVC):

Implemented for high-dimensional separation.

K-Means Clustering:

Grouped customers into clusters for exploratory insights.

Principal Component Analysis (PCA):

Reduced dimensionality for visualization and identified key data patterns.

Gaussian Naive Bayes:

Tested with hyperparameter tuning to handle probabilistic data.

AdaBoost:

Boosted model accuracy with ensemble learning.

# Evaluation Metrics

Accuracy: Measured overall correctness of predictions.

ROC-AUC Score: Assessed model performance in distinguishing between accepted and rejected loans.

Confusion Matrix: Visualized true positive, true negative, false positive, and false negative rates.

# Recommendations

Targeted Marketing:
Focus campaigns on segments with higher likelihood of loan acceptance based on income, family size, education and credit card usage.

Customized Offers:
Tailor loan proposals for specific demographics, emphasizing personalized financial solutions.

Customer Education:
Provide clear information about loan benefits and repayment options to build trust and increase appeal.

# View Results:
Review generated plots, metrics, and model outputs in the slides folder.

# Made by:
Vasco Freire
