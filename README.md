# adidas-spark-sql-insights
This project analyzes Adidas U.S. retail sales data using PySpark and Spark SQL. It provides insights into total sales, profit, units sold, performance by region, product, and retailer—enabling data-driven decision-making with interactive queries and visualizations.

# 🚀 Project Implementation Steps
### 1. Project Setup

- 📁 Create a new notebook in databricks platform by providing suitable name (eg: adidas_sales_insights_extraction_using_pyspark_and_sparksql)
- 🔗 Make sure to select the python interpretor and the cluster if avaible or you can create a new cluster.
- 📄 Upload your dataset (Adidas_US_Sales_Datasets.csv) in the catalog page and copy the path.

### 2. Data Loading & Exploration
   
- 📥 Load the CSV file using spark.read.csv
- 🕵️ Inspect schema and preview data with .limit() and .show()

### 3. Create Temp View
🧮 Use createOrReplaceTempView("adidas_sales") to use Spark SQL queries

### 4. Perform Analysis
   
- Split your requirements across different cells or scripts with visual outputs:

- ✅ Requirement 1: Total sales, profit, avg price, total units
- 📅 Requirement 2: Sales by month
- 🌎 Requirement 3: Sales by state
- 🌍 Requirement 4: Sales by region
- 👟 Requirement 5: Sales by product
- 🛍️ Requirement 6: Sales by retailer
- 🎯 Requirement 7: Units sold by product category/gender
- 🌆 Requirement 8: Top cities by operating profit
- 🛒 Requirement 9: Units sold by sales method

### 5. Visualization

- 📊 Use visualization in result block to visualize your result according to your interest
- 🌈 Highlight trends, top contributors, etc.

### Note:
- I used both Spark SQL and PySpark to test my knowledge in using PySpark(Python) and Spark SQL(SQL)
- Either use Spark SQL or PySpark, both will provide the same results.
