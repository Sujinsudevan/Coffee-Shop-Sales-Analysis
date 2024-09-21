#  Coffee Shop Sales Data Analysis

##  Project Overview

This project focuses on analyzing sales data from a coffee shop chain to uncover insights that can enhance business performance. By cleaning and processing the data, the objective is to derive actionable insights into sales trends, product performance, store efficiency, and customer preferences.

##  Dataset Overview

The dataset contains sales data with the following features:

- **Transaction_id**: Unique sequential ID representing an individual transaction.
- **Transaction_date**: Date of the transaction (MM/DD/YY).
- **Transaction_time**: Time of the transaction (HH:MM:SS).
- **Transaction_qty**: Quantity of items sold.
- **Store_id**: Unique ID of the coffee shop.
- **Store_location**: The location of the coffee shop.
- **Product_id**: Unique ID of the product sold.
- **Unit_price**: Retail price of the product sold.
- **Product_category**: Description of the product category.
- **Product_type**: Description of the product type.
- **Product_detail**: Detailed description of the product sold.

### Cleaning and Preprocessing

The following operations were performed to clean and preprocess the dataset:

- Created a new column `Size` using conditional logic based on the `Product_detail` column.
- Adjusted the positions of columns for better readability.
- Created a `Total Bill` column by multiplying `Unit_price` and `Transaction_qty`.
- Extracted time features such as `Month`, `Month_name`, `Hour`, and `Weekday` from the `Transaction_date` column.
- Formatted and saved the data for further analysis and visualization.

##  Analysis

### 1. Sales by Day of the Week and Hour of the Day

Analyzed the variation in sales across different days of the week and times of the day to identify peak sales periods. This helps in understanding customer purchasing patterns and aligning operations accordingly.

### 2. Peak Sales Times

Identified peak times for sales activity, both by hour and day. This information is crucial for staffing and inventory management.

### 3. Total Monthly Sales Revenue

Calculated the total sales revenue for each month, which helps in tracking business performance over time and identifying trends or seasonality.

### 4. Sales by Store Location

Analyzed sales data across different store locations to understand which stores perform better and contribute more to overall revenue.

### 5. Average Price/Order per Person

Calculated the average spending per customer per transaction, providing insights into customer behavior and potential upselling opportunities.

### 6. Best-Selling Products (Quantity & Revenue)

Identified the top products in terms of both quantity sold and total revenue. This helps in stock management and marketing efforts.

### 7. Sales by Product Category and Type

Analyzed sales variation across different product categories and types to identify which categories contribute the most to sales and revenue.

##  Dashboard Overview

The dashboard includes the following visualizations:
- **Total Sales by Month**: Line chart showing monthly sales trends.
- **Total Quantity by Hours**: Line chart depicting hourly sales distribution.
- **Total Sales by Category**: Bar chart of sales across different product categories.
- **Sales by Store Location**: Bar chart showing sales and footfall across various store locations.
- **Sales Based on Size**: Pie chart showing sales based on product size (Large, Regular, Small).
- **Top 5 Product Types by Sales**: Bar chart of the top five best-selling products by revenue.

##  Key Insights

1. **Peak Hours**: Most sales occur between 7 AM and 11 AM, with a significant peak around 8 AM.
2. **High Revenue Months**: The months of May and June exhibit the highest sales, with a steady upward trend starting from January.
3. **Best-Performing Store Locations**: The stores in Hell's Kitchen and Astoria generate the highest revenue.
4. **Top Product Categories**: Coffee and Coffee beans lead the sales in terms of quantity and revenue.
5. **Popular Product Sizes**: Regular-sized products contribute the most to total sales.

##  Conclusion

By analyzing the sales data, several actionable insights were discovered. The coffee shop can focus on:
- Optimizing inventory and staffing during peak sales hours.
- Prioritizing popular products such as coffee, tea, and espresso drinks to meet customer demand.
- Adjusting store strategies to improve performance in underperforming locations like Lower Manhattan.
- Expanding offerings in high-demand product categories while reassessing less popular categories like packaged chocolates and loose tea.
- Capitalizing on high foot traffic during the morning hours by offering promotions or loyalty programs to increase repeat customers.

Overall, these insights can help the coffee shop enhance its operational efficiency, maximize revenue, and provide a better customer experience across all its locations.
