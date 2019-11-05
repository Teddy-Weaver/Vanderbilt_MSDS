README - Telco Customer Churn Data

## About the Data
Each row is a customer that has or has not churned (churn = yes or no) in the last month. There are some demographic attributes but most of the data is related to the customer's subscription. This include services, contract type, billing method, tenure (length of time subscribed), monthly charges, and total charges.

A number of fields (senior_citizen, dependents, etc.) have been converted to logical, from numeric or character, during the import process.

Data Source (originally provided by IBM): https://www.kaggle.com/blastchar/telco-customer-churn

## Column Details
customer_id                Unique identifier for each customer<br>
gender                        Customer's gender (male or female)<br>
senior_citizen                TRUE/FALSE if customer is a senior citizen (65+ years old)<br>
partner                       TRUE/FALSE if the customer has a partner (e.g. wife/husband)<br>
dependents                    Number of dependents in the household (e.g. number of kids)<br>
tenure                        How long the customer has been a subscriber (# months)<br>
phone_service                 TRUE/FALSE if the customer has signed up for phone service<br>
multiple_lines                yes/no if the customer has multiple phone lines. Will say 'no phone service' if not subscribed to phone<br>
internet_service              Type of internet service (dsl, fiber optic). Will say 'no' if not subscribed to interent.<br>
online_security               yes/no if subscribed. Can only be subscribed to if also subscribed to internet<br>
online_backup                 yes/no if subscribed. Can only be subscribed to if also subscribed to internet<br>
device_protection             yes/no if subscribed. Can only be subscribed to if also subscribed to internet<br>
tech_support                  yes/no if subscribed. Can only be subscribed to if also subscribed to internet<br>
streaming_tv                  yes/no if subscribed. Can only be subscribed to if also subscribed to internet<br>
streaming_movies              yes/no if subscribed. Can only be subscribed to if also subscribed to internet<br>
contract                      Type of contract -- month-to-month, one year, two year<br>
paperless_billing             TRUE/FALSE if signed up for paperless billing<br>
payment_method                Payment method used by the customer<br>
monthly_charges               Monthly charges due (dollars)<br>
total_charges                 Total lifetime charges<br>
churn                         yes/no if the customer unsubscribed in the last month<br>
