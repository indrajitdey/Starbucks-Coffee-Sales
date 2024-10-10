# Starbucks Coffee Shop Sales Dashboard
This project involves creating an interactive Excel dashboard to analyze the sales performance of a coffee shop. The dashboard provides insights into sales trends, product performance, customer preferences, and other key metrics to help the business make data-driven decisions.

# Problem Statement
Managing sales efficiently is crucial for any business, especially in a competitive space like the coffee shop industry. Identifying trends, peak sales times, and top-performing products can enhance operations, optimize inventory, and increase profits. This dashboard aims to provide an easy-to-understand visualization of the shop's sales data, helping to identify areas for growth and improvement.

# Dashboard
![ScreenShot](https://github.com/user-attachments/assets/f0f054d1-85c6-4798-8a00-0899ea0f6a2a)

# Data Overview
The dataset consists of daily sales records from the coffee shop with the following columns:
- transaction_id: Unique identifier for each transaction.
- transaction_date: Date when the transaction occurred.
- transaction_time: Time of the transaction.
- transaction_qty: Number of units sold in the transaction.
- store_id: Unique identifier for each store location.
- store_location: Name or description of the store location.
- product_id: Unique identifier for the product sold.
- unit_price: Price per unit of the product sold.
- product_category: Category the product belongs to (e.g., beverages, bakery items).
- product_type: Type of product (e.g., coffee, sandwich).
- product_detail: Detailed description or name of the product.

# Approach
- Data Cleaning: The dataset was cleaned to remove any inconsistencies, such as missing data and duplicate records.
- Data Aggregation: Sales data was aggregated on different levels (daily, weekly, monthly) to spot trends and patterns.
- Visualization: The data was visualized using pivot tables, pivot charts, and other visual tools in Excel, focusing on key performance metrics like:
- Total Sales per Day/Week/Month
- Product Category Performance
- Top 5 Products by Sales
- Sales Trends Over Time
- Interactivity: Filters and slicers were added to the dashboard, allowing users to interact with the data and generate custom reports based on specific time periods or product categories.

# Results
- The dashboard provides actionable insights into:
- Best-Selling Products: A clear view of top-performing items, helping the business optimize inventory.
- Sales Peaks and Trends: Identifying the best and worst performing time periods, which can help optimize staffing and promotions.
- Category Performance: Visual breakdown of which categories (e.g., beverages, food items) are contributing the most to revenue.

# Outputs
- The dashboard includes the following key charts:
- Quantity Orders Based on Hours: Shows the distribution of orders throughout the day, highlighting peak times.
- Categories % Distribution Based on Sales: Visualizes the percentage contribution of different product categories (e.g., beverages, bakery items) to overall sales.
- Order Size % Distribution: Analyzes the size of customer orders and their frequency.
- Footfall and Sales Over Various Store Locations: Compares the number of customers and total sales across different store locations, offering insights into location-based performance.
- Top 5 Products Based on Sales: Highlights the best-selling products, helping to focus inventory and promotions.
- Orders on Weekdays: Shows the distribution of orders throughout the week, helping to identify the busiest and slowest days.

# Conclusion
This dashboard helps the coffee shop management quickly assess their sales performance and make informed decisions. It offers valuable insights into product trends, customer preferences, and revenue-driving time periods. The project can be extended by incorporating more advanced analytical models like time series forecasting to predict future sales or clustering techniques for customer segmentation.
