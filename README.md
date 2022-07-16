In the project made above the dataset consists of details of all the data of the customers who have an account in the bank. The columns which are present in the dataset are 
 CUSTID: Identification of Credit Card holder 
 ,BALANCE: Balance amount left in customer's account to make purchases
 ,BALANCE_FREQUENCY: How frequently the Balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated)
 ,PURCHASES: Amount of purchases made from account
 ,ONEOFFPURCHASES: Maximum purchase amount done in one-go
 ,INSTALLMENTS_PURCHASES: Amount of purchase done in installment
 ,CASH_ADVANCE: Cash in advance given by the user
 ,PURCHASES_FREQUENCY: How frequently the Purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased)
 ,ONEOFF_PURCHASES_FREQUENCY: How frequently Purchases are happening in one-go (1 = frequently purchased, 0 = not frequently purchased)
 ,PURCHASES_INSTALLMENTS_FREQUENCY: How frequently purchases in installments are being done (1 = frequently done, 0 = not frequently done)
 ,CASH_ADVANCE_FREQUENCY: How frequently the cash in advance being paid
 ,CASH_ADVANCE_TRX: Number of Transactions made with "Cash in Advance"
 ,PURCHASES_TRX: Number of purchase transactions made
 ,CREDIT_LIMIT: Limit of Credit Card for user
 ,PAYMENTS: Amount of Payment done by user,MINIMUM_PAYMENTS: Minimum amount of payments made by user,,PRC_FULL_PAYMENT: Percent of full payment paid by user,TENURE: Tenure of credit card service for user
 The main objective of this project is divide the customers present in bank into atleast 3 categories based on the dataset given above.To perfrom  this  task we first applied the elbow method to find out the optimal number of clusters we took the intial number of clusters to be 8 when applying the k means method. After the completion of the k means method we perfromed Autoencoders and displayed the ouptuts 
 
