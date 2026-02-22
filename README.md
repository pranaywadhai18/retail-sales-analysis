# retail-sales-analysis
# 📌 Project Overview

This project analyzes raw retail sales data to uncover key business insights related to:  
Revenue trends over time\n
Top-selling products
High-performing countries/regions
Overall business performance
The goal is to simulate a real-world business analytics scenario and provide strategic recommendations as if advising a company.

# 🎯 Objectives
During this task, the following objectives were achieved:
✔ Cleaned and organized raw sales data (CSV format)
✔ Analyzed monthly revenue trends
✔ Identified top-selling products
✔ Identified high-value countries
✔ Built visual dashboards using Python
✔ Generated actionable business insights and recommendations

# 🛠 Tools & Technologies Used
VS Code (Jupyter Notebook Extension)
Python 3.12
Pandas – Data Cleaning & Analysis
Matplotlib & Seaborn – Data Visualization
OpenPyXL – Excel Export

# 📂 Dataset Information
The dataset contains retail transaction data including:
Invoice Number
Product Code
Product Description
Quantity
Invoice Date
Unit Price
Customer ID
Country

# 🔎 Project Workflow
1️⃣ Data Cleaning
Removed missing values in:
Description
CustomerID
Removed cancelled/returned transactions:
Negative Quantity
Negative UnitPrice
Converted InvoiceDate to datetime format
Created new column:
Revenue = Quantity × UnitPrice
2️⃣ Revenue Trend Analysis
Extracted Year-Month from InvoiceDate
Grouped data by month
Calculated total monthly revenue
Visualized using line chart
📈 Insight:
Revenue peaks during Q4 (September–November), indicating strong seasonal demand.
3️⃣ Top-Selling Products
Grouped data by product description
Calculated total revenue per product
Sorted in descending order
Visualized top 10 products
🛍 Insight:
Decorative and home-related products generate the highest revenue.
4️⃣ High-Value Countries
Grouped revenue by country
Identified top-performing regions
Visualized using bar chart

🌍 Insight:
United Kingdom contributes the majority of revenue, with strong potential in European markets.
5️⃣ Key Business KPIs
Total Revenue
Total Orders
Average Order Value (AOV)
Top Country
Best-Selling Product

#📊 Dashboard Outputs
The project includes:
Monthly Revenue Trend Chart
Top 10 Products Chart
Top 10 Countries Chart
KPI Summary

# 💡 Business Recommendations
1️⃣ Seasonal Strategy
Increase inventory before Q4
Launch marketing campaigns starting in Q3
2️⃣ Product Strategy
Expand high-performing product categories
Create bundles and premium variations
3️⃣ Geographic Expansion
Focus marketing efforts in strong European markets
Reduce revenue dependency on one country

# 📈 Business Impact

This analysis helps the company:
Identify revenue growth patterns
Improve inventory planning
Optimize marketing strategy
Reduce geographic revenue risk
Increase profitability through data-driven decisions

# 🚀 How to Run This Project

Install required libraries:
pip install pandas matplotlib seaborn openpyxl
Open the notebook in VS Code
Run all cells sequentially
Review generated charts and insights

# 🏆 Skills Demonstrated

Data Cleaning & Preprocessing
Exploratory Data Analysis (EDA)
Data Visualization
Business Insight Generation
Dashboard Creation
Analytical Thinking
Report Writing

# 📌 Project Type

✔ Academic Submission
✔ Portfolio Project
✔ Entry-Level Data Analyst Practice
✔ Business Intelligence Simulation

# 👨‍💻 Author
pranay wadhai
Data Analyst | Python | Business Intelligence
