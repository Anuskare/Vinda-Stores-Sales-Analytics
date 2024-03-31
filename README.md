# Vinda-Stores-Sales-Analytics
##Objective
Draw insights and prepared a dashboard to answer sales related question in one go using Excel
##Problem Statement
Vrinda Store wants to create an annual sales report for 2022.
So that, Campany can understand their customers and grow more sales in 2023.
------------------------------------------------
Questions to be answered:
------------------------------------------------
1. Compare the sales and orders visually
2. Which month got the highest sales and orders?
3. Who purchased more by gender in 2022?
4. What are different order status in 2022?
5. List top 5 states contributing to the sales?
6. Relation between age and gender based on number of orders.
7. Which channel is contributing to maximum sales?
8. Which is the Highest selling category?
-------------------------------------------------------
First We need to find if this data is capable of solving our business problem value of data and prepare data for processing
-----------------------------------------------
Data cleaning 
------------------------------------------------
check for null values, otliera
find and replace M with Men
Qty
chk app datatypes
check mistakes at highlevel
duplicate values
-----------------------------------------------
Data Processing
----------------------------------------
Adding new column for better n ease of analysis
1. Age group column to create age buckets
----------------------------------------------
Data Analysis
-----------------------------------------------------
Q. 1. Compare the sales and orders visually
Q. 2. Which month got the highest sales and orders?

Created a pivot table
Amount and orders in values
months in row
inserted a bar chart
change y axis values to millions for user readiness

Q. 3. Who purchased more by gender in 2022?

pivotchart --men vs women --pie-chart with percentages

Q 4. What are different order status in 2022?

pivot chart --pie chart

Q 5. List top 5 states contributing to the sales?

Pivot chart-top 10 status dynamic for each month--horizontal bar chart


After the report is made with all charts, Added slicers 
to combine all the charts and display values according to criteria
Slicer option comes only for pivot charts not in normal charts

--------------------------------------------------------
Insights Drawn from data
______________________________________________________
March more sales 
Women adult more sales
more sales from amazon channel
more sales from maharastra 
-------------------------------------------------------------
Suggested Insights
---------------------------------------------------------------
Women are more likely to buy compared to men (~65%)
Maharashtra, Karnataka and UP are the top 3 states (~35%)
Adult age group(30-49 yrs) is max contributing(~50%)
Amazon, FlipKart and Myntra channels are max contributing (~80%)
--------------------------------------------------------
Final Conclusion to improve Vrinda store sales:
-------------------------------------------------------------
Target customers: women of age group (30-49 years)
Target states : Maharashtra, Karnataka and Uttar Pradesh
Target channels: Amzon, Flipkart and Myntra
Focus on above customers by advertisements/coupons/discounts
