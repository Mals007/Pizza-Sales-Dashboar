# Pizza-Sales-Dashboard
Pizza Sales Power Bi Dashboard

Dashoard link: https://app.powerbi.com/links/pwzSHmJpd4?ctid=7e2137dd-6ef9-46eb-974e-5086fd7cdd20&pbi_source=linkShare&bookmarkGuid=2043c58d-0082-4bd3-942c-2a3df0729069

Project Objective
To  Develop a comprehensive pizza sales dashboard that integrates data to provide actionable insights into sales performance, customer behavior, and keep track of best seller and the worst selling pizza. The dashboard aims to help stakeholders monitor sales trends, identify top-selling products, optimize inventory, and enhance marketing strategies to drive revenue growth and improve customer satisfaction.


Import data to Power BI 
1. Prepare csv file 
2. Import CSV file to Microsoft SQL
3. Perform Data calculation to verify the numbers in SQL and Power BI
4. Data cleaning 
5. Data Processing 

DAX Queries
1. Total Revenue
Total_Revenue = sum(pizza_sales[total_price])
2. Total Orders
Total_Order = DISTINCTCOUNT(pizza_sales[order_id]) 
3. Total Pizza Sold
Total_Pizza_Sold = sum(pizza_sales[quantity])
4. Average Pizza Per Order 
Average Pizza Per Order = [Total_Pizza_Sold]/[Total_Order]
5. Average Order Value 
Average_Order_Value = DIVIDE([Total_Revenue],[Total_Order])

Project Insight
Overview (Jan 2015-Dec 2015)

•	Total Revenue: 817.86 K
•	Total Order: 21,350
•	Total Pizza sold: 49,574
•	Average Pizza per order: 2.32
•	Average order value: 38.31
•	The classic category pizza were sold the highest and the large size pizza was ordered most by the customer.
•	The weekly trend for order were highest on Friday and Saturday.
•	The Thai Chicken pizza earned the highest revenue and the classic deluxe pizza was most sold by the pizza hub and ordered by the customer
•	The Brie Care pizza was the least ordered and lowest revenue contributing pizza on the menu.
