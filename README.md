# Zepto-Data-analysis
Business-focused analytics project using Python and SQL to analyze Zepto's product portfolio, pricing strategy, inventory distribution, and revenue opportunities through data-driven insights.

## 📂 Dataset

The dataset consists of **3,700+ products** from Zepto's online grocery catalog. Each record represents a product and contains information related to pricing, discounts, inventory, package size, and stock availability.

### Features

- **Category** – Product category
- **Name** – Product name
- **MRP** – Maximum Retail Price
- **Discount Percentage** – Discount applied on the product
- **Discounted Selling Price** – Final selling price after discount
- **Available Quantity** – Current inventory available
- **Weight (g)** – Product weight in grams
- **Out of Stock** – Product availability status
- **Quantity** – Pack size or unit description

  ## 🚀 Project Approach

### Phase 1: Data Preparation (Python)

Cleaned and validated the raw dataset by converting prices from paise to rupees, removing invalid records, checking data quality, and preparing a consistent dataset for SQL-based business analysis.

### Phase 2: Business Analysis (SQL)

Used SQL to answer real-world business questions related to product pricing, discounts, inventory management, and revenue estimation. Each query was designed to generate actionable insights for business decision-making.

---

## 📈 Business Insights Generated

The SQL analysis focuses on answering the following business questions:

- Identify the **Top 10 products offering the highest discounts**.
- Find **high-priced products that are currently out of stock**, highlighting potential missed revenue opportunities.
- Estimate **potential revenue by category** based on selling price and available inventory.
- Compare products using **price per gram** to identify better value-for-money options.
- Determine **which categories offer the highest average discounts**.
- Analyze the **total inventory weight** across product categories to understand inventory distribution.
- Segment products into **Low, Medium, and Bulk weight categories** for inventory planning.
- Identify **premium products with low discounts**, helping evaluate pricing and promotional strategies.
