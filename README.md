# Forecast-Dashboard
# Inventory-Dashboard
🌼 FNP Inventory Intelligence Dashboard
A dynamic Power BI dashboard developed for Ferns N Petals (FNP) to optimize inventory planning and deepen customer insights across major Indian markets—Delhi, Bangalore, and Mumbai. This report brings together forecasting, sales performance, and customer profiling into one interactive analytical solution.

📌 Short Description / Purpose
The FNP Inventory Intelligence Dashboard is a strategic business tool designed to help decision-makers track inventory demand, identify top-selling customers (CID-wise), and understand customer behavior across three key locations. It simplifies complex reporting into visual insights to support informed business planning.

⚙️ Tech Stack
The dashboard was built using the following tools and technologies:

📊 Power BI Desktop – Core platform for data visualization and interactive reporting.

📂 Power Query – Used for ETL operations (Extract, Transform, Load) to prepare and clean datasets.

🧠 DAX (Data Analysis Expressions) – Implemented to build forecasts, rankings, KPIs, and conditional visuals.

🧱 Data Modeling – Defined relationships across sales, customer, and inventory tables to enable seamless filtering.

📁 File Format – .pbix (Power BI file) and .png for high-res dashboard previews.

🗂 Data Source
Mock data has been structured to reflect realistic business logic using three primary datasets:

Sales Data: Date, CID, product, units sold, revenue.

Customer Data: CID, region (Delhi/Bangalore/Mumbai), customer type, segment.

Inventory Data: Product ID, CID, current stock, reorder level, historical demand.

🌟 Features / Highlights
• Business Problem
Inventory mismatches and delayed demand recognition can lead to stockouts, lost revenue, or excess inventory. FNP needed a scalable solution that offers location-specific forecasting, sales visibility, and customer intelligence.

• Goal of the Dashboard
To provide a user-friendly analytics tool that:

Predicts future inventory needs based on CID-level trends.

Tracks top-performing CIDs based on sales volume/value.

Delivers customer insights to guide engagement and strategy.

Allows both location-specific and combined analysis for flexible decision-making.

• Walkthrough of Key Visuals
🟢 Inventory Forecast by CID (Top Left)
A predictive model uses historical monthly sales data to estimate future demand at the CID level. Forecasts are calculated using Power BI’s time series capabilities and show:

Next 3 to 6 months' demand

Seasonal trends and anomalies

CID-level granularity

This allows procurement and supply chain teams to plan replenishment before demand peaks.

📈 CID-wise Sales Ranking (Top Right)
A sorted visual showing CIDs from highest to lowest sales. Users can switch between monthly, quarterly, or yearly performance.

👥 Customer Insights Panel (Middle)
Breaks down customer data by:

Region

Customer Type (new vs returning)

Revenue Contribution

Count of Active vs Dormant Customers

🌍 Location Slicers (Top Navigation)
Toggle between Delhi, Bangalore, and Mumbai to isolate trends or analyze them together in a combined view.

📊 Combined Overview
All metrics are available in a summary view to support pan-India business decisions.

• Forecast Analysis
The forecasting logic is built using Power BI’s native Analytics pane, enhanced with:

DAX formulas for monthly trendline smoothing

Time-based grouping to capture moving averages

Auto-adjusting projections when filters (like city or CID) are changed

This makes the forecast dynamic, user-responsive, and actionable for monthly purchase planning and budget forecasting.

• Business Impact & Insights
Reduced Inventory Risk: Anticipate demand, cut down stockouts.

Revenue Focus: Spotlight on top-selling CIDs improves planning and marketing.

Customer Strategy: Understand where value is concentrated and how to serve segments better.

Scalable Model: Easily replicable for other cities or regions as the business grows.

![Report](https://github.com/user-attachments/assets/e996cf45-7ab7-401c-b43c-78893fc5ac91)
