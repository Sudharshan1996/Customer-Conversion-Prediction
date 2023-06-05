# Customer-Conversion-Prediction

## Problem Statement
You are working for a new-age insurance company and employ mutiple outreach plans to sell term insurance to your customers. Telephonic marketing campaigns still remain one of the most effective way to reach out to people however they incur a lot of cost. Hence, it is important to identify the customers that are most likely to convert beforehand so that they can be specifically targeted via call. We are given the historical marketing data of the insurance company and are required to build a ML model that will predict if a client will subscribe to the insurance.

## Libraries Used
- Pandas
- Numpy
- Matplotlib
- Seaborn
- XgBoost
- Sklearn
- Warnings
- Imblearn

## Installation
Install all Flask requirements by run the following command
```
    pip install -r requirements.txt
```
## How the model is developed
- The dataset - customer_details is a history of customers who accepted or rejected the insurance when called via phone.
- The data is highly imbalanced because of a reason that only a few will accept insurance.
- With the details of the customer provided, six features that affect acceptance percentage the most were selected.
- Classification models (Logistic Regression, K-Nearest Neighbors, Decision Tree, Random Forest, XgBoost) are used for training.
- XgBoost comes out to be the best model.
- I am using free cloud service which provides limited ROM. So, I used the Decision Tree pickle file to predict the customers who accept the insurance beforehand.
- **Note:** If you are also using a Decision Tree pickle file like me and using a free cloud service remove xgboost==1.6.2 from the requirements.txt file.
