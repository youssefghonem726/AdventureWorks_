# AdventureWorks Sales Performance Dashboard (Power BI)

## Project Overview

This project was developed as a Business Intelligence case study for a global manufacturing company producing cycling equipment and accessories.

Management required a centralized dashboard to monitor and analyze key performance indicators including sales, revenue, profit, returns, customer value, and regional performance.

The objective was to transform raw transactional data into structured insights using data modeling, DAX calculations, and interactive Power BI dashboards.

## Business Questions

The dashboard was designed to answer the following strategic business questions:

- What is the overall financial performance of the company?
- How are sales, profit, and return rates trending over time?
- Which regions generate the highest order volume?
- Which product categories and subcategories drive the most revenue?
- Which products have the highest return rates?
- Who are the highest value customers?
- Are there geographic expansion opportunities?

## Executive Dashboard Insights

The Executive Dashboard provides a summarized view of company performance through key performance indicators.

Key metrics displayed:

- Total Revenue: $24.9M  
- Total Profit: $10.5M  
- Total Orders: 25.2K  
- Return Rate: 2.2%

Key observations:

- Accessories lead in total order volume, followed by Bikes and Clothing.
- Revenue shows a consistent upward trend across the observed period.
- The Top 10 products matrix highlights high-performing products and return behavior.
- The page supports interactive filtering by region and year for dynamic performance comparison.

This page enables leadership to quickly evaluate overall business health and monitor KPI performance in real time.

## Geographic Analysis

The interactive map visualizes global order distribution by continent.

Key findings:

- The United States accounts for the majority of total orders (~8,700).
- The Pacific region contributes a significant share (~6,060 orders).
- Europe shows moderate activity.
- No sales were recorded in Asia, Africa, or South America.

Business implication:

The absence of sales in three major continents highlights potential opportunities for international expansion and strategic market growth.

## Product Performance Analysis (Drillthrough Page)

The Product Details page was designed as a drillthrough page from the Top 10 Products table on the Executive Dashboard. This allows deeper investigation of individual product performance.

### Key Features Implemented

- Drillthrough functionality for product-level deep dive
- Monthly comparison vs target (Orders, Revenue, Profit)
- What-If parameter for price adjustment simulation
- Dynamic narrative summary

## Customer Analysis

The Customer Details page evaluates customer value, segmentation, and purchasing behavior to identify high-value segments and revenue drivers.

### Key Metrics

- Unique Customers
- Revenue per Customer
- Top 100 Customers Ranking
- Orders by Income Level
- Orders by Occupation

### Key Insights

- Revenue per customer varies significantly across segments, indicating differences in purchasing power and engagement levels.
- Customers in Skilled Manual and Professional occupations contribute substantial revenue, highlighting strong demand within working-class and mid-income segments.
- The Top 100 Customers ranking enables identification of high-value individuals responsible for a significant portion of total revenue.
- Revenue per Customer provides a clearer profitability perspective beyond simple order volume.
- Segment-based analysis supports targeted marketing and customer retention strategies.

Business implication:

Understanding customer segmentation allows management to prioritize high-value groups, personalize promotions, and optimize customer acquisition strategies. Rather than treating all customers equally, the dashboard enables data-driven targeting decisions.

## AI Visuals (Advanced Analytics)

To extend the analysis beyond traditional reporting, advanced AI-powered visuals were implemented to uncover hidden patterns and behavioral drivers.

### Decomposition Tree

The Decomposition Tree was used to dynamically break down total orders across multiple dimensions:

- Category  
- Subcategory  
- Product  

This visual enables root-cause exploration of performance drivers.

Key finding:

The dominant sales path follows:

Accessories → Tires and Tubes → Patch Kit/8 Patches

This indicates that low-cost, high-frequency maintenance products significantly drive overall transaction volume. The decomposition analysis helps identify which product layers contribute most to order activity.

---

### Key Influencers

The Key Influencers visual was used to analyze factors affecting customer characteristics, specifically HomeOwner status.

Key findings:

- Marital Status (Married) significantly increases the likelihood of being a homeowner.
- Annual income level strongly influences ownership probability.
- Education level and occupation type also contribute to behavioral patterns.

This analysis moves beyond descriptive metrics and explores predictive relationships within the dataset.

---

Business Value:

By leveraging AI visuals, the dashboard transitions from performance reporting to behavioral insight discovery. This enhances decision-making by identifying not only what is happening, but also potential drivers behind customer and sales trends.

## Advanced Features Implemented

This dashboard incorporates advanced Business Intelligence capabilities beyond standard reporting:

- **Star Schema Data Modeling** for scalable and optimized relationships  
- **Time Intelligence Functions** (YTD, Previous Month, Growth Comparisons)  
- **Custom DAX Measures** for revenue, profit, margin, and performance tracking  
- **What-If Parameter Simulation** for dynamic scenario analysis  
- **Drillthrough Pages** for detailed product-level exploration  
- **Bookmark-Based Interactions** (Filter Panel Toggle & Customer Insight Views)  
- **AI-Powered Visuals** including Decomposition Tree and Key Influencers  

These features demonstrate the ability to move from static dashboards to interactive analytical solutions.

## Tools Used

- **Power BI Desktop**
- **Power Query (ETL & Data Transformation)**
- **DAX (Advanced Calculations & Time Intelligence)**
- **Star Schema Data Modeling**
- **AI Visualizations (Key Influencers & Decomposition Tree)**
