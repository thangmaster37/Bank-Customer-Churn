<h1 align="center">
  DATA SCIENCE PROJECT: BANK CUSTOMER CHURN
</h1>


## 🚀 1.INTRODUCTION
Customer Churn prediction means knowing which customers are likely to leave or unsubscribe from your service. For many companies, this is an important prediction. Some studies confirmed that acquiring new customers can cost five times more than satisfying and retaining existing customers. Once you’ve identified customers at risk of churn, you need to know exactly what marketing efforts you should make with each customer to maximize their likelihood of staying.As a matter of fact, there are a lot of benefits that encourage the tracking of the customer churn rate, for example:
- Marketing costs to acquire new customers are high. Therefore, it is important to retain customers so that the investment is not wasted
- It has a direct impact on the ability to expand the company
- Improve the customer experience
- Increase profits
- Etc

Customers have different behaviors and preferences, and reasons for cancelling their subscriptions. Therefore, it is important to actively communicate with each of them to keep them on your customer list. You need to know which marketing activities are most effective for individual customers and when they are most effective.

In this project our goal is to predict the probability of a customer is likely to churn using machine learning techniques.

## 🧐 2.ABOUT DATA 
This data set contains details of a bank's customers and the target variable is a binary variable reflecting the fact whether the customer left the bank (closed his account) or he continues to be a customer.

- **RowNumber**: Row Numbers from 1 to 10000
- **CustomerId**: Unique Ids for bank customer identification
- **Surname**: Customer's last name
- **CreditScore**: Credit score of the customer
- **Geography**: The country from which the customer belongs
- **Gender**: Male or Female
- **Age**: Age of the customer
- **Tenure**: Number of years for which the customer has been with the bank
- **Balance**: Bank balance of the customer
- **NumOfProducts**: Number of bank products the customer is utilising
- **HasCrCard**: Binary Flag for whether the customer holds a credit card with the bank or not
- **IsActiveMember**: Binary Flag for whether the customer is an active member with the bank or not
- **EstimatedSalary**: Estimated salary of the customer in Dollars
- **Exited**: Binary flag 1 if the customer closed account with bank and 0 if the customer is retained

## 🛠️ 3.INSTALLATION LIBRARIES

|ID  |     Command Prompt            |     Jupyter Notebook                        |
|----|-------------------------------|---------------------------------------------|
|1   |pip install numpy              |conda install numpy                          |
|2   |pip install pandas             |conda install pandas                         |
|3   |pip install matplotlib         |conda install -c conda-forge matplotlib      |
|4   |pip install seaborn            |conda install -c anaconda seaborn            |
|5   |pip install plotly             |conda install -c plotly plotly               |
|6   |pip install -U scikit-learn    |conda install -c conda-forge scikit-learn    |
|7   |pip install -U imbalanced-learn|conda install -c conda-forge imbalanced-learn|
|8   |pip install tk                 |conda install -c anaconda tk                 |
|9   |pip install joblib             |conda install -c anaconda joblib             |
