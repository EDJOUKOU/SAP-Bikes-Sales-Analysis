# SAP-Bikes-Sales-Analysis

![icons8-bike-50](https://github.com/user-attachments/assets/43361319-f920-437a-9912-c90b718dd4e9)

## Project Overview
This project aims to assess the sales performance of a bike shop. The insights gained will assist the owner in refining sales and marketing strategies, while optimizing overall business practices to boost profitability.

## Data Source
The data used for this study was retrieved from the Kaggle website and is available for download in this repository.

## Tools
- MySQL Workbench 8.0 to create an instance of MySQL an connect it to python
- Jupyter notebook IDE for data analysis
- Power BI for data visualization

## Exoloratory Data Analysis
The following business questions were investigated as part of EDA:
- **Products Analysis**
- Q1: Find the total number of products for each product category
- Q2: List the top 5 most expensive products
- Q3: Find all products that belong to the 'Mountain Bike' category
- Q4: List the total sales amount (gross) for each product category
- Q5: List the top 5 suppliers by total product sales.
- Q6: Find the total number of products created by each employee
- Q7: List the employees who have changed product details the most

- **Sales Orders Items Analysis**
- Q8: Calculate the total gross amount for each sales order.
- Q9: Trend in sales over different fiscal year periods
- Q10: Which products contribute the most to revenue when the billing status is 'Complete'
- Q11: Find the sales order items for a specific product ID.

- **Sales Orders Analysis**
- Q12: How does revenue vary over different fiscal year periods for orders with a billing status of 'Complete'
- Q13: Find the top-selling product within each category and its total sales amount.
- Q14: Calculate the total gross amount for each sales organization.
- Q15: Find the top 5 sales orders by net amount.
- Q16: How many sales orders were created in the year 2018?

- **Employees Analysis**
- Q17: Find the number of employees for each sex
- Q18: List the employees who have 'W' in their first name

- **Addresses Analysis**
- Q19: Count the number of addresses in each country.
- Q20: Find the number of business partners in each region.

## Data Analysiss
it has been performed on jupyter notebook, please check the uploaded SAP Bikes Sales 

## Results/ Findings
1. Products in categories RC and BX lead in gross sales revenue, generating $3,690,100 and $3,076,279 respectively.  
2. Supplier ID 100000004 has the highest sales revenue, amounting to $1,028,310.  
3. Product RO-1001 contributes the most to overall revenue.  
4. Product CB-1161 has the largest number of orders.  
5. The EMEA sales organization is the top performer, with total sales revenue of $9,031,740.  
6. Sales order 500000244 holds the highest revenue among all orders.

## Recommendations
Here are a few recommendations for optimizing this business based on the sales data:

1. Focus on Top Products (RC, BX, RO-1001)  
   Invest more in marketing and promoting the best-performing products (RC, BX, and RO-1001). These products already contribute significantly to revenue, and scaling their visibility and availability could further boost sales.

2. Strengthen Supplier Relationships (ID 100000004)
   Since Supplier ID 100000004 generates the highest sales revenue, fostering a closer partnership could result in better pricing, exclusive deals, or priority access to products, enhancing profitability.

3. Optimize High-Order Products (CB-1161) 
   As Product CB-1161 has the highest number of orders, ensure efficient stock management and fulfillment processes to avoid backorders and capitalize on its popularity.

4. Leverage EMEA's Performance  
   The EMEA sales organization is leading in revenue. Expanding its operations or replicating its successful strategies in other regions may drive further growth.

5. Analyze High-Value Sales Orders
   Investigate sales order 500000244 and similar high-value orders to identify patterns, customer preferences, or opportunities for upselling and cross-selling.
