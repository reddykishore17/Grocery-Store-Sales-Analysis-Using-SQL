# Grocery-Store-Analysis-Using-SQL
This project demonstrates how SQL can be used to analyze grocery store sales data and generate business insights. The goal is to transform raw transactional data into actionable intelligence that helps improve decision-making in sales, inventory, customers, suppliers, and employees.
## Project Objectives
The primary goal is to leverage SQL to transform raw sales data into meaningful business intelligence. The key objectives of this project are:
*   **Analyze Sales:** Identify best-selling products and sales patterns.
*   **Understand Customers:** Discover the most valuable customers and their purchasing habits.
*   **Improve Inventory:** Determine popular product categories to optimize stock management.
*   **Optimize Supplier Relationships:** Evaluate which suppliers provide the most profitable and popular products.
*   **Provide Recommendations:** Use data-driven findings to suggest strategies for increasing sales and customer satisfaction.

## Database Schema
The project is built on a relational database designed to track sales, customers, products, suppliers, and employees. The database consists of the following tables:
*   `Supplier`: Contains information about product suppliers.
*   `Categories`: Groups products into categories like "Dairy" or "Bakery."
*   `Employees`: Stores information about employees who process orders.
*   `Customers`: Holds data on all customers.
*   `Products`: Includes details for every product, linking to its category and supplier.
*   `Orders`: Records every order, linking customers and employees.
*   `Order_Details`: Provides a detailed breakdown of each order, including products and quantities.

## Analysis and Queries
The analysis is divided into several sections, each focusing on a different aspect of the business. Here are some of the key questions answered using SQL queries:

### Customer Insights
This section focuses on understanding customer behavior and identifying high-value customers.
*   **Top Customers**: Ranked customers based on their total purchase amount to identify the most valuable ones.
*   **Order Frequency**: Determined which customers placed the highest number of orders.
*   **Customer Inactivity**: Identified customers who have not made a purchase in the last 180 days.

### Product Performance
This part of the analysis looks at which products and categories are driving sales.
*   **Top-Selling Products**: Identified the best-selling products by revenue and sales volume.
*   **Category Performance**: Analyzed the average price and sales of products by category.
*   **Supplier-Category Analysis**: Examined how product sales vary by category and supplier.

### Sales and Order Trends
This section analyzes overall sales patterns to understand business cycles.
*   **Monthly Trends**: Tracked monthly order volume and revenue to identify seasonal patterns.
*   **Weekday vs. Weekend**: Compared order patterns between weekdays and weekends.
*   **Peak Order Dates**: Found the dates with the highest number of orders placed.

### Supplier Contribution
This analysis evaluates the performance and importance of different suppliers.
*   **Top Suppliers**: Identified suppliers who provide the most products and contribute the most to total revenue.
*   **Category-Specific Suppliers**: Determined which suppliers are the top revenue contributors for specific product categories.

### Employee Performance
This section measures the efficiency and contribution of employees in processing orders.
*   **Order Processing**: Identified which employees handled the most orders.
*   **Sales Value**: Calculated the total sales value processed by each employee.
*   **Average Order Value**: Determined the average order value handled per employee.

## Key Insights and Recommendations
The analysis yielded several actionable insights that can directly impact business strategy:
*   **Focus on High-Value Customers**: A small group of customers accounts for a majority of the store's revenue. The business should create loyalty programs and personalized marketing to retain these customers.
*   **Promote High-Performing Categories**: "Personal Care" and "Grains & Cereals" are the top revenue-driving categories. These items should always be in stock and featured in promotions.
*   **Strengthen and Diversify Supplier Relationships**: The business relies heavily on a single supplier, "Aarya," for several key categories. While strengthening this partnership is important, the store should also find alternative suppliers to reduce risk.

## Challenges Faced
This project involved a few technical challenges that were successfully overcome:
*   **Designing an Effective Database Schema**: Creating a well-structured schema with proper primary and foreign keys was essential for data integrity and accurate analysis.
*   **Writing Complex SQL Queries**: Answering detailed business questions required writing complex queries with multiple joins across tables like `products`, `categories`, `supplier`, and `order_details`.

## Conclusion
This project successfully demonstrated how SQL can be used to extract actionable insights from raw sales data. The findings from this analysis empower the grocery store to make data-driven decisions regarding inventory management, targeted marketing, and strategic supplier relationships, ultimately leading to improved business performance.
