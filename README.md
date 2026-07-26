# OmniTech_Retail_Anlaysis
OmniTech Retail Performance DashboardA comprehensive Power BI business intelligence solution designed to analyze and optimize retail performance across customer demographics, regional sales, profitability drivers, and return behaviors.

🚀 Project OverviewThis project transforms raw retail data into actionable strategic insights using Power Query for data cleansing/transformation and Power BI for advanced visual modeling. The analytics architecture evaluates customer segmentation, geographic performance, revenue drivers, and operational risks.

🛠️ Tech Stack & Architecture
Data Transformation: Power Query (Data cleaning, handling nulls, formatting dates, column profiling).
Data Modeling: Power BI Desktop (Star Schema modeling, relationships configuration).
Core Capabilities: Demographic Analysis, Geospatial Mapping, Key Influencer Modeling, Trend Forecasting.

📊 Dashboard Modules & Key Insights

1. Customer Demographics Dashboard
Focuses on customer acquisition footprint, geographic reach, and demographic distribution.

Core KPIs:
Total Customers: 1,017
Market Reach: 20 Cities across 4 Regions (East, West, North, South)
Average Order Value (AOV): ₹7,881
Average Quantity Per Order: 1.86 items

VisualDiscoveries:

Seasonality Trends: Customer acquisition spikes aggressively in months 2 (February), 5 (May), and 10 (October), while experiencing sharp drops in months 4, 6, and 8.
Gender Neutral Demographics: The customer base is almost evenly split between Male (34.22%), Other (33.04%), and Female (32.74%).
Revenue Contributor: While the counts are balanced, Male consumers drive the highest sales share (₹15.16M / 34.74%), followed closely by Female buyers (₹14.69M / 33.66%).

2. Sales & Profitability Analysis Dashboard

Evaluates core financials, volume metrics, and logistical operations.
Core KPIs:Gross Revenue: ₹45.96M
Net Profit: ₹20.90M (Healthy ~45.4% profit margin)
Total Orders Processed: 6,500
Total Returns: 703 (10.8% return rate anomaly)

Visual Discoveries:

Regional Champion: The East region is the primary business engine, driving the highest revenue (₹12.34M / 28.3%) and highest profit (₹5.64M / 28.43%).
Underperforming Market: The South region yields the lowest revenue output (₹10.02M / 22.98%) and lowest absolute profits (₹4.55M / 22.96%).
Sales-to-Profit Mirroring: Monthly revenue trends tightly mirror profit trends, indicating consistent operational costs throughout the calendar year.

3. Key Influencer Analysis Dashboard

An AI-driven root-cause module isolating parameters causing performance deterioration.

Core Metric Targeted: Drivers of Profit Decrease.

Visual Discoveries:
The Discount Threshold: High discounting aggressively erodes profitability. When the Sum of Discount exceeds 20.00%, the average profit per transaction drops significantly by an average of ₹1.28K.
Margin Erosion Cascade: Transactions offering a 5.00% or less discount hold an average profit above ₹4K. This drops steadily as discounts step up, plummeting to its lowest level when discounts cross the 20% mark.

💡 Strategic Business Recommendations
Based on the dashboard insights, OmniTech should deploy the following strategies:

Optimize Discount Guardrails: Immediately implement system limits to prevent discounts from crossing the 20% threshold, as this specific behavior directly cuts ₹1,280 out of standard transaction profits.
Address Return Rates: Investigate the 10.8% return rate (703 returns out of 6500 orders). High returns drain logistics budgets and damage net margins.Targeted Regional Expansion: Replicate the high-performing sales playbooks used in the East region to uplift the lagging performance profiles found in the South region.
Capitalize on Demand Spikes: Align marketing spend and inventory stocking schedules with the predictable customer acquisition surges observed in February, May, and October.
