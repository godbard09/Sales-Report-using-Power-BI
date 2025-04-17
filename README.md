# Problem Statement
The task involves designing and implementing a Sales Report System for Elite Retails. The company requires a system that can consolidate data from various sources, process it, and deliver comprehensive insights into sales performance across multiple dimensions. These include total sales, sales by product category, regional sales distribution, and sales trends over time. The primary goal is to provide actionable insights for the company's leadership and other stakeholders to optimize sales strategies, improve performance, and make data-driven decisions.

# Steps Followed
**1. Data Collection:** Gathered all required datasets from multiple sources including sales files (Excel), geography data (Excel), and sales representative data (Excel).

**2. Data Preprocessing:**

* Split location data into city and country.

* Cleaned ID fields (removed prefix “ID - ”) for consistency.

* Adjusted date formats for proper analysis.

**3. Data Modeling:**

* Created the Sales fact table and linked it to the other tables (Geography, SalesRep, Categories, etc.).

* Ensured unique identifiers (e.g., GeoKey) were used to establish relationships between tables.

**4. DAX Calculations:**

* Implemented measures to calculate Total Revenue, Total Cost, Gross Profit, and Sales Growth.

* Created time-based measures (e.g., Monthly Growth, Quarterly Growth) for trend analysis.

**5. Data Visualization:**

* Designed and developed an interactive dashboard with different visualizations such as bar charts for product categories, heat maps for regional sales, and line graphs for sales trends.

# Key Highlights:
1. Total Revenue reached 126.01M, demonstrating strong business performance during the reporting period.

2. Gross Profit stood at 86.89M, accounting for over 68% of total revenue, reflecting a healthy profit margin and effective pricing strategy.

3. 4 million units were sold, confirming large-scale operations and high product demand.

4. Germany and the Czech Republic emerged as top-performing markets in terms of unit sales, playing a crucial role in overall revenue.

5. Products under 'Regular' and 'Deluxe' subcategories contributed the highest gross profit, proving to be key revenue drivers.

6. Q2 recorded the most significant growth in both revenue and profit, indicating successful seasonal campaigns or business strategies.

7. Monthly gross profit trends show positive growth overall, with some slowdowns in months like August, suggesting areas for strategic improvement.

# Final Result
## Sales Report

![image](https://github.com/user-attachments/assets/1289c33a-1cf0-47c0-b855-e58ca8974527)
