
# 🛒 UrbanCart Superstore – Data Analysis Project

A comprehensive Python-based retail data analysis project focused on uncovering profit drivers, margin leakages, and performance insights across products, regions, and customer segments using Pandas and Matplotlib.

# 📌 Project Overview

UrbanCart Superstore experiences steady sales growth but inconsistent profitability across regions and product categories.
This project analyzes transactional retail data to identify why high sales don’t always translate into high profits and provides actionable, data-driven recommendations.

**Key Goals:**

* Analyze revenue, profit, and margin trends

* Identify loss-making regions and categories

* Compare performance across time, geography, and segments

* Support strategic decision-making with insights

# 🧠 Business Problem

Despite increasing sales, UrbanCart faces:

* Margin compression

* Regional losses (especially Central region)

* Category-level profitability imbalance

👉 The objective is to diagnose root causes and recommend profit optimization strategies.

# 📂 Dataset Details

Source: Public Superstore dataset (GitHub)

**Records:** 9,994 transactions

**Columns:** 25

Granularity: Each row represents one order line item

Key Data Columns

* **Order & Shipping**

  * Order ID, Order Date, Ship Date, Ship Mode, Delivery Days

* **Customer**

  * Customer ID, Customer Name, Segment

* **Geography**

  * Country, City, State, Region, Postal Code

* **Product**

  * Category, Sub-Category, Product Name, Product ID

* **Financials**

  * Sales, Quantity, Discount, Profit

* **Time Dimensions**

  * Year, Month, Year-Month

# 🛠️ Tools & Technologies

* Python

* Pandas – data manipulation & analysis

* Matplotlib – data visualization

* VS Code

* PowerPoint – insight presentation

# 🔧 Data Preparation & Feature Engineering

* Validated and standardized data types

* Converted date columns to datetime

* Checked and handled duplicate records

* Generated statistical summaries for numeric columns

* Engineered Columns

  * Revenue = Sales × Quantity

  * Net Revenue = Revenue × (1 − Discount)

  * Year-Month for trend and MoM analysis

  * Profit Margin = Profit / Revenue

# 📊 Key Business Insights
🔹 Overall Performance

* Total Revenue: $9.9M

* Total Profit: $286K

* Profit Margin: 2.89%

* Units Sold: 37,873

📈 Revenue and profit show consistent year-over-year growth, with December 2016 being the best-performing month.

# 🌍 Regional Analysis
| Region  | Revenue     | Profit Margin | Insight               |
| ------- | ----------- | ------------- | --------------------- |
| West    | $3.14M      | **21.95%**    | Strongest performer   |
| South   | $1.73M      | 16.35%        | Healthy profitability |
| East    | Significant | 16.72%        | Stable & reliable     |
| Central | $2.09M      | **-10.41%**   | ❗ Loss-making region  |

# 📦 Category Analysis
| Category        | Revenue     | Profit Margin | Observation              |
| --------------- | ----------- | ------------- | ------------------------ |
| Technology      | $3.49M      | **4.16%**     | Highest revenue & profit |
| Office Supplies | Strong      | 3.86%         | Consistent margins       |
| Furniture       | High volume | **0.57%**     | Margin concern           |

# 📈 Visualizations Included

* Monthly revenue & profit trends

* Year-over-year growth analysis

* Region-wise revenue & profit comparison

* Category and sub-category performance

* High-sales vs low-profit identification

(All charts created using Matplotlib)

# 💡 Strategic Recommendations
* 📌 Regional Optimization

  * Immediate investigation into Central region losses

  * Review discounting, logistics costs, and product mix

* 📌 Product Strategy

  * Increase focus on Technology and Office Supplies

  * Re-evaluate pricing and costs for Furniture

* 📌 Profitability Improvement

  * Reduce excessive discounting

  * Optimize supplier negotiations

  * Focus on high-margin SKUs

* 📌 Customer Strategy

  * Introduce loyalty programs for high-value customers

  * Personalized offers to improve lifetime value
