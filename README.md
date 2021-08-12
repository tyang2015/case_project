**What area of specialization should I decide on in order to be financially successful?  **

**Purpose**:
From the historical data compiled on job-postings by a staffing agency, the purpose of this project is to analyze each job posting's criterion information and assess each of those criterion's relative importance on salary. 

**EDA**:
I compared salaries for each feature in elaborate visualizations and see their relative correlations. This project is useful for unemployed candidates, particularly those in secondary education to help determine their decisions (eg. which degree or industry should they plan for in the short-term) to maximize their salary potential. It is also useful for those who are currently in the workforce, with many possible applications and has room for expanded leverage. 

**ML Prediction**:
I mainly used 3 main types of machine learning models: Linear Regression, GBM (Gradient-Boosting Machine), and Random Forest. I chose to optimize mean-squared error (MSE) as the performance metric in K-fold cross-validation, which determined Random Forest to be the model with the best performance. Based off the feature importances internalized in the model, we can determine which features ultimately have the highest predictive power for salary.

I hope you will find the codes to be informative and easy to understand.
