# Online-Retail-Analysis
Data Set Information:

This Online Retail II data set contains all the transactions occurring for a UK-based and registered, non-store online retail between 01/12/2009 and 09/12/2011.The company mainly sells unique all-occasion gift-ware. Many customers of the company are wholesalers.


Attribute Information:

InvoiceNo: Invoice number. Nominal. A 6-digit integral number uniquely assigned to each transaction. If this code starts with the letter 'c', it indicates a cancellation.
StockCode: Product (item) code. Nominal. A 5-digit integral number uniquely assigned to each distinct product.
Description: Product (item) name. Nominal.
Quantity: The quantities of each product (item) per transaction. Numeric.
InvoiceDate: Invice date and time. Numeric. The day and time when a transaction was generated.
UnitPrice: Unit price. Numeric. Product price per unit in sterling (Â£).
CustomerID: Customer number. Nominal. A 5-digit integral number uniquely assigned to each customer.
Country: Country name. Nominal. The name of the country where a customer resides.

Data Cleaning:

1. During data cleaning, there are quite a number of stockcodes with multiple descriptions, that requires us to perform data patching.
2. Convert date column from string to datetime
3. Drop row that for country row that indicate ‘Unspecified'
4. Set Customer ID to integer


Data Analyzing Approach
My approach on this analysis are mainly around looking the sales performance of the company and product.
By analyzing the both online and retail sales trend, allows relevant department to study,plan and bring in suitable products for marketing.

