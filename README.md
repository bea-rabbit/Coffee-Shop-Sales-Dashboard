# Coffee-Shop-Sales-Dashboard
## About the Dataset

The dataset contains transaction records from Mavean Roasters, a fictitious coffee shop operating out of three locations in New York City. It includes the transaction date, timestamp, and location, along with product-level details.

## Data Description

- `transaction_id` : Unique sequential ID representing an individual transaction
- `transaction_date` : Date of the transaction (MM/DD/YY)
- `transaction_time` : Timestamp of the transaction (HH:MM:SS)
- `transaction_qty` : Quantity of items sold
- `store_id` : Unique ID of the coffee shop where the transaction took place
- `store_location` : Location of the coffee shop where the transaction took place
- `product_id` : Unique ID of the product sold
- `unit_price` : Retail price of the product sold
- `product_category` : Description of the product category
- `product_type` : Description of the product type
- `product_detail` : Description of the product detail

## Project Overview

This project presents an interactive Power BI dashboard that analyzes coffee shop sales data. All data cleaning, transformation, and modeling were performed directly within Power BI using Power Query and DAX.

The dashboard provides insights into:

- How have Maven Roasters sales trended over time?
- Which days of the week and hours of the day are the busiest?
- Which product categories contribute most to overall revenue?
- Which products are sold most and least frequently? Which generate the highest revenue?

## **KEY INSIGHTS**

**1. Sales Overview**
    
In the first 6 months of 2023, total revenue from coffee shop locations in New York reached approximately **$699K**, with **214K units sold**. **Brewed Chai Tea** was the best-selling product, with **26,250 units sold**. This product contributed a significant protion to the overall sales, indicating high customer preference.
    
**2. Product Categories**
    
**Coffee** and **Tea** were the two core product categories, accounting for the majority of total sales:

- **Coffee** is the largest contributor to revenue, accounting for 89K units sold, **$269.95K** in revenue—over 40% of total sales. This highlights the popularity and importance of coffee products for Maven Roasters, reinforcing the idea that coffee is the cornerstone of their business.
- **Tea** contributes 70K units sold, bringing in **$196.41K**, making it the second most popular category. This indicates a strong consumer demand for tea, suggesting that the product offerings in this category are well-received by customers.
- Other products such as **Bakery** and **Drinking Chocolate** also contributed notably to sales, with 23K and 17K units sold, respectively.
**3. Sales by Store Location**
    
All three store locations had relatively balanced revenues, with no significant difference between them:

- **Hell’s Kitchen**: Contributed 33.84% of total revenue
- **Lower Manhattan**: Accounted for 32.92%
- **Astoria**: Contributed 33.23%
**4. Sales by Month**
    
The monthly sales revenue shows a general upward trend from January to July 2023. This indicates positive business growth and increasing customer engagement over the months.

- **January to March**: Revenue ranged from **$76K to $99K**, indicating stable consumption but no sharp growth.
- **April to June**: Revenue increased significantly each month, with **$157K in May** and **$166K in June**. These were the highest revenue months in the first half of the year, showing a strong rise. This upward trend may be attributed to seasonal factors, shifts in consumer behavior, or promotional campaigns conducted during this time.
**5. Sales by Days of the Week**
- **Weekdays (Monday to Friday)**: Revenue remained relatively stable between **$99K and $102K**. **Monday** and **Friday** had the highest figures, with $102K and $101K respectively, suggesting increased customer traffic at the beginning and end of the workweek.
- **Weekends (Saturday and Sunday)**: Revenue slightly decreased to around **$97K**.This could be due to customers engaging in different activities over the weekend or the presence of other competing business.
**6. Sales by Hours of the Day**
    
There was a clear fluctuation in revenue across different time slots:

- **Peak Hours**: Revenue peaked between **8 AM and 10 AM**, when customers typically buy coffee and breakfast before starting their day.
- **Gradual Decline**: After 10 AM, revenue dropped significantly and after 12 PM, revenue continued to decline steadily until closing, indicating that coffee consumption is concentrated more in the morning than in the afternoon or evening.

## Recommendations:

- **Boost weekend and evening engagement**: Implement promotional events or introduce evening-specific menu items to attract more customers and increase sales during lower-traffic periods such as weekends and late hours.
- **Optimize operational costs**: Adjust staffing levels and streamline operations based on traffic patterns to improve efficiency during both peak and off-peak hours.
- **Leverage High-Performing Products**: Expand popular categories such as coffee and tea offerings with new flavors and sizes, and implement targeted promotions to further capitalize on their strong performance and custoemr appeal.
