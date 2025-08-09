# Retail Sales Dashboard

📌 Project Overview
The Retail Sales Dashboard is an interactive Excel-based tool that transforms raw retail transaction data into actionable insights. It provides a clear, visual representation of sales trends, customer behavior, product performance, payment preferences, and operational efficiency. By leveraging Pivot Tables, slicers, charts, and KPIs, the dashboard allows users to explore the dataset dynamically without needing advanced technical skills.

📂 Features

Main Dashboard (Overview)
KPIs: Total Sales, Total Orders, Total Quantity, High Priority Order Value
Trends: Monthly Sales Trend
Sales Breakdown: Sales by Payment Method, Sales by City & Country
Customer Insights: Top-Spending Customers
Operational Analysis: Returned Orders by Shipment Provider

Product Analysis Dashboard
Monthly Sales: Online vs. In-store
Performance Metrics: Quantity by Product Type, Average Discount by Category, Revenue by Product Description
Categorical Insights: Sales by Product Category, Quantity by Sales Channel & Category
Data Sheet: A cleaned and structured dataset for analysis.
Pivot Tables: A total of 12 pivot tables covering different analytical aspects.

📊 Dataset
Source: Online Sales Dataset from Kaggle.
Columns: InvoiceNo, StockCode, Quantity, InvoiceDate, UnitPrice, CustomerID, Country, Discount, PaymentMethod, ShippingCost, SalesChannel, ReturnStatus, ShipmentProvider, Category.

⚙️ Methodology
Data Cleaning & Preprocessing:
Removed duplicates, null CustomerIDs, and invalid entries.
Corrected anomalies, such as negative quantities.
Created a Total Amount column.
Exploratory Data Analysis (EDA):
Analyzed monthly sales trends, payment preferences, top customers, and returns.
Evaluated category and sales channel performance.

Dashboard Design:
Utilized Pivot tables and charts for dynamic interaction.
Incorporated slicers for easy filtering by Country, Year, Category, and Payment Method.

📈 Key Insights
Sales Trends: August saw the highest monthly sales, followed by a seasonal dip from September to December.
Payment Preferences: Bank Transfer is the most popular payment method (35%), with PayPal (33%) and Credit Card (32%) close behind.
Product Performance: Accessories & Furniture are the top-performing categories.
Returns: Returns are evenly distributed among shipment providers, with FedEx having a slightly higher return rate.
Geographic Performance: The United Kingdom leads in total sales, and Amsterdam is the top-performing warehouse city.

🚀 Future Scope
Integrate with Power BI/Tableau for real-time analytics.
Automate dashboard updates using Power Query or VBA.
Add forecasting models for sales prediction.
Implement RFM (Recency, Frequency, Monetary) based customer segmentation.
Conduct profitability and return rate analysis.
Publish the dashboard online for broader accessibility and add a mobile-friendly design.

📎 Project Links
GitHub Repository: Retail Sales Dashboard
Dataset: https://www.kaggle.com/datasets/yusufdelikkaya/online-sales-dataset
LinkedIn Post: https://www.linkedin.com/feed/update/urn:li:activity:7317191276422959104/

📜 License
This project is based on a publicly available dataset under the CC0: Public Domain license.
