# Credit-Card-Default-Prediction

Numerous companies from financial indutry often invest considerable resources to improve their predictive models with the aim of having better insights into their customers. Such an interest in model improvement has intensified in recent years mostly because of fast development of machine learning and artificial intelligence. For standard lending institution default predictive model with high performance helps to considerably minimize Credit Loss, resulting in higher revenue and profits. Usually the better predictive model the more efficient is the underwriting policy and collection process. A well-functioning model should distinguish creditworthy customers from those that are credit risks. Often, more-predictive credit-decisioning model can identify a greater number of customers within an institution’s specified risk tolerance, which should expand revenues as well.

In this project the goal is to increase detection of defaulted loans before the loan is issued/offered by P2P lending company - Lending Club. Peer-to-peer lending differs from traditional financial institutions like banks or commercial lending companies.

![image](https://user-images.githubusercontent.com/84207691/160981727-d2818760-5431-4492-8ae5-0bab5bfbd5e2.png)

# Problem Statement Analysis

Loan default occurs when a borrower fails to pay back a debt according to the initial arrangement. In the case of most consumer loans, this means that successive payments have been missed over the course of weeks or months. Fortunately, lenders and loan servicers usually allow a grace period before penalizing the borrower after missing one payment. The period between missing a loan payment and having the loan default is known as delinquency. The delinquency period gives the debtor time to avoid default by contacting their loan servicer or making up missed payments. Defaulting on a loan will cause a substantial and lasting drop in the debtor's credit score, as well as extremely high interest rates on any future loan. For loans secured with collateral, defaulting will likely result in the pledged asset being seized by the bank. The most popular types of consumer loans that are backed by collateral are mortgages, auto loans and secured personal loans. For unsecured debts like credit cards and student loans, the consequences of default vary in severity according to the type of loan. In the most extreme cases, debt collection agencies can garnish wages to pay back the outstanding debt. ###The loan is one of the most important products of the banking. All the banks are trying to figure out effective business strategies to persuade customers to apply their loans. However, there are some customers behave negatively after their application are approved.

# Data Pipeline

Feature engineering: we’ve removed unnecessary features. Since there were many columns with more than 70% of null values.

Data Analysis: We used visualization tools like seaborn and matplotlb to get a visual analysis on the features selected in above sections.

Encoding of features: In this section, we manually went through each feature, analysed them using EDA and encoded them into Label and One Hot encode.

Model Selection: In this section, we have first created a baseline model and have used XGboost as our Machine Learning architecture.

Model Interpretability: Used SHAP to interpret our black-box model using force plots and feature importance plots.

# Our Model Summary

Click Here to view Presentation in Pdf()

Developed an XGBoost binary classifier to predict whether a customer will default on a loan and achieved the Recall scores of 84% on test data respectively. Basic data inspection by Exploratory Data Analysis using Matplotlib and Seaborn giving an in-depth intuition to the important features of our dataset. Missing value imputation using KNN-Imputer, implemented SMOTE boosting, and carried out hyperparameter tuning using RandomizedSearchCV.
