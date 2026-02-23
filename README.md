# 🛒 Superstore Sales Analysis Dashboard

A comprehensive data analysis project exploring sales, profit, and discount trends for a US-based retail superstore. Built using **Excel** for data cleaning and analysis, and **Power BI** for interactive dashboard visualization.

---

## 📊 Dashboard Preview

![Superstore Sales Analysis Dashboard](Superstore_Dashboard.pdf)

---

## 🎯 Business Questions Answered

1. Which regions are most and least profitable?
2. Which product categories and sub-categories drive the most revenue and profit?
3. Are discounts helping sales or hurting profitability?
4. Which customer segments are most valuable?
5. What does the sales trend look like over time — is the business growing?

---

## 🔍 Key Insights

- **West region** is the top performer with $725K in sales and a 21.9% profit margin
- **Central region** is losing money despite $501K in sales — driven by heavy discounting
- **Technology** is the most profitable category ($145K profit); **Furniture** barely breaks even ($18K profit)
- **Discounts above 20% consistently destroy profit** — Binders (37% avg discount, -19.9% margin) and Tables (26% avg discount, -14.7% margin) are the worst offenders
- **Home Office** customers have the highest profit margin (14.2%) despite being the smallest segment
- Business grew **51% in sales** and **89% in profit** from 2014 to 2017 — profit growing faster than sales indicates improving efficiency

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| Microsoft Excel | Data cleaning, pivot table analysis, profit margin calculation |
| Power BI | Interactive dashboard creation and visualization |

---

## 📁 Project Structure

```
Superstore-Sales-Analysis/
│
├── Superstore_Analysis.xlsx     # Cleaned data + pivot table analysis
├── Superstore_Dashboard.pbix    # Power BI dashboard file
├── Superstore_Dashboard.pdf     # Exported dashboard (static view)
└── README.md                    # Project documentation
```

---

## 📌 Dataset

- **Source:** [Superstore Dataset - Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- **Records:** 9,994 rows
- **Columns:** 21 (Order details, Customer info, Product info, Sales, Profit, Discount)
- **Time Period:** 2014 – 2017

---

## 🧹 Data Cleaning Steps

- Verified zero duplicate rows across all columns
- Confirmed no missing/blank values in any column
- Fixed inconsistent date formats in Order Date and Ship Date columns
- Added calculated column: **Profit Margin = Profit / Sales**

---

## 📈 Dashboard Features

- **4 KPI Cards:** Total Sales (2.30M), Total Profit (286.40K), Total Orders (5,009), Avg Profit Margin (12%)
- **Sales & Profit by Region:** Horizontal bar chart comparing all 4 regions
- **Category Performance:** Clustered column chart across Technology, Furniture, Office Supplies
- **Sales Trend 2014–2017:** Line chart showing year-over-year growth
- **Discount vs Profit by Sub-Category:** Scatter plot revealing the discount-profit relationship
- **Interactive Region Slicer:** Filter all visuals by region with one click

---

## 💡 Business Recommendations

1. **Investigate Central region discounting strategy** — the region is generating losses despite significant sales volume
2. **Re-evaluate Tables and Bookcases pricing** — both sub-categories are loss-making and dragging down Furniture profitability
3. **Cap discounts at 20%** — data clearly shows discounts beyond this threshold consistently result in negative margins
4. **Invest more in Home Office segment** — highest profit margin at 14.2%, strong growth opportunity

---

## 👤 Author

Simerpreet Kaur 

Data Analyst | Excel • SQL • Power BI • Python 

https://www.linkedin.com/in/simer-preet-kaur/ 

https://github.com/Simer45
