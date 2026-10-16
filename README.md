# Assignment - 4 - Power-BI
                                                  ## DAX & DATA VISUALIZATION - POWER BI
**Calculated Columns:**

● Create a Calculated Column for 'Category Type': Add a calculated column in the
Order Details table that combines the 'Category' and 'Sub-Category' columns into a
single 'Category Type' column.

          On "New Column" Created "Category Type" Column and Combined Category + Sub-category

● Calculate Revenue per Order in Order Details Table: Create a calculated column in
the Order Details table to compute the revenue (Amount * Quantity) per order.

          On "New Column" Created "Revenue per Order" Column and multiplied - Amount * Quantity 

● Create a Calculated Column to Categorize Sales: Add a calculated column named
‘Sales Category’ in the Order Details table that categorizes each order as 'Above
Average' or 'Below Average' based on the Amount value.

          On "New Column" Created "Sales Catogory" Column and used "IF" and "Average" to Categorize as Above and Below


**Calculated Measures:**

● Calculate Order Count: Define a measure to count the total number of orders in the
Order Details table.

          On "New Measure" Created "Order COunt" Column and used "DISTINCTCOUNT" to count the total number of orders

● Calculate Average Profit in Delhi: Create a measure to calculate the average profit for
orders placed in Delhi.

          On "New Measure" Created "Average profit in Delhi" Column and Calculated Average profit based on City - Delhi


● Calculate Year-to-Date (YTD) Sales: Define a measure to calculate the total sales
amount accumulated from the earliest order date up to each order date.

          On "New Measure" Created "YTD Sales" Column and Calculated total sales amount.



**Data Visualization:**

● Sales Target Achievement by Category: Compare actual sales with sales targets by category using a clustered column chart.

         The chart compares actual sales with sales targets for Clothing, Electronics, and Furniture.

● Max Profit Margin by Sub-Category: Analyze the maximum profit margin for each sub-category of products using a donut chart.

         The donut chart displays the maximum profit margin for each product sub-category.

● Monthly Sales Trend: Show the trend of monthly sales over time using a line chart.

         The line chart shows how sales increase or decrease month by month.

● Comparison of Profit and Quantity by Sub-Category: Compare the relationship between profit and quantity sold for different sub-categories using a scatter chart.

         The scatter chart shows the relationship between profit earned and quantity sold for each sub-category.

● Comparison of Total Sales Amount and Target: Create cards to succinctly display the total sales amount alongside the sales target for quick comparison and analysis. Also, create a multi-row card to display the minimum target for each segment.

         The cards display total sales and sales targets, while the multi-row card shows the minimum target for each segment.

● Sales Performance Matrix: Build a matrix view to analyze how actual sales compare to sales targets across different categories and months.

         The matrix compares actual sales and sales targets across categories and months.

● Geographic Sales Analysis: Visualize total sales on a map by city to identify regional sales patterns.

         The map displays total sales by city and helps identify regions with higher sales.

● Sales Distribution by Sub-Category: Represent the sales distribution across different sub-categories using a treemap.

         The treemap uses different-sized rectangles to show each sub-category's contribution to total sales.

Order Count Analysis by State: Create a funnel chart to visualize the distribution of order counts across different states.

         The funnel chart compares order counts across different states.

