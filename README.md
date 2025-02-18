# Home_Sales_Solution

🏡 Home Sales Analysis - PySpark & Colab
📌 Project Name: Home Sales Analysis using PySpark in Google Colab
📌 Notebook: Home_Sales_Solution.ipynb

📖 Project Overview
This project analyzes home sales data using PySpark to answer key business questions related to real estate pricing, trends, and performance improvements using caching and Parquet optimization.

🔹 Data Source: AWS S3 bucket - home_sales_revised.csv

🔹 Tools Used:
Google Colab (for cloud-based execution)
PySpark (for Big Data processing)
Parquet Format (for optimized storage)
SQL Queries (for data analysis)

📌 Key Objectives & Steps

1️⃣ Data Import & Processing
Read home_sales_revised.csv from AWS S3 into a PySpark DataFrame.
Create a temporary table for SQL queries.

2️⃣ SQL Analysis on Home Sales Data
🏠 Average home price for 4-bedroom homes per year
🏡 Average price of homes with 3 beds & 3 baths per year built
📏 Average price for homes (3 bed, 3 bath, 2 floors, ≥2,000 sqft) per year built
🌟 Average price per "view" rating (≥$350,000), with runtime measurement

3️⃣ Performance Optimization

Cache the dataset and re-run queries to compare execution time.
Partition by date_built and save data in Parquet format.
Compare query performance between cached, uncached, and Parquet-based queries.
📊 Performance Comparison
Query Type	Execution Time (seconds)
Uncached Query	⏳ 0.2900846004486084
Cached Query	⚡ 0.634345293045044 seconds
Parquet Query	🚀 0.6004045009613037 seconds


🛠 How to Run the Notebook
1️⃣ Open the Google Colab Notebook.
2️⃣ Run the cells sequentially to process the dataset.
3️⃣ Modify SQL queries if needed to perform additional analysis.
4️⃣ Compare the runtime performance of uncached vs. cached vs. Parquet queries.

🚀 Technologies Used
PySpark SQL
Google Colab
Parquet Format
AWS S3 (Data Source)
Big Data Processing
📂 Repository Structure
bash
Copy
Edit
📦 Home_Sales_Project
 ┣ 📜 Home_Sales_Solution.ipynb  # Colab Notebook
 ┣ 📜 README.md                   # Project Documentation
 
🎯 Conclusion
This project demonstrates how PySpark SQL can process large datasets efficiently and improve performance with caching & Parquet optimizations. 🚀



🔗 Author: Neda Jamal

📧 Contact: neda.jamal@yahoo.com - LinkedIn: linkedin.com/in/nedajamal

📢 Star ⭐ this repository if you found it helpful! 🌟
