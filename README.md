# Ecommerce-Sales-Data-Analysis
1. Project Overview
This project is a comprehensive Ecommerce Sales Performance Dashboard built in Tableau. Its primary purpose is to visualize and analyze key business metrics to derive actionable insights. The dashboard provides a holistic view of sales and profit trends, customer behavior, operational efficiency, and product performance. It allows stakeholders to monitor the health of the business, identify strengths and weaknesses, and make data-driven decisions.
Primary Business Questions Answered:
•	What are the total sales and profit figures?
•	How does current performance compare to the previous month?
•	Who are the top-performing sales personnel?
•	What is the rate of returned items, and which regions have the most returns?
•	How do discounts affect profitability?
•	What are the most profitable product categories?
•	How efficient is the order processing and shipping pipeline?
2. KPI Description (Top Summary Card)
The top of the dashboard features key performance indicators (KPIs) that provide a snapshot of business health for a selected period (in this case, December 2023).
•	Order Month: Dec | Order Year: 2023 | Month Type: Current Month
•	Total Sales: $2,297,739 - The total revenue generated from all orders.
•	Total Profit: $286,755 - The total earnings after costs.
•	Total Order: 37,873 - The total number of orders placed.
•	Total Quantity Sold: 5,009 - The total number of individual items sold.
•	Profit Margin: 12.48% - (Total Profit / Total Sales) * 100. This is a crucial metric showing how much profit is made per dollar of sales.
•	Returned %: 5.91% - (Returned Orders / Total Orders) * 100. This indicates the rate of product returns, which impacts profitability and customer satisfaction.
•	Top Profitable Sub-Category: Binders - The product sub-category with the highest profit contribution.
3. Chart & Visualization Description
1. Sales Over Month By Category (Line Chart)
•	Description: A multi-line chart tracking Sales (Y-axis) over the Months of the year (X-axis). Each line represents a different product Category (Furniture, Office Supplies, Technology), shown in different colors.
•	Purpose: To identify sales trends and seasonality throughout the year and compare performance across different product categories.
2. Current vs Previous Month Profits (Bar Chart - Time Series)
•	Description: A dual-axis chart likely showing Profit (Bar chart, primary axis) over the Day of Order Date (X-axis) for both the current and previous month (e.g., Dec vs Nov).
•	Purpose: To perform a day-by-day comparison of profitability between two consecutive months, helping to identify specific days of improvement or decline.
3. Profit and Sales By Person (Bar Chart)
•	Description: Horizontal bar charts for four salespersons (Anna Andreadi, Cassandra Bra.., Chuck Magee, Kelly Williams). Each person has two bars: one for their Total Sales and one for their Total Profit.
•	Purpose: To evaluate the performance of individual sales personnel. It helps identify top revenue generators and, more importantly, those who contribute the most to profit (e.g., Kelly has high sales but lower profit compared to Anna).
4. Returned Status & Returned By Region (Pie Chart & Bar Chart)
•	Returned Status (Pie Chart): Shows the proportion of orders that were Not Returned (91.95%, 9,252 orders) vs. Returned (8.05%, 810 orders).
•	Returned By Region (Bar Chart): A bar chart showing the Count of Returned items per Region (West, East, Central, South).
•	Purpose: To analyze product return rates. The pie chart gives an overall return rate, while the bar chart pinpoints which geographic regions have the highest volume of returns, which could indicate issues with shipping, product quality, or regional preferences.
5. Profit and Discount (Scatter Plot)
•	Description: A scatter plot with Discount (X-axis) against Profit (Y-axis). Each point represents an order or a group of orders.
•	Purpose: To analyze the correlation between discount levels and profitability. The ideal insight is to find the discount "sweet spot" that drives sales without severely eroding profits.
6. Order Processing Time (Histogram)
•	Description: A histogram showing the Count of Orders (Y-axis) by the number of days it takes to process them (Order Processing Time on X-axis). The chart shows most orders (2,734) are processed in 1 day.
•	Purpose: To measure operational efficiency. A concentration of orders on the left (low processing time) indicates a smooth, efficient fulfillment process.
7. Ship Mode By Orders (Bar Chart)
•	Description: A horizontal bar chart showing the Count of Orders for each Ship Mode (Standard Class, Second Class, First Class, Same Day). Standard Class is the most used (6,009 orders).
•	Purpose: To understand customer shipping preferences and the cost structure of the logistics operation.
8. Most Profitable Sub-Category (Horizontal Bar Chart)
•	Description: A horizontal bar chart showing the Profit Margin for various Sub-Categories. Copiers, Envelopes, Paper, and Fasteners are shown with high profit margins (e.g., 44.42% for Paper).
•	Purpose: To identify which specific products are the most profitable. This helps in inventory planning, marketing focus, and strategic decision-making.
4. Filters Description
The dashboard includes interactive filters, allowing users to dynamically change the view:
•	Month: Allows selection of a specific month (e.g., "All" or "Dec").
•	Category: Filter by Furniture, Office Supplies, or Technology.
•	Year: Filter by a specific year (e.g., "All" or "2023").
5. Conclusion & Business Insights
This dashboard effectively tells the story of the e-commerce business's performance in December 2023.
Key Conclusions:
1.	Strong Financial Performance: The company achieved significant sales (~$2.3M) with a healthy profit margin of 12.48%.
2.	Top Performers: Anna Andreadi is the top contributor to both sales and profit, making her the most valuable salesperson. Kelly Williams generates high sales but with a lower profit margin, suggesting she may be offering higher discounts.
3.	Operational Efficiency: The order processing is highly efficient, with the vast majority of orders being processed within 1-2 days. Standard Class shipping is the dominant mode.
4.	Returns Management: The overall return rate of 5.91% is within an acceptable range for e-commerce. However, the West region has the highest number of returns, which should be investigated further to address potential causes.
5.	Product Strategy: Binders are the top profitable sub-category by total profit, while products like Paper and Envelopes have the highest profit margins. The marketing and inventory strategy should focus on these high-margin items.
6.	Discount Strategy: The scatter plot showing Profit vs. Discount is critical. It likely reveals that high discounts (e.g., above 20-30%) lead to losses or very low profits. The strategy should be to optimize discounts to maximize volume without sacrificing profitability.
In summary, the business is healthy and efficient. The immediate actions would be to investigate the reason for high returns in the West region, analyze Kelly Williams's discounting strategy, and promote high-margin products like Paper and Envelopes more aggressively

