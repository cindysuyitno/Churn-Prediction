# Data Science Project: Churn-Prediction
This project aims to predict the users that has high probability of churn and vice versa. The model use primarily user's retention days and buying frequency to get the predicted number of purchase and probability of being alive. The main aim of the model is to assist marketing team generating more targetted campaign. The segmented users (most-likely-to-churn, probably-churning, not-likely-to-churn) can be examined more to get better understanding of each segments' behavior and interest. With total of 8 years transactions data are used to predict the probabiliry of churn in the next 5 months.

# Technologies used
Python (Lifetime, Matplotlib, Pandas)

## Table of Content:
### Data Collection:
  - Sources: confidential
  - Eight years transaction data
  - Contains user_id and transaction date
### Data Cleaning:
  - Summarize transaction frequency per user and the retention between first and last transaction (in days)
  - Removing user with transaction less than 2
### Data Modelling:
  - There are 2 parameters of the Lifetime model that can be used: probability alive prediction and purchase prediction

# Illustration
![alt text](https://github.com/cindysuyitno/Churn-Prediction/blob/main/churn_1.png)
![alt text](https://github.com/cindysuyitno/Churn-Prediction/blob/main/churn_2.png)

# Conclusion and Suggestions from the Author 
The churn prediction project is a very beneficial project in any marketing team, since churn users are generally one of the problems any company have to deal with. With the end accuracy of 81.63%, it is considered quite successfull to predict whether users are morelikely to churn. However, more elaboration projects are needed in the future to make it easily used and interpreted. There are some parameters to be considered, e.g. is there any influence of having higher or lower period of prediction, what kind of raw data is the most suitable to determine user's churn probability, etc. Since the raw data used in this project is general data (not filtered), maybe different training data (like filtered for members or loyal customer only) can give a better fitted prediction of the customers.
