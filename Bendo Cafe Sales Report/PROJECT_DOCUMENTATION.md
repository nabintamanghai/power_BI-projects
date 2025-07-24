# Bendo Café Sales Analysis – Looker Studio Project Documentation

---

## 1. Project Overview

This is a sales analysis dashboard created in Looker Studio connecting a dataset stored in Google Sheets. The dashboard gives an overview of how Bendo Cafe is performing in terms of sales, products, and regions.

**Name**: Bendo Café Sales Analysis  
**Tool**: Google Sheets and Google Looker Studio (Google Data Studio)  
**Data Source**:

| Column Name | Description | Example |
|-------------|-------------|---------|
| Order ID | Unique identifier for each order | TCSTORD1 |
| Date | When the product was sold | 2023-01-02 |
| Product | Name of the drink | Mystic Oolong |
| Category | Product type (Coffee or Tea) | Tea & Coffee |
| State | U.S states | Georgia |
| Units Sold | Quantity of the product or drinks | 3 |
| Unit Price | Cost per single product or drinks (in USD) | $2.50 |
| Sales | Total sales per orders (Unit Price × Units Sold) | $7.50 |

**Purpose**: To analyze and optimize the sales performance of “Bendo Café” across various products and states to identify top selling items, seasonal trends, and underperforming categories in order to make data driven decisions for inventory, marketing, and expansion.

---

## 2. Business Objectives/Goal

1. Track sales trends over time.
2. Identify best selling products & categories.
3. Understand regional performance.
4. Measure revenue contribution per product.
5. Detect low performing items for discount offers.

**KPIs to Include:**  
- Total Order  
- Total Sales  
- Total Units Sold  
- Average Units Price  
- Average Sales Value  
- Average Unit Sold  

---

## 3. Key Metrics (KPIs)

- **Total Order**: 962  
- **Total Sales**: $8,127  
- **Total Unit Sold**: 2338  
- **Average Unit Price**: $3.49  
- **Average Unit Sold**: 2.43  
- **Average Sales Value**: $8  

These metrics help track overall sales and business performance.

---

## 4. Dashboard Components & Chart Descriptions

### 1. Top KPI Tiles

- **Total Order**: Overall number of orders done within the given time period (2023-01-03 to 2024-12-28)  
- **Total Sales**: Total sales  
- **Total Units Sold**: Quantity sold  
- **Average Unit Price**: Average cost per product  
- **Average Unit Sold**: Average quantity per order  
- **Average Sales Value**: Average revenue per order  

**Business Value**: These numbers help quickly understand the overall status of our customer base and whether our efforts are working.

---

### 2. Sales by Category (Donut Chart)

**What it shows:**  
- Tea contributes 50.4% of total sales.  
- Coffee contributes 49.6%.  

**Why it matters:**  
Reveals slight category preference for planning and marketing.

**How It Helps:**  
- Focus Tea promotions and bundles.  
- Push Coffee offers to balance sales.  
- Helps inventory planning.

**Insight:**  
Both categories perform well but Tea slightly leads.

---

### 3. Sales by Product (Horizontal Bar Chart)

**What it shows:**  
- Mystic Oolong leads with $1,572.  
- Velvety Vanilla Latte follows at $1,490.  
- Espresso Energizer is lowest at just over $1,000.

**Why it matters:**  
Quickly identifies best and worst performing products.

**How It Helps:**  
- Promote top sellers like Mystic Oolong.  
- Offer combos or redesign low sellers like Espresso Energizer.

**Insight:**  
Espresso Energizer has room for repositioning instead of removing.

---

### 4. Revenue Contribution by Product (Donut Chart)

**What it shows:**  
- Mystic Oolong: 19.3%  
- Velvety Vanilla Latte & Bold Brewed Mocha: ~18%  
- Espresso Energizer: 13.1%

**Why it matters:**  
Optimizes inventory and marketing based on product importance.

**How It Helps:**  
- Feature top earners in promos.  
- Rework bottom contributors.  
- Align inventory to product revenue.

**Insight:**  
Revenue is well distributed, tweak pricing and bundling for improvements.

---

### 5. Top 5 States by Sales (Bar Chart)

**What it shows:**  
- Georgia is top performer in sales and volume.  
- Texas & North Carolina are balanced.  
- Ohio sells well but earns less.  
- Pennsylvania underperforms.

**Why it matters:**  
Highlights regional strengths and weaknesses.

**How It Helps:**  
- Boost prices in Ohio.  
- Run campaigns in Pennsylvania.  
- Focus expansion on Georgia.

**Insight:**  
Run regional promos and price tests.

---

### 6. Monthly Sales Trend by Category (Stacked Vertical Bar Chart)

**What it shows:**  
- Tea leads most months.  
- Coffee wins in September & December.  
- Coffee spikes in December ($356.2).

**Why it matters:**  
Shows seasonal product performance.

**How It Helps:**  
- Promote Coffee in Q4.  
- Build Tea loyalty campaigns.  
- Plan seasonal inventory.

**Insight:**  
Capitalize on Coffee spikes, maintain Tea’s steady presence.

---

### 7. Filters or Slicers

- **Category**, **Date**, **Product**, **State**  
- **Dynamic Analysis**: Drill-down capability by filters.  
- **Business Value**: Empowers custom analysis and quick decisions.

---

## 8. Project Goal Answered

| Questions | Answers |
|----------|---------|
| Track sales trends over time | Monthly charts show seasonal patterns & demand shifts. |
| Identify best selling products & category | Mystic Oolong = top product, Tea = best overall, Coffee = holiday star |
| Understand regional performance | Georgia #1 in sales & orders, California & Illinois need action. |
| Measure revenue contribution per product | Mystic Oolong contributes most with 19.3%, Espresso Energizer least with 13.1%. |
| Detect low performing items for discount offers | Espresso Energizer and Illinois flagged for offers or marketing push. |

---

## 9. Key Insights & Recommendations

### Sales Trends:
- December = Coffee’s BIG month (holiday effect).  
- Tea dominates most of the year.  
- Sales peak during colder seasons.

### Product Performance:
- Tea = Best category.  
- Coffee = Holiday hero.  
- Ohio sells more but earns less → check pricing.

### Regional Performance:
- Georgia is top state.  
- Illinois underperforms.

**Recommendations:**  
- Boost Coffee promotions in colder months.  
- Run ads in California & Illinois.  
- Introduce Tea bundles/loyalty cards.  
- Adjust pricing where necessary.

---

## 10. Conclusion

This Looker Studio dashboard offers a clear, interactive view of Coffee vs. Tea sales trends. It empowers business teams to:  
- Identify product trends & seasonal shifts  
- Take strategic actions (campaigns, inventory, promos)  
- Drive revenue with data-driven decisions

**Prepared In**: July 22, 2025  
**By**: Nabin Tamang  
"""

