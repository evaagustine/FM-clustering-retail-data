# FM-clustering-retail-data
This repository contains FM (Frequency and Monitory) customer segmentation using K-Means with retail dataset from Kaggle

# Dataset
The dataset could access here https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci/code. It is containing retail transaction data that has 7 columns, they are InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID.
In this dataset, the data is limited only in December 2009 due to alignment with previous analysis (price elasticity analysis) and due to limited of resources

# Results
**Cluster Description**
* Cluster 0 are interpeted as Low Cluster. There are 793 customers that has minimum frequency (only 1-2 transactions per customer) and monetary between 10 - 4380
* Cluster 1 are interpeted as High Cluster. There are only 6 customers that has high frequency (9-15 transactions per customer) and monetary between 5749 - 20427
* Cluster 2 are interpeted as Mid Cluster. There are 99 customers that has average frequency (2-18 transactions per customer) and monetary between 46.67 - 8367

**Information gained from the result**
* Majority of the customers are in Low cluster, means low frequency and total amount spending
* There only has 6 customers in High cluster, company should attract more high cluster if they want to increase our overall GMV
