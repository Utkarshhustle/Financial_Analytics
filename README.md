# 📊 E-Commerce Sales Analysis Dashboard

**Project Type:** End-to-End Business Analytics  
**Tech Stack:** SQL · Python · Power BI  
**Duration:** 3 Weeks  
**Status:** Completed  
**Repository:** [Financial_Analytics](https://github.com/Utkarshhustle/Financial_Analytics)

---

## 🧭 Project Objective

Simulating a real-world scenario for an e-commerce company, this project analyzes sales data to:
- Understand customer behavior
- Perform RFM (Recency, Frequency, Monetary) segmentation
- Visualize trends through a Power BI dashboard
- Provide actionable business recommendations to improve revenue and retention

---

## 🛠 Tools & Technologies Used

| Tool      | Purpose                              |
|-----------|--------------------------------------|
| **SQL**   | Data cleaning, joins, transformation |
| **Python**| EDA, RFM analysis, visualizations    |
| **Power BI** | Interactive dashboard building     |
| **Pandas, Matplotlib, Seaborn** | Data analysis and visualization in Python |

---

## 🔄 Workflow Overview

### 1. **Data Collection & Understanding**
- Realistic e-commerce dataset with ~99K customers and 135K order items
- Data covers product orders, payments, reviews, and customer info

### 2. **SQL-Based Data Cleaning**
- Cleaned and joined datasets:
  - `customers`, `orders`, `order_items`, `payments`, `products`, etc.
- Filtered relevant time frame: **May 2016 – Oct 2018**

### 3. **Python EDA & RFM Segmentation**
- **Recency** = Days since last order  
- **Frequency** = Number of orders per customer  
- **Monetary** = Total payment value

Sample RFM Table:
| CustomerID | Recency | Frequency | Monetary | R | F | M | RFM_Score |
|------------|---------|-----------|----------|---|---|---|-----------|
| 00012a...  | 287     | 1         | ₹114.74  | 2 | 1 | 3 | 6         |
| 000161...  | 409     | 1         | ₹67.41   | 1 | 1 | 2 | 4         |

---

## 📈 Power BI Dashboard Insights

**Dashboard Includes:**
- Monthly Orders & Revenue Trend
- Revenue by Product Category & State
- Payment Type Distribution
- RFM-Based Customer Segmentation
- Year-over-Year Growth

![Power BI Dashboard](./Power-Bi%20Dashboard.png)

---

## 📊 Key Analytical Insights

- **Customer Spend**: Most customers spend ₹50–₹300, very few spend ₹1000+
- **Order Frequency**: ~85–90% customers are one-time buyers
- **Payment Method**: Credit Cards dominate (75%+)
- **Top Revenue States**: SP, RJ, MG
- **Category Leaders**: Health, Watches, Computing products

---

## 💡 Final Business Recommendations

1. **Launch Loyalty Program**  
   To increase frequency among one-time buyers

2. **Re-engagement Campaigns**  
   Target low-frequency, high-recency customers

3. **Upsell to High RFM Segments**  
   Promote high-value bundles to top 10% customers

4. **Subscription-Based Models**  
   For customers with high monetary but low frequency

5. **Combo & Bundling Offers**  
   Increase AOV (Average Order Value) and repeat purchases

---

## 📁 Project Structure


