**Inventory Demand & Product Performance Dashboard (SQL & Power BI)**
**Dashboard Link: https://app.powerbi.com/groups/me/reports/8ebc7360-77dd-4516-86e0-2f23aac26a1e?ctid=1ca90c9a-c0b5-4503-a35a-726a4f55924a&pbi_source=linkShare**

The objective of this dashboard is to help the business understand product demand patterns, availability issues, and pricing impact. By analyzing order trends, stock availability, and product-level demand, the organization can identify inventory shortages, high-demand items, and optimize supply chain planning.

This report allows stakeholders to:

Track demand fluctuations by product

Identify availability issues

Evaluate unit price impact

Improve forecasting and inventory management

Steps Followed
Step 1 — Data Loading

Imported CSV datasets containing Order Date, Product ID, Availability, Demand, Product Name, and Unit Price into Power BI Desktop.

Step 2 — Data Cleaning (SQL)

Cleaned and transformed data using SQL:

Handled missing values and invalid records

Standardized dates (DD/MM/YYYY)

Merged product tables using Product ID

Created new calculated fields for analysis

Step 3 — Power BI Modelling

Connected cleaned SQL output to Power BI.

Created relationships between order and product tables using Product ID.

Created calculated columns/measures such as:

Total Demand

Availability Status

Revenue (Unit Price × Demand)

Demand Forecast Buckets

Step 4 — Visualization

Added slicers for Product Category, Availability Status, Date Range.

Created visuals such as:

Line chart for monthly demand trends

Bar chart for top/high-demand products

KPI cards for total demand, total revenue, and availability %

Table for product-wise price and demand comparison

Applied formatting, themes, and tooltips for better readability.

Step 5 — Insights Identification

Analyzed availability vs. demand to identify stockout risks.

Highlighted products generating maximum revenue.

Identified seasonal or monthly peaks in demand based on Order Date.

Key Insights
1. Product Demand Trends

Certain SKUs show consistently high demand across months.

Demand spikes are observed in certain periods, indicating seasonality.

2. Availability Challenges

Products with low availability but high demand can lead to lost sales.

Multiple items show repeated “Unavailable” status, highlighting supply gaps.

3. Price–Demand Relationship

Products with higher unit prices showed moderate demand.

Lower-priced items contributed to higher total volume.

4. Revenue Contribution

Top 10 products generated a significant portion of total revenue.

Unit price variations impacted revenue more than demand alone.
