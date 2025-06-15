# Power-Bi-UPI_Dashboard
Purpose

This Power BI dashboard is a professional-grade, multi-page analytics solution designed to help stakeholders analyze UPI transaction data,
for insights into transaction behavior, fraud patterns, user demographics, and system performance. Built with a modular and dynamic structure,
it delivers both executive summaries and AI-driven insights.

Pages Overview

1.Executive Summary

Purpose: High-level KPIs for decision-makers.
Key Elements:

KPI cards: Total Txns, Total Amount, Avg Amount, Fraud Rate

Donut: Transaction Type Split

Bar Chart: Merchant Category Spend

Line Chart: Amount Trend by Date

Gauge: Fraud Rate (%)

Table: Top Transactions by Value

2. Demographic & Channel Insights

Purpose: Explore user behavior & transaction channels.
Key Elements:

Stacked Bar: Age Group by Device

Heatmap: Hour vs Day of Week

Pie: Network Type

Bar Chart: Sender Bank

Matrix: Sender State × Receiver Bank

Scatter Plot: Hour vs Amount (Fraud Highlight)

3. Fraud Detection Insights

Purpose: Investigate fraud patterns and identify high-risk areas.
Key Elements:

KPI Cards: Fraud Count, Fraud Amount, Fraud Rate

Bar Chart: Transaction Type vs Fraud

Line Chart: Fraud Trend over Time

Map: State-wise Fraud Incidence

Table: Fraud Transaction Details

4. AI-Powered Insights

Purpose: Automatically generated insights using Power BI’s built-in AI.
Key Elements:

Decomposition Tree: Drill into total/fraud amount by categories

Key Influencers: Discover top predictors of fraud

Smart Narrative: Auto-summarized text-based insights

Q&A Visual: Ask natural-language questions

Line + Anomaly: Detect transaction spikes or irregular patterns

Dataset Used

Filename: UPI_Cleaned.csv

Columns: Transaction ID, Timestamp, Transaction Type, Merchant Category, Amount (INR), Transaction Status, Sender/Receiver Age Group, Sender State, Sender/Receiver Bank, Device Type, Network Type, Fraud Flag, Hour, Day, Weekend, Time, Date

🎨 Design Standards

Fonts: Segoe UI, Calibri

Theme: Bright colors (Green=Success, Red=Fraud, Blue=Weekend)

Layout: 2x3 visual grid with responsive spacing

Format: Consistent DAX naming, dynamic slicers, clean tooltips


Integrate real-time fraud prediction model (Python API)

Enable drillthrough pages from high-risk categories

👤 Author & Credits

Dashboard Developer: Power BI Analyst / AI Developer (5+ Years Experience)
Contact: Zohaib Khan
