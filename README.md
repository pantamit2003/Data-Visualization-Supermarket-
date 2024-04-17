# About
This project focuses on analyzing sales data for office supplies and technology products in the United States. The dataset includes information such as the order ID, order priority, discount, unit price, shipping cost, customer details (ID, name, segment), product details (category, sub-category, container, name, base margin), region, state or province, city, postal code, order date, ship date, profit, and quantity ordered.
The analysis aims to uncover insights into the sales trends, customer segments, and product performance. By examining this dataset, we can identify the best-selling products, understand customer preferences, and optimize pricing and shipping strategies. This information can help businesses in the office supplies and technology sectors enhance their sales and marketing strategies to drive profitability and customer satisfaction.


# Purpose
This analysis delves into various aspects of the business, including profit based on product category to guide strategic product focus and resource allocation. Understanding profit at the unit level aids in pricing strategies and identifying high-performing products. Region-wise profit analysis helps optimize sales strategies and resource allocation across different geographic areas. Sales distribution by product container informs packaging decisions and enhances customer experience. Total sales by product category offers insights into market trends and guides sales strategies to align with customer demand. Together, these analyses empower informed decision-making in product management, pricing, marketing, sales, and regional operations, contributing to overall business growth and success.
| Column Name             | Description                                                   | Data Type  |
|-------------------------|---------------------------------------------------------------|------------|
| Row ID                  | Unique identifier for each row.                                | INT        |
| Order Priority          | Priority level of each order.                                  | VARCHAR(20)|
| Discount                | Discount applied to orders.                                    | FLOAT(2,2) |
| Unit Price              | Price per unit of the product.                                 | FLOAT(2,2) |
| Shipping Cost           | Cost of shipping each order.                                   | FLOAT(2,2) |
| Customer ID             | Unique identifier for customers.                                | INT        |
| Customer Name           | Name of the customer.                                          | VARCHAR(100)|
| Ship Mode               | Shipping method used.                                          | VARCHAR(20)|
| Customer Segment        | Classification of customers.                                   | VARCHAR(30)|
| Product Category        | Broad category of products.                                    | VARCHAR(30)|
| Product Sub-Category    | Detailed category of products.                                 | VARCHAR(30)|
| Product Container       | Type of container for products.                                | VARCHAR(30)|
| Product Name            | Description of the product.                                     | VARCHAR(100)|
| Product Base Margin     | Base profit margin for products.                               | FLOAT(2,2) |
| Region                  | Geographic region.                                             | VARCHAR(30)|
| State or Province       | State or province.                                             | VARCHAR(30)|
| City                    | City where orders are shipped.                                  | VARCHAR(50)|
| Postal Code             | Postal code of shipping address.                                | VARCHAR(20)|
| Order Date              | Date of order placement.                                       | DATE       |
| Ship Date               | Date of order shipment.                                        | DATE       |
| Profit                  | Profit generated from orders.                                   | FLOAT(2,2) |
| Quantity ordered new    | Quantity of units ordered.                                     | INT        |
| Sales                   | Total sales revenue.                                           | FLOAT(2,2) |
| Order ID                | Unique identifier for each order.                               | INT        |

# Approach Used
1.	Data Preparation: Used Pandas for cleaning and preparing the movie dataset, handling missing values, and formatting data for analysis.
2.	Numerical Analysis: Leveraged NumPy for numerical operations like calculating statistics and aggregating data to uncover insights.
3.	Visualization: Created visualizations using Matplotlib to visualize trends, distributions, and relationships in the movie data.
4.	Feature Engineering: Utilized Pandas to transform data, including splitting the release date into month, year, and country for better analysis.
5.	Insights Generation: Combined Pandas, NumPy, and Matplotlib to derive actionable insights and present findings effectively.
# Question
1.	What types of technology products are contributing most to maximum profits?
2.	How does the unit price range of 0-1000 impact profit compared to the ranges of 3000-4000 and 7000?
3.	Why is the central region experiencing higher sales compared to the south region?
4.	What strategies could be implemented to improve sales in the south region based on these findings?
5.	What factors contribute to the central region generating maximum profits?
6.	How can the profitability of the south region be increased?
7.	What makes the "Small box" product have the highest sales distribution at 34.8%?
8.	How does the sales distribution of "Wrap bag" compare to other product types, and why is it at 2%?
9.	What insights can be gained from the sales distribution percentages across different product types?
10.	Are there any specific product categories driving the high sales distribution in the central region?
11.	How can marketing strategies be adjusted to improve sales in the south region?
12.	What recommendations can be made based on the sales and profit trends observed in the analysis?




