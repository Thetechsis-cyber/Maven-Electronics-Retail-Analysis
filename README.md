# Maven Electronics Retail Analysis

### Overwiew
Maven Electronics is a global retailer that sells computers, cell phones, TVs, cameras, appliances, and other consumer products through both online and in-store
channels. The company operates across multiple regions and aims to improve profitability, monitor store and product performance, and enhance customer satisfaction.

### Business Problem: 
Revenue has been on a downward trend since 2020, and management currently lacks a unified view of performance across sales channels, regions, and customer demographics.
Without an interactive dashboard, it is difficult to identify top performing products, regions, and customer segments, or to understand areas of declining performance. 
Management needs a consolidated data model and an interactive report to explore key sales drivers, monitor revenue and profit trends, and evaluate store and product-level
performance.

### Business Objective
Create a sales performance dashboard for a global electronics retailer to consolidate and analyze sales, customer, product, and store data. The dashboard will track key
performance metrics, uncover sales trends, and provide actionable insights for management to make data-driven decisions.

### Business Questions
1. Overall Performance (KPI Tracking)
* What is our total revenue, profit, quantity sold, and customer count?
* Are these KPIs growing or declining compared to targets?
2. Trends Over Time (Monthly Analysis)
* How have revenue, profit, quantity, and customer count changed month by month since 2020?
* Are there seasonal patterns or months where performance consistently drops?
3. Year-over-Year (YoY) Comparison
* How does performance in the current year compare to previous years?
* What is the YoY growth/decline % for revenue, profit, and customers?
* Are we recovering or still trending downward?
4. Product Performance
* Which products, categories, and subcategories are driving revenue and profit growth?
* Which ones are underperforming and contributing to the decline?
* What are the top 10 best-sellers vs. the bottom 10 laggards?
5. Customer Insights
* Who are our customers? (gender, age, geography)

### Data Model Overview
The dataset consists of multiple related tables:
* Sales: Contains transactional data including orders, delivery dates, quantities, currency, and links to customers, stores, and products.
* Customers : Provides customer demographics (gender, age, location) to analyze customer behavior and segmentation.
* Products: Includes product details (brand, color, subcategory, category, unit cost, and unit price) for product performance and profitability analysis.
* Stores: Provides store-level details (location, size, and open date) to assess regional and store performance.
* Exchange Rates (Supporting Table): Provides conversion rates by date and currency to ensure consistent reporting in USD

### Data Cleaning and Preparation
The dataset was cleaned and transformed for analysis by:
* Imported the 5 tables into PowerBI query editor
* Checked for duplicate rows: None was found.
* Checked structure (rows, columns, data types).
* Ensured numerical columns are in number format.
*  Standardized categorical fields
* Created calculated columns and measures table.

The cleaned dataset is now ready for visualization and insights.

[view my dashboard here
](https://app.powerbi.com/view?r=eyJrIjoiODk4YjU4N2ItYzhmMy00ZjYzLWE1OTUtMDNjMTQzN2Q2ZGUyIiwidCI6IjE5NDlmNzRjLTQzY2UtNDRhZi1iYTdhLWJhYjRhYjYyNzljNiJ9)

### Key Insights
* Strong profitability – $55.8M revenue, $32.7M profit → ~59% margin. Business is financially healthy.
* Walk-in stores dominate – 79.55% of revenue comes from physical stores; online is only 20.45%.
* Revenue peaked in 2019 (~$18.3M) then fell in 2020 and 2021 (sharp drop), – performance dropped sharply in 2020–2021, showing vulnerability to external shocks
  (e.g., supply chain, pandemic).
* Revenue dips around March–April, picks up toward year-end → possibly seasonal buying (holiday spikes, fiscal-year cycles).
* Product concentration – In Category level, Computers and Home Appliances are the backbone (largest in both revenue & profit) while Computer(44K units) and
   Cell phones(31K units) sold the most in terms of quantity.
* In Sub-Category level, Desktops and Television are the backbone (largest in both revenue & profit), while in term of quantity, Movie DVDs (29K units) sell the most,
   but with very low unit value compared to desktops (21K units). 
* In brand level, Adventure Works and Contoso are the biggest drivers of revenue and profit while Contoso sells the most units (50K), but revenue/profit leadership belongs
  to Adventure Works.
* The best-seller is WWI Desktop PC2131 X2100 Black (~$505K) and Other top revenue drivers are also desktop PCs, with revenues between $437K–$466K. Items like USB cables
   (~$15–$25 revenue each) contribute negligible revenue.
* Customer concentration – A handful of customers contribute disproportionately to revenue and profit, there will be risk if any leave.
* Geographic reliance – By Continent,  North America (esp. U.S.) drives most revenue/profit. Europe has potential, Australia is weak.
* By Country, United States is the top profit driver ($17.5M), far ahead of UK ($4.1M), Germany ($3.2M), Canada ($2.8M), and Australia ($1.6M).
* By City, Toronto ($348.67K), New York ($286.19K), Los Angeles ($273.09K) lead in city-level profit. This suggests high concentration of profitability in a few urban areas
* Balanced gender contribution – Revenue and profit are roughly balanced across male/female — both are significant audiences.
* Customers between the ages of 66 years and above contribute more to revenue while customers between the ages of 23-35 years contribute less to revenue. 

### Recommendation
* Protect high profit leaders
* Plan big promotions in November–December and stimulate off-peak (March–April) with clearance sales or loyalty promotions to smooth revenue dips.
* Boost online sales by promoting real-time inventory display and digital marketing campaign 
* VIP treatment for top customers such as dedicated service and exclusive service.
* Review low value categories and subcategories if they are worth shelf space in store or consider moving them online only.
* High value categories and sub categories should always be prioritized for in-store stocking to avoid out-of-stock scenarios and lost sales.

