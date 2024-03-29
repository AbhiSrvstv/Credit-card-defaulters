# Credit Card Default Prediction

  ![image](https://user-images.githubusercontent.com/99960098/172371124-18371712-36f6-4d14-8f73-61354b115038.png)
## Overview
This project is aimed at predicting the case of customers default payments in Taiwan.
From the perspective of risk management, the result of predictive accuracy of the
estimated probability of default will be more valuable than the binary result of
classification - credible or not credible clients. The main objective is to build a
predictive model, which could help them in predicting the customers who might
default in upcoming months.
Credit card default happens when you have become severely delinquent on your
credit card payments. Missing credit card payments once or twice does not count as
a default. A payment default occurs when you fail to pay the Minimum Amount Due
on the credit card for a few consecutive months.

## Data Understanding
The dataset contains 30000 rows and 25 columns. This project employed a binary
variable, default payment (Yes = 1, No = 0), as the response variable. After reviewing
the literature and the 23 variables are taken as explanatory variables.
![image](https://user-images.githubusercontent.com/99960098/172366978-0a6e26ee-bb3e-4f42-80f9-0f6fca9b45d2.png)
The dataset had a class imbalance where only 22% of the customers defaulted on their payment.

## Dataset
![image](https://user-images.githubusercontent.com/99960098/172367323-f54935b2-694b-4026-96f6-23d51dc6ba11.png)
The measurement scale for the repayment status is:

    -1 = pay duly
    1 = payment delay for one month
    2 = payment delay for two months
    [...]
    8 = payment delay for eight months
    9 = payment delay for nine months and above
    
## Models Used and Result
This is a binary classification problem where the target variable is whether or not a client will default on their payment (Yes = 1, No = 0). After cleaning the data, handling class imbalance using SMOTE and feature engineering, several baseline models were fit to the training data. Baselines included Logistic Regression, Random Forest Classifier, XGBoost Classifier. Each model iteration's hyperparameters were tuned with GridSearchCV and RandomSearchCV. Predictions were evaluated using the ROC_AUC Score.

The final Random Boost model achieved an ROC_AUC score of 0.9116.
  
  ![image](https://user-images.githubusercontent.com/93547700/188253603-07952587-07b4-42ab-afa3-1c60bbcc94f7.png)


## 🚀 About Me


- 👋 Hi, I’m Abhishek, a curious Data Scientist
- 👀 I’m currently working on Machine Learning projects.
- 🌱 I’m currently learning various machine learning models and deep learning techniques.
- 💞️ I’m would love to collaborate on Machine Learning projects.
- 📫 How to reach me : abhishekanand3120@gmail.com
- 👀 LinkedIn : https://www.linkedin.com/in/abhshkannd/


