# Blinkit Sales Data Analysis: A Comprehensive Report

This project presents an in-depth **SQL-based data analysis** of Blinkit sales, complemented with **Power BI visualizations**. The goal was to transform raw sales data into **actionable insights** that can guide strategic decisions in inventory, marketing, and operations.

---

## 📌 Executive Summary

The analysis identified several critical factors influencing Blinkit’s sales performance and profitability:

* **Medium-sized outlets** and **Supermarket Type1 locations** are the highest-performing segments.
* **“Low Fat” items dominate** sales, making up over **65% of total transactions**.
* **Item visibility has little correlation** with sales performance.
* The **oldest outlets are the most profitable**, suggesting strong customer loyalty.
* The **Supermarket Type1 + Tier 2 location** combination is the most profitable outlet-location pair.

---

## 🛠️ Project Overview & Methodology

* **Tools Used:** SQL (for data cleaning, transformation, and analysis), Power BI (for visualization).
* **Objective:** Convert raw sales data into reliable business intelligence.
* **Data Cleaning:** Standardized inconsistent entries in the `Item_Fat_Content` column (e.g., `LF`, `low fat`, `reg`) to ensure accurate analysis.
* **Analysis Approach:**

  * Aggregation and segmentation using SQL queries.
  * Ranking outlets with **SQL window functions**.
  * Multi-dimensional analysis across **item categories, outlet characteristics, and locations**.

---

## 🔎 Key Findings & Insights

### Overall Sales Performance

* **Top Item Categories:** Fruits & Vegetables, Snack Foods, and Household (40%+ of sales).
* **Fat Content Preference:** “Low Fat” items make up \~64.7% of transactions and \~64.6% of total sales.
* **Outlet Types:** Supermarket Type1 contributes \~65.5% of sales.

### Top & Bottom Performing Outlets

* **Top 5 Outlets (by sales):** OUT035, OUT046, OUT013, OUT018, OUT045.
* **Lowest 5 Outlets (by sales):** OUT019, OUT010, OUT017, OUT049, OUT027.

### Sales by Outlet Characteristics

* **Outlet Size:** Medium-sized outlets lead with \~\$507,896 in sales.
* **Outlet Age:** The **oldest outlet (1998)** tops sales, showing the strength of established locations.
* **Outlet & Location Combo:** Supermarket Type1 in Tier 2 generates **\$393K+ in sales**.

### Highest-Selling Items per Outlet

* Consumer preferences vary by outlet:

  * **Fruits & Vegetables** lead in multiple outlets.
  * **Snack Foods** dominate in others.
  * Some outlets’ top products include **Dairy** and **Frozen Foods**.

### Item Visibility Impact

* Sales are **not strongly influenced by visibility**.
* Items with the highest visibility actually showed **slightly lower sales averages**.
* This disproves the assumption that display prominence alone drives sales.

---

## 📈 Recommendations

Based on findings, the following **data-driven strategies** are suggested:

1. **Optimize Inventory:** Stock more “Low Fat” products, especially in Fruits & Vegetables and Snack Foods.
2. **Strategic Expansion:** Focus on **Tier 2 locations** and **Medium-sized Supermarket Type1 outlets**.
3. **Improve Underperformers:** Analyze operational issues in the lowest-performing outlets.
4. **Targeted Promotions:** Design outlet-specific promotions based on top-selling categories.

---

## ✅ Conclusion

This project demonstrates:

* Strong **SQL skills** (data cleaning, CTEs, window functions, ranking).
* Ability to uncover **multi-layered business insights**.
* Proficiency in **turning raw data into actionable recommendations**.
* Effective use of **Power BI** for storytelling and visualization.

The insights derived offer a **clear roadmap for Blinkit** to optimize inventory, strengthen outlet strategies, and improve profitability through **data-driven decision-making**.

---
