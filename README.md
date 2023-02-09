# Customer-Churn---Ecommerce-Data

# Customer Churn Prediction
![image](https://user-images.githubusercontent.com/42872872/158339814-d33fb740-9d1e-4d31-acfa-faccaac69afc.png)\
Churn prediction is identifying customers that are most likely to live a service. This is important for most companies as acquiring new customers is more costlier than retaining old ones, So the results of Churn prediction help companies focus on customers that are likely to churn and develop strategies for retaining those customers.

Here I worked with [E Commerce Customer](https://www.kaggle.com/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction).\
The work flow of the project is given below
## Table of Contents
* [Exploratory Data Analysis](#section-one)
* [Data Preprocessing](#section-two)
    - [Missing Value Treatment](#subsection-one)
    - [Categorical Encoding](#subsection-two)
* [Model Development](#section-three)
* [Conclusion](#section-four)

# Conclusion:
After building the 4 models, the tree classifiers performed better than the linear classifiers, with XGBoost performing best with a test f1-score of **91.73%**. I then tuned the xgboost hyperparameters which resulted in a 1.2% increase in cross validation score, and a 1.1% increase in test score.

The **true positive rate is 93.68%** which means we can correctly identify 93% of the customers that will leave.

The **precision is also 93.68%** which means out of the predicted customers that will leave, 93% will actually leave

From the models feature importance the top three features with impact on customer's churn probability are;
* The Tenure of the customer.
* Whether the customer has a complain on the service or not, as expected those with complains have higher churn rate than those without complain.
* The order category of the customers, where those on the mobile category have higher churn rate than other categories.

**These features importances were seen in the visualizations in the EDA section and were documented as findings.**

