# Furniture Sales Performance Dashboard (Excel)
> *Interactive Excel dashboard analyzing furniture sales performance across different regions in the United States to uncover trends in sales, profit, shipping, and customer segments for better business decision-making.*


---

## Table of Contents

1. [Project Overview](#1-project-overview)
2. [Objectives](#2-objectives)
3. [Project Scope & Tools](#3-project-scope--tools)
4. [Repository Structure](#4-repository-structure)
5. [Data Workflow](#5-data-workflow)
6. [Data Model & Schema](#6-data-model--schema)
7. [Analysis & Metrics](#7-analysis--metrics)
8. [Key Insights](#8-key-insights)
9. [Recommendations](#9-recommendations)
10. [Assumptions & Limitations](#10-assumptions--limitations)
11. [Future Enhancements](#11-future-enhancements)
12. [Deliverables](#12-deliverables)
13. [Author](#13-author)

---

## 1. Project Overview

**Context:** 
This project was developed as part of a hands-on end-to-end Excel dashboard project focused on analyzing furniture sales data across multiple regions in the United States.

**Problem Statement:** 
Businesses often struggle to quickly identify sales trends, profitable regions, top-performing categories, and shipping performance from large sales datasets.

**Approach:**  
Using Microsoft Excel, Power Query, Pivot Tables, Pivot Charts, and slicers, raw sales data was cleaned, transformed, analyzed, and visualized into an interactive dashboard.

**Outcome:**
The final result is a dynamic sales performance dashboard that provides insights into revenue, profit, shipping methods, customer segments, and regional sales performance.

---

## 2. Objectives

- **Primary Objective:** Build an interactive Excel dashboard to analyze furniture sales performance across regions and customer segments.
- **Secondary Objective 1:** Identify trends in sales, profit, and quantity sold over time.
- **Secondary Objective 2:** Analyze shipping methods and delivery performance.
- **Secondary Objective 3:** Visualize geographic and category-level sales performance.

> 💡 *Every analysis and dashboard component in this project was designed to support these objectives.*

---

## 3. Project Scope & Tools

### Scope

-->

| Dimension        | Details |
|-----------------|---------|
| **In Scope**     | Furniture sales data, sales trends, shipping analysis, customer segments, category performance, and regional analysis |
| **Out of Scope** | Predictive modeling, customer demographics, and advanced statistical forecasting |
| **Time Period**  | Historical sales transaction dataset used within the tutorial project |
| **Granularity**  | Transaction-level sales records |

### Tools & Technologies

| Category        | Tool(s) Used |
|----------------|-------------|
| Data Storage    | Excel Workbook / CSV Dataset |
| Data Processing | Microsoft Excel, Power Query |
| Analysis        | Pivot Tables, Pivot Charts |
| Visualization   | Microsoft Excel Dashboard |
| Documentation   | Microsoft Excel / Excel Notes |
| Other           | Slicers, Dynamic Titles |

---

## 4. Repository Structure

```
furniture-sales-performance-dashboard/
│
├── data/
│   ├── raw/          # Original dataset before cleaning
│   └── processed/    # Cleaned and transformed data used for analysis
│
├── dashboard/        # Excel dashboard file (.xlsx)
│
├── visuals/          # Dashboard screenshots for README
│
└── README.md         # You are here (Project documentation)
```

---

## 5. Data Workflow

```
Sales Dataset
      ↓
Data Import into Excel
      ↓
Data Cleaning & Transformation (Power Query)
      ↓
Pivot Table & Pivot Chart Analysis
      ↓
Interactive Dashboard Development
      ↓
Business Insights & Reporting
```

1. **Source:** [Where did the data come from? Format, size, access method.]
2. **Ingestion:** Dataset imported into Microsoft Excel.
3. **Cleaning:** Removed duplicates, standardized formats, and handled inconsistent entries using Power Query.
4. **Transformation:** Created calculated fields, KPIs, and summarized data for dashboard reporting.
5. **Analysis:** Performed trend analysis, category analysis, shipping analysis, and regional comparisons using Pivot Tables and Charts
6. **Output:** Interactive Excel dashboard with filters, KPIs, and visual reports.

---

## 6. Data Model & Schema

# 6. Data Model & Schema

## Dataset: Furniture Sales Data

This dataset contains transactional-level furniture sales records used for analysis and dashboard development.

Each row represents a single sales transaction, including customer, product, shipping, and financial details.

---

## Data Structure

| Field Name     | Data Type | Description | Example Value |
|----------------|----------|-------------|---------------|
| Order ID       | Text     | Unique identifier for each order | CA-2016-152156 |
| Order Date     | Date     | Date the order was placed | 11/08/2016 |
| Ship Date      | Date     | Date the order was shipped | 11/11/2016 |
| Ship Mode      | Text     | Shipping method used | Second Class |
| Customer ID    | Text     | Unique identifier for each customer | CG-12520 |
| Customer Name  | Text     | Name of the customer | Claire Gute |
| Segment        | Text     | Customer segment | Consumer |
| Country        | Text     | Country of purchase | United States |
| City           | Text     | Customer city | Henderson |
| State          | Text     | Customer state | Kentucky |
| Region         | Text     | Geographic region | South |
| Product ID     | Text     | Unique product identifier | FUR-BO-10001798 |
| Category       | Text     | Product category | Furniture |
| Sub-Category   | Text     | Product sub-category | Bookcases |
| Product Name   | Text     | Name of the product | Bush Somerset Collection Bookcase |
| Sales          | Number   | Revenue generated from sale | 261.96 |
| Quantity       | Number   | Number of units purchased | 2 |
| Discount       | Number   | Discount applied to order | 0.00 |
| Profit         | Number   | Profit generated from order | 41.91 |
| Duration       | Text     | Shipping duration | 3 days |
| Month          | Text     | Month of order | Nov |

> **Row count (approx.):** 2122 rows
> **Date range:** 01/06/2014 – 12/30/2017 

---

## 7. Analysis & Metrics

### Analytical Approach

This project uses exploratory data analysis (EDA) in Excel to examine furniture sales performance across regions, customer segments, product categories, and shipping methods. The goal is to identify trends, performance drivers, and business opportunities from transactional sales data.

The analysis was carried out using Pivot Tables, Pivot Charts, and Excel formulas to summarize and visualize key business metrics.


## Key Metrics Defined

| Metric | Definition | Purpose |
|--------|------------|---------|
| Total Sales | Sum of all sales revenue across transactions | Measures overall business revenue performance |
| Total Profit | Sum of profit from all transactions | Shows overall profitability of the business |
| Total Quantity | Total number of items sold | Measures sales volume and demand |
| Average Discount | Average discount applied across orders | Helps assess pricing and discount strategy |
| Profit Margin | Profit divided by Sales | Indicates efficiency and profitability of sales |

### Methods Used

- Pivot Tables for data aggregation and summarization  
- Pivot Charts for visual trend analysis  
- Filtering by Region, Segment, and Category using slicers  
- Time-based analysis using Order Date and Month fields  
- KPI calculations for Sales, Profit, and Quantity  
- Comparative analysis across regions and categories  

---

## 8. Key Insights

**Insight 1: Regional Performance Drives Revenue Differences**
Sales performance varies significantly across regions, with certain regions consistently outperforming others in both sales and profit. This suggests that regional demand, customer behavior, or operational efficiency plays a major role in revenue distribution.

**Insight 2: High Sales Do Not Always Equal High Profit**
Some high-sales orders or categories do not translate into high profit due to discounts and cost factors. This indicates that profitability is strongly influenced by pricing strategy, not just sales volume.

**Insight 3: Consumer Segment Contributes the Highest Sales Volume**
The Consumer segment accounts for the largest share of total sales compared to Corporate and Home Office segments, showing that individual customers drive most of the revenue.

**Insight 4: Shipping Mode Distribution Affects Delivery Patterns**
Standard Class shipping is the most frequently used method, indicating customer preference for cost-effective shipping options over faster delivery methods.

**Insight 5: Seasonal Fluctuations Exist in Monthly Sales**
Sales performance fluctuates across months, with certain months showing higher peaks. This suggests seasonality in furniture demand and potential opportunities for targeted promotions.

---

## 9. Recommendations

| Priority | Recommendation | Based On | Suggested Owner |
|----------|---------------|----------|-----------------|
| High | Focus marketing and inventory allocation on high-performing regions to maximize revenue and ensure stock availability in strong markets | Insight 1 | Sales & Inventory Team |
| Medium | Review pricing and discount strategies for low-profit sales to improve overall profitability without reducing demand | Insight 2 | Pricing/Finance Team |
| Medium | Run targeted campaigns for the Consumer segment to further increase revenue contribution while exploring growth in Corporate and Home Office segments | Insight 3 | Marketing Team |
| Low | Optimize shipping strategy by evaluating the cost vs efficiency of Standard Class shipping to improve delivery performance | Insight 4 | Operations & Logistics Team |
---

## 11. Assumptions & Limitations

## Assumptions

- All transaction records in the dataset are assumed to be complete and accurate.
- Sales, profit, and discount values are assumed to be correctly recorded without external validation from accounting systems.
- Shipping duration values are assumed to reflect actual delivery timelines.
- Customer and product information is assumed to be consistent across all records.

---

## Limitations

- The analysis is based on historical data only and does not include predictive forecasting.
- Customer demographic data (e.g., age, income, behavior patterns) is not available, limiting deeper customer segmentation.
- External factors such as marketing campaigns, competition, or economic conditions are not included in the dataset.
- The dataset is a tutorial/sample dataset and may not fully represent real-world business complexity.
- Analysis is limited to Excel capabilities (no advanced statistical or machine learning modeling applied).*

---

## 12. Future Enhancements

- [ ] Automate data cleaning and transformation using Power Query refresh connections to reduce manual work
- [ ] Build a Power BI version of the dashboard for more advanced interactivity and real-time insights
- [ ] Integrate forecasting models to predict future sales trends based on historical performance
- [ ] Include customer demographic or behavioral data to improve segmentation and targeting analysis

---

## 13. Deliverables

| Deliverable | Description | Location |
|-------------|-------------|----------|
| Excel Dashboard | Interactive furniture sales performance dashboard with slicers and KPIs | `/dashboard/` |
| Raw Dataset | Original unprocessed sales data used for analysis | `/data/raw/` |
| Processed Dataset | Cleaned and transformed dataset used in pivot tables and analysis | `/data/processed/` |
| Visuals | Screenshots and exported charts from the dashboard | `/visuals/` |
| README Documentation | Full project documentation explaining workflow, insights, and analysis | `/README.md` |

---

## 14. Author

**Freedom Omojuwa**
Aspiring Data Analyst | Quantity Surveying Graduate

- 🔗 [LinkedIn URL]
- 💼 freedom-omojuwa.github.io
- 📧 Freedomomojuwa@gmail.com

---

*Last updated: May 2026*

