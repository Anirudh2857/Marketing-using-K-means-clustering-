This project aims to divide bank customers into at least three categories based on their credit card usage using K means clustering. The dataset used in this project consists of various features of the customers, such as balance, purchase frequency, cash advance frequency, credit limit, etc.

**Dataset**

The dataset consists of the following columns:

CUSTID: Identification of Credit Card holder

BALANCE: Balance amount left in customer's account to make purchases

BALANCE_FREQUENCY: How frequently the balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated)

PURCHASES: Amount of purchases made from account

ONEOFFPURCHASES: Maximum purchase amount done in one-go

INSTALLMENTS_PURCHASES: Amount of purchase done in installment

CASH_ADVANCE: Cash in advance given by the user

PURCHASES_FREQUENCY: How frequently the purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased)

ONEOFF_PURCHASES_FREQUENCY: How frequently purchases are happening in one-go (1 = frequently purchased, 0 = not frequently purchased)

PURCHASES_INSTALLMENTS_FREQUENCY: How frequently purchases in installments are being done (1 = frequently done, 0 = not frequently done)

CASH_ADVANCE_FREQUENCY: How frequently the cash in advance is being paid

CASH_ADVANCE_TRX: Number of Transactions made with "Cash in Advance"

PURCHASES_TRX: Number of purchase transactions made

CREDIT_LIMIT: Limit of Credit Card for user

PAYMENTS: Amount of Payment done by user

MINIMUM_PAYMENTS: Minimum amount of payments made by user

PRC_FULL_PAYMENT: Percent of full payment paid by user

TENURE: Tenure of credit card service for user

**Methodology**

To perform the task of dividing the customers into different categories, we first applied the elbow method to determine the optimal number of clusters. After analysis, we decided to proceed with eight initial clusters in the K means method.

Once the K means clustering was completed, we performed Autoencoders to further analyze the outputs.

**Conclusion**

Through this project, we successfully divided bank customers into different categories based on their credit card usage, which could be helpful for marketing and improving customer experience.
