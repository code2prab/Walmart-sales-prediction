# Walmart-sales-prediction
# 1. Statement of Research:
For a big sales company it becomes very difficult to fulfil demand of customers
when the demand beforehand is unknown. As a result, the aim is to predict the 
weekly sales of WALMART. Since sales depend on several factors, the strong 
aim is to determine the way these factors influence the sales of products. This 
is done to study the market potential and customer power to purchase the 
products. Thus, this will help in maintaining proper inventory with good 
supplies to all the warehouses.
# 2. Description of Dataset

This is the historical data that covers sales from 2010-02-05 to 2012-11-01, in the file 
WalmartStoresales. Within this file you will find the following fields:<br />
 --> Store - the store number<br />
 --> Date - the week of sales<br />
 --> Weekly_Sales - sales for the given store<br />
 -->Holiday_Flag - whether the week is a special holiday week 1 – Holiday week 0 – Nonholiday week<br />
 --> Temperature - Temperature on the day of sale<br />
 --> Fuel_Price - Cost of fuel in the region<br />
 --> CPI – Prevailing consumer price index<br />
 --> Unemployment - Prevailing unemployment rate<br />
# Holiday Events
Super Bowl: 12-Feb-10, 11-Feb-11, 10-Feb-12, 8-Feb-13\
Labour Day: 10-Sep-10, 9-Sep-11, 7-Sep-12, 6-Sep-13\
Thanksgiving: 26-Nov-10, 25-Nov-11, 23-Nov-12, 29-Nov-13\
Christmas: 31-Dec-10, 30-Dec-11, 28-Dec-12, 27-Dec-13
The dataset consists of:
• 6435 rows and 8 columns
• There are distinct 45 Walmart stores located in different regions are available.
• There is holiday flag column that takes Boolean yes or no.
• This takes Unemployment rate as a feature.
• Temperature for the day is also an input feature.
• Fuel price is another important feature considered.
• Consumer price index is also one feature.
• We predict weekly sales from the provided above features. We see if all or some 
input variable columns are essential for predicting weekly sales OR taking 
unnecessary column is adding variability in the predicted output
