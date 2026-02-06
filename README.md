# Fraud_Detection

Credit Card Fraud Detection Using Regularization and Comparative ML Models

### Problem Statement: 
Our primary goal is to identify fraudulent credit card transactions and prevent financial losses. It is essential for credit card companies to detect these fraudulent transactions in order to protect customers against financial loss and increase safety protocols for future transactions. We plan to use a combination of ML models, including Ridge and Lasso Logistic Regression, Polynomial feature expansion, and the Gradient Boosting Model, to predict whether transactions are fraudulent while attempting to minimize false negatives (stating a transaction is not fraudulent while it is in reality) and also adjusting for class imbalance. 

### Dataset we plan to use: Kaggle Credit Card Fraud Detection Dataset 
The dataset contains transactions made by credit cards in September 2013 by European cardholders. All transactions in this dataset are anonymized, with a binary variable labeling all credit card transactions as fraudulent or genuine. This dataset presents transactions that occurred within the span of two days, with 492 frauds out of 284,807 transactions. The positive class (frauds) accounts for 0.172% of all transactions, indicating that this dataset is imbalanced.  

### Machine Learning Models & Deliverables:
We plan to build, compare, and evaluate multiple classification models for fraud detection. While paying attention to overfitting, underfitting, and generalization performance. We plan to implement and compare:

* Logistic regression with Regularization
Ridge (L2) and Lasso (L1) Regularization
* K-fold cross-validation for model evaluation 
* Logistic Regression with Polynomial Feature Expansion - to explore nonlinear relationships 
Gradient Boosting Model - as a non-linear ensemble baseline

### Deliverables include:
A cleaned dataset, EDA results, trained models, evaluation metrics, and a final report summarizing methodology and findings 

### Project Roadmap/Timeline:

* Week 1-3: Brainstorm ideas for the model, decide on ML models to develop, and work on the project proposal
* Week 4: Data Preprocessing: data cleaning, sampling, and scaling data using Z-score 
* Week 5: Exploratory Data Analysis: Finding outliers, understanding dataset descriptions, Correlation analysis, and checking for skewedness, Feature Selection/Engineering
* Week 6: Model Construction: Implement the logistic regression model. Use the Sigmoid function and the Negative log likelihood cost function, as the MLE principle states
* Week 7: Model Construction: Optimize weights with Stochastic Gradient Descent to find the best fit weights for the logistic regression model, and make sure it is learning from the limited fraud samples
* Week 8: Model Optimization: Check for underfitting and overfitting, including bias-variance trade-offs. Use Lasso or Ridge regularization for optimization
* Week 9: Model Evaluation: K-fold cross-validation to prove our model’s performance is accurate 
* Week 10: Project Report writing and final edits before submission
