# Car-Loan-Default-Prediction
This machine learning project aimed at predicting car loan defaults for a Non-Bank Financial Company (NBFC). The project focuses on optimizing expected gross profit by leveraging customer characteristics to assess loan repayment probabilities.

# Tools & Techniques:
R Studio

# Key Features:
## 1.Business Context:
To address a surge in car loan defaults (15-year high) by predicting loan repayment capabilities.
## 2.Objective: 
Maximize expected gross profit through data-driven loan approval decisions.
## 3.Data:
- Dataset: 121,856 car loan records from a Kaggle competition.
- Features: Loan details, client demographics, financial data, and verification metrics.
## 4.Methodology:
- Data Preprocessing: Addressed missing data with strategies including mode imputation, categorical labeling, and MICE for numerical variables.
- Unsupervised Learning: Conducted PCA to extract principal components representing significant customer segments.
## 5.Modeling:
- Implemented Logistic Regression, Classification Trees, and Random Forests.
- Logistic Regression selected based on cross-validation results (accuracy and R² scores).
- Defined a profit-maximizing threshold of 8.2% for loan approval.
## 6.Results:
- Achieved optimized classification performance, balancing accuracy and business profit.
- Developed actionable insights into borrower characteristics contributing to default risk.
## 7.Deployment:
- Automated loan decision-making process with profit-maximizing thresholds.
- Included considerations for fairness, data privacy, and dynamic market conditions.
