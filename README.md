# Hadoop-Reducer-Join
Basic join operation in standard Java Map Reduce. Reducer handles the join after mapper outputs values with same keys. This is suitable for joining two similarly large datasets. 
There are two data sets:
1. cust - customer data
2. txns - transactions
The objective here is to join the two files such that the output contains the name of each customer along with the number of transactions and total transaction value. 
