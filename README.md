# Retail-Sector-Domain-Analysis
### Business Problem
In Retail Sector, it is potential to unlock insights to win and retain customers, drive business efficiencies and ultimately improve performance in terms of sales and customer interest. Beyond the hype, retail organization are using advance analysis to do everything from understanding their customers to improve forecasting, driving better , faster results. Since the resources that a company has are limited, it is vital to find these customers and target them to win customer loyalty, drive business efficiencies and ultimately improve performance.

### Objective

1. To predict for all customers who shopped at-least once during 12/1/2009 till 11/9/2011.

2. To Predict who will come back to buy any product next month (11/9/2011 – 12/9/2011).

3. To predict likelihood of customers shopping next month

### Variables
The variable names and their descriptions are as follows:

1. InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.

2. StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.

3. Description: Product (item) name. Nominal.

4. Quantity: The quantities of each product (item) per transaction. Numeric.

5. InvoiceDate: Invoice Date and time. Numeric, the day and time when each transaction was generated.

6. UnitPrice: Unit price. Numeric, Product price per unit in sterling.

7. CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.

8. Country: Country name. Nominal, the name of the country where each customer resides.

### Method

1. Customer Clustering
2. RFM Timeseries

### Conclusion
1. We are able to separate customers into different segments, based on the type of products that they buy.

2. Using a Voting Classifier and a combination of multiple machine learning models, such as Random Forest, Gradient Boosted Decision Trees, K-Nearest Neighbours, and Logistic Regression, we are able to predict what type of product a user will buy, with a precision of 94.07%.

3. We can use this information to target selected customers with promotional offers for their desired products, which increases the likelihood of more sales in the future.
