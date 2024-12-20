# Target Dataset Analysis  

### Overview  
This project analyzes the Target dataset, a comprehensive collection of data covering 100,000 orders from Brazil between 2016 and 2018. The data includes information on customer demographics, orders, payments, shipping, and product reviews. The project was conducted in a Jupyter Notebook environment, showcasing skills in data exploration, manipulation, and analysis using SQL-like queries and Python.  

### Dataset Description  
The dataset is organized into eight CSV files:  
- **customers.csv**: Information about customers, including location details.  
- **sellers.csv**: Details of sellers who fulfilled orders.  
- **order_items.csv**: Data on individual order items, including price and product details.  
- **geolocation.csv**: Geographical details for customer locations.  
- **payments.csv**: Payment methods and installments for each order.  
- **orders.csv**: Order-specific information, such as order status and timestamps.  
- **products.csv**: Product-related attributes, such as category and description.  

### Objective  
This project aims to derive insights from the dataset by addressing a series of predefined queries grouped into basic, intermediate, and advanced levels. The results help reveal trends in customer behavior, order performance, and overall business efficiency.  

---

## Analysis and Queries  

### Basic Queries  
1. **List all unique cities where customers are located.**  
2. **Count the number of orders placed in 2017.**  
3. **Find the total sales per category.**  
4. **Calculate the percentage of orders that were paid in installments.**  
5. **Count the number of customers from each state.**  

### Intermediate Queries  
1. **Calculate the number of orders per month in 2018.**  
2. **Find the average number of products per order, grouped by customer city.**  
3. **Calculate the percentage of total revenue contributed by each product category.**  
4. **Identify the correlation between product price and the number of times a product has been purchased.**  
5. **Calculate the total revenue generated by each seller, and rank them by revenue.**  

### Advanced Queries  
1. **Calculate the moving average of order values for each customer over their order history.**  
2. **Calculate the cumulative sales per month for each year.**  
3. **Calculate the year-over-year growth rate of total sales.**  
4. **Calculate the retention rate of customers, defined as the percentage of customers who make another purchase within 6 months of their first purchase.**  
5. **Identify the top 3 customers who spent the most money in each year.**  

---

## Tools and Libraries  
- **Python**  
  - Pandas  
  - NumPy  
  - Matplotlib and Seaborn (for visualization)  
  - SQLAlchemy for query-style operations  
- **Jupyter Notebook**: To execute and present the analysis.  

---

## Results and Insights  
- Trends in customer demographics and order patterns were revealed.  
- Payment methods and their effect on customer behavior were analyzed.  
- Product categories contributing the most to revenue were identified.  
- Customer retention and seller performance insights were derived.  

---

## How to Run the Project  
1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/devarajv88/target-dataset?select=products.csv).  
2. Place the CSV files in the project directory.  
3. Open the Jupyter Notebook file and run each cell to replicate the analysis.  

---

## Conclusion  
This project showcases advanced data analysis skills and provides actionable insights into Target's Brazilian operations. It is an example of how data can drive strategic business decisions and enhance operational efficiency.  

---
