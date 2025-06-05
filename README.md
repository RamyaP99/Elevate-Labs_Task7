# Elevate-Labs_Task7

### Basic Sales Summary from SQLite Database

This project extracts a basic sales summary from a small SQLite database (sales_data.db) using Python. It computes total quantity sold and total revenue per product with SQL queries, displays results via print statements, and visualizes revenue using a matplotlib bar chart. The tools used are Python (sqlite3, pandas, matplotlib) and SQLite (built-in). 

**Key Outputs:**

* Printed table with product, total quantity, and revenue (e.g., Laptop: 3 units, $2500).
* Bar chart (sales_chart.png) showing revenue per product.
* Insights: Identifies high-revenue products (e.g., Laptops) for business focus.

**Dataset**

The dataset is a single table (sales) in sales_data.db, created programmatically:

Columns:
              
            product (TEXT): Product name (e.g., Laptop, Phone, Tablet).
            quantity (INTEGER): Units sold.
            price (REAL): Price per unit (e.g., $1000.00).

Sample Data: 6 rows (3 products: Laptop, Phone, Tablet) with varied quantities and prices.

Creation: The Python script generates sales_data.db and populates the sales table.

**Details:**
* Create sales_data.db with a sales table and sample data.
* Execute SQL query to compute total quantity and revenue per product.
* Print results as a table (e.g., Laptop: 3 units, $2500).
* Generate a bar chart (sales_chart.png) showing revenue per product.
* Revenue is calculated as quantity * price per row, summed by product.

  No external dataset is required; the script includes sample data.

**Outputs**

**Table:** Pandas DataFrame with product, total_qty, revenue.

**Chart:** Bar chart with products on x-axis, revenue on y-axis (saved as sales_chart.png).

**Sample Insights**
* Laptops generate high revenue due to high prices, despite lower quantities.
* Phones have low revenue due to low prices, despite high quantities.
