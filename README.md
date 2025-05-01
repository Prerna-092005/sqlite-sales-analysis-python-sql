# Task 7 - Sales Summary with Python and SQLite

## Objective
Analyze sales data stored in a SQLite database using SQL inside Python. Generate a summary of total quantity and revenue by product, and visualize the results using bar and pie charts.

## Tools Used
- Python
- SQLite (`sqlite3`)
- Pandas
- Matplotlib
- Jupyter Notebook

## Steps Performed

### 1. Created SQLite Database
A new database `sales_data.db` was created containing a single table `sales` with sample product data including quantity and price.

### 2. Ran SQL Query to Summarize Data
Used a SQL query to calculate:
- Total quantity sold (`SUM(quantity)`)
- Total revenue (`SUM(quantity * price)`)
Grouped by product.

### 3. Loaded Data into pandas
The SQL result was imported into a pandas DataFrame for analysis.

### 4. Displayed Sales Summary
Printed a clean summary showing quantity and revenue per product.

### 5. Visualized Results
Created the following charts using `matplotlib`:
- **Bar Chart** of Revenue by Product
- **Bar Chart** of Quantity Sold by Product
- **Pie Chart** showing Quantity Share
- **Pie Chart** showing Revenue Share

### 6. Calculated Total Revenue
Displayed total revenue across all products.

### 7. Bonus Insights
- Identified the **top-selling product** (by quantity)
- Identified the **highest revenue product**
- Calculated **average revenue per unit** per product

### 8. Exported to CSV
Exported the summary DataFrame to `sales_summary.csv`.

## Outputs
- Jupyter Notebook: `Task7.ipynb`
- Database file: `sales_data.db`
- Charts: `sales_chart.png`, `quantity_chart.png`, `quantity_pie_chart.png`, `revenue_pie_chart.png`
- CSV file: `sales_summary.csv`

## Sample Charts
Screenshots included in the notebook:
- ![Bar Chart Revenue](sales_chart.png)
- ![Pie Chart Quantity](quantity_pie_chart.png)

## Conclusion
This project demonstrates the ability to:
- Use SQL inside Python
- Perform basic data aggregation
- Visualize business data effectively
- Extract real-world insights from sales data
