📊 **E-Commerce Sales Dashboard — Power BI Project**

📝 **Overview**

This project showcases an interactive E-Commerce Sales Dashboard built in Power BI.
Using real-world sales data, the dashboard highlights key business metrics, sales trends, customer insights, and profitability across different product categories and regions.

The goal is to enable business owners and decision-makers to quickly understand:

1. Which products and categories generate the most revenue

2. How sales and profit change over time

3. Performance by region and customer segment

4. High-level KPIs such as Total Sales, Total Profit, Total Customers, and Profit Margin

📂 **Project Objectives**

Clean and prepare raw sales data for analysis

Build a structured data model using Power BI

Create DAX measures for KPIs and business metrics

Develop visually compelling and interactive dashboards

Provide actionable business insights

🛠 **Tools & Technologies**
Power BI Desktop - Data modeling, DAX, dashboard development
Power Query Editor - Data cleaning and transformation
Microsoft Excel - Source dataset
DAX (Data Analysis Expressions) - Custom measures & calculations

🧹 **Data Preparation**

Using Power Query, the dataset was cleaned and transformed by:

Correcting data types (Date, Text, Numeric)

Handling column quality issues

📐 **Data Modeling**

Created several important DAX measures, including:

Total Sales = SUM('superstore'[Sales])

Total Profit = SUM('superstore'[Profit])

Total Quantity = SUM('superstore'[Quantity])

Total Customers = DISTINCTCOUNT('superstore'[Customer Name])

Profit Margin = DIVIDE([Total Profit], [Total Sales])

📊 **Dashboard Features**

The final dashboard includes:

📌 KPI Cards

Total Sales

Total Profit

Total Customers

Total Quantity

Profit Margin

📈 Visualizations

Line Chart — Monthly Sales vs Profit

Matrix Heatmap — Segment & Category Profitability

Bar Chart — Top Selling Products

Bar Chart — Sales by Region

Donut Chart — Sales by Category

Slicers — Year and Category filters

Custom Background & Color Theme for clean styling

🔍 **Key Insights**

Technology & Office Supplies categories show strong profit margins

Sales peak in the final months of the year

West and East regions are the top revenue contributors

A small number of products contribute heavily to total sales

Customer base is diverse but has clear high-value segments

🚀 **How to Use**

Download the .pbix file

Open in Power BI Desktop

Refresh the dataset (if needed)

Interact with slicers and visuals to explore insights

🤝 **Contributions**

Feel free to fork this repository and suggest improvements through pull requests.

📬 **Contact**

For any questions or collaboration requests, connect with me on LinkedIn or GitHub.
