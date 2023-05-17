# Customer-Churn-Prediction

## Churn Prediction using Logisitic Regression
### Data Dictionary
There are multiple variables in the dataset which can be cleanly divided in 3 categories:

### Demographic information about customers
customer_id - Customer id

vintage - Vintage of the customer with the bank in number of days

age - Age of customer

gender - Gender of customer

dependents - Number of dependents

occupation - Occupation of the customer

city - City of customer (anonymised)

Customer Bank Relationship
customer_nw_category - Net worth of customer (3:Low 2:Medium 1:High)

branch_code - Branch Code for customer account

days_since_last_transaction - No of Days Since Last Credit in Last 1 year

Transactional Information
current_balance - Balance as of today

previous_month_end_balance - End of Month Balance of previous month

average_monthly_balance_prevQ - Average monthly balances (AMB) in Previous Quarter

average_monthly_balance_prevQ2 - Average monthly balances (AMB) in previous to previous quarter

current_month_credit - Total Credit Amount current month

previous_month_credit - Total Credit Amount previous month

current_month_debit - Total Debit Amount current month

previous_month_debit - Total Debit Amount previous month

current_month_balance - Average Balance of current month

previous_month_balance - Average Balance of previous month

churn - Average balance of customer falls below minimum balance in the next quarter (1/0)

### Churn Prediction using Logisitic Regression
Now, that we understand the dataset in detail. It is time to build a logistic regression model to predict the churn. I have included the data dictionary again here for reference.

- Load Data & Packages for model building & preprocessing
- Preprocessing & Missing value imputation
- Select features on the basis of EDA Conclusions & build baseline model
- Decide Evaluation Metric on the basis of business problem
- Build model using all features & compare with baseline
- Use Reverse Feature Elimination to find the top features and build model using the top 10 features & compare
