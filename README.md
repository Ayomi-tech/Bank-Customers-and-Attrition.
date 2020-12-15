# Group Project: Statistics_project

## Title: Bank Customers and Attrition  

## Team Members: Ayodeji, Shola, and Behrooz

## Date: 12.12.2020

## Data Source: [BankChurners.csv](https://www.kaggle.com/sakshigoyal7/credit-card-customers)

### The story

A manager at the bank is disturbed with more and more customers leaving their credit card services. They would really appreciate if one could predict for them who is gonna get churned so they can proactively go to the customer to provide them better services and turn customers' decisions in the opposite direction. This dataset consists of 10,000 customers mentioning their age, salary, marital_status, credit card limit, credit card category, etc. There are nearly 18 features.

The problem:
In the data set, only 16.07% of customers have churned. Thus, it could be a bit difficult to train the model to predict churning customers. Since the problem is customer attrition. we want to analyze the data to find out the reason behind this and leverage the same to predict customers who are likely to drop off.

Suggested Objectives:
	•	To find the correlation between the relevant numeric columns
	•	The main determinants of attrition (logistic regression)
	•	The relationship between type of credit card on attrition ( Logistic)
	•	The relationship between different income categories on attrition (logistic)
	•	The impact of dummy and binary variables (education and gender) on attrition 


## Dataset Columns:
- Client number: Unique identifier for the customer holding the account
Attrition: Internal event (customer activity) variable - if the account is closed then 1 else 0
- Age: Demographic variable - Customer's Age in Years
- Gender: Demographic variable - M=Male, F=Female
- Dependent_count: Demographic variable - Number of dependents
- Education_level: Demographic variable - Educational Qualification of the account holder (example: high school, college graduate, etc.)
- Marital_status: Demographic variable - Married, Single, Divorced, Unknown
- Income_category: Demographic variable - Annual Income Category of the account holder (< $40K, $40K - 60K, $60K - $80K, $80K-$120K, > $120K, Unknown)
- Card_category: Product Variable - Type of Card (Blue, Silver, Gold, Platinum)
- Months_on_book: Period of relationship with bank
- Months_inactive: No. of months inactive in the last 12 months
- Contacts_count: No. of Contacts in the last 12 months
- Credit_limit: Credit Limit on the Credit Card
- Total_revolving_balance: Total Revolving Balance on the Credit Card
- Average_open_to_buy : Open to Buy Credit Line (Average of last 12 months)
- Total_amt_chng: Change in Transaction Amount (Q4 over Q1)
- Total_trans_amt: Total Transaction Amount (Last 12 months)
- Tota_trans_ct: Total Transaction Count (Last 12 months
- Total_ct_chng Q: Change in Transaction Count (Q4 over Q1)
- Average_utilization R: Average Card Utilization Ratio
