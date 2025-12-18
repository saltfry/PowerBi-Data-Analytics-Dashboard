🛒 Madhav Store Sales Analysis | Power BI Project
📌 Executive Summary

This project transforms raw e-commerce data into an interactive sales intelligence tool. By analyzing 1,500+ transactions, the dashboard identifies growth drivers, customer purchasing patterns, and regional performance for Madhav Store.

🎯 Business Challenges Addressed

    Sales Tracking: Monitoring monthly profit and revenue fluctuations.

    Customer Segmentation: Identifying "Power Shoppers" for targeted marketing.

    Logistics Insights: Tracking geographical sales distribution to optimize supply chains.

    Payment Preferences: Analyzing the shift between COD and Digital Payments (UPI/Cards).

🛠️ Technical Workflow
1. Data ETL (Extract, Transform, Load)

    Connected flat CSV files via Power Query.

    Performed data profiling to handle missing values and inconsistent date formats.

    Relationship Mapping: Established a 1:Many relationship between the Orders and Details tables using Order ID.

2. DAX & Analytics

Created advanced measures to go beyond surface-level data:

    AOV (Average Order Value): AOV=∑Quantity∑Amount​ to track spending per customer.

    Dynamic Ranking: Used filters to isolate Top 5 States and Categories.

3. Data Visualization

    Conditional Formatting: Profit bars change color (Red/Blue) based on positive/negative margins.

    Interactive Slicers: Dynamic filtering by Quarter and State for real-time drill-downs.

📊 Dashboard Preview

<img width="1905" height="943" alt="image" src="https://github.com/user-attachments/assets/00f25dfc-7dc4-4054-b9cd-da0a4f322e45" />


📈 Key Insights

    Top Category: Clothing dominates with 63% of total orders.

    Peak Performance: Significant profit spikes observed in specific months (Oct-Dec seasonality).

    Regional Leader: Maharashtra is the highest-grossing state.

    Customer Loyalty: Top 4 customers contribute roughly 15% of the total revenue.
    
    Dataset/: Raw CSV files used for the analysis.
