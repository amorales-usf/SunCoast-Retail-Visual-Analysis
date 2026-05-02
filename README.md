
# 📊 SunCoast Retail Visual Analysis (Matplotlib Project)

## 📌 Overview
This project focuses on **data visualization using Matplotlib** to analyze retail sales and customer behavior for SunCoast Retail.

It demonstrates how to transform raw data into meaningful visual insights through:
- Time series analysis
- Category and regional comparisons
- Relationship analysis
- Distribution analysis
- Dashboard creation

---

## 🧰 Technologies Used
- Python 3
- Pandas
- NumPy
- Matplotlib

---

## 📂 Dataset Description

The project generates **synthetic retail data** including:

### 🛍️ Sales Data (`sales_df`)
- Quarterly sales (Q1 2022 – Q4 2023)
- Locations: Tampa, Miami, Orlando, Jacksonville
- Categories:
  - Electronics
  - Clothing
  - Home Goods
  - Sporting Goods
  - Beauty
- Advertising spend
- Sales efficiency metrics

### 👥 Customer Data (`customer_df`)
- Customer ages (18–80)
- Purchase amounts
- Preferred categories
- Price tiers:
  - Budget
  - Mid-range
  - Premium

---

## 🚀 Features

### 📈 Time Series Analysis
- Quarterly sales trends
- Sales comparison across locations

### 📊 Category & Location Analysis
- Grouped bar charts for category performance
- Stacked bar charts for sales composition

### 🔗 Relationship Analysis
- Scatter plot: Advertising spend vs. sales
- Trend line visualization
- Ad efficiency over time

### 📉 Distribution Analysis
- Customer age distribution (histograms)
- Purchase behavior by age group (box plots)

### 💰 Sales Distribution
- Purchase amount histogram
- Sales breakdown by price tier (pie chart)

### 🧩 Market Share Analysis
- Sales by category
- Sales by location

### 📊 Business Dashboard
- Combined visual insights in a multi-plot layout

---

## 📊 Visualizations Included

| Function | Description |
|--------|------------|
| `plot_quarterly_sales_trend()` | Line chart of total sales over time |
| `plot_location_sales_comparison()` | Multi-line comparison by location |
| `plot_category_performance_by_location()` | Grouped bar chart |
| `plot_sales_composition_by_location()` | Stacked bar chart |
| `plot_ad_spend_vs_sales()` | Scatter plot with regression line |
| `plot_ad_efficiency_over_time()` | Ad ROI trend |
| `plot_customer_age_distribution()` | Age histograms |
| `plot_purchase_by_age_group()` | Box plots by age group |
| `plot_purchase_amount_distribution()` | Histogram of purchases |
| `plot_sales_by_price_tier()` | Pie chart by pricing tier |
| `plot_category_market_share()` | Category market share |
| `plot_location_sales_distribution()` | Location market share |
| `create_business_dashboard()` | Multi-plot dashboard |

---

## 🧠 Concepts Demonstrated

- Data visualization best practices
- Time series plotting
- Multi-line comparisons
- Bar and stacked bar charts
- Scatter plots with regression lines
- Histograms and box plots
- Pie charts for proportions
- Subplot dashboards

---

## ▶️ How to Run

1. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib
````

2. Run the script:

   ```bash
   python main.py
   ```

3. All visualizations will display automatically.

---

## 📈 Key Insights (Example)

* 📊 Sales increase significantly in **Q4 (holiday season)**
* 🌴 **Miami** consistently outperforms other locations
* 📺 **Electronics** dominate total sales across categories
* 📉 Advertising shows **positive correlation with sales**, but with diminishing returns
* 👥 Different age groups show **distinct purchasing behaviors**
* 💎 Premium-tier purchases contribute a significant share of revenue

---

## 📊 Dashboard Overview

The project includes a **comprehensive dashboard** combining:

* Sales trends
* Location performance
* Category performance
* Customer purchase distribution

---

## 🔮 Future Improvements

* Add interactive visualizations (Plotly)
* Export charts as images
* Build a web dashboard (Streamlit)
* Add real-world datasets

---

## 📄 License

This project is for educational purposes only.

---

## 👨‍💻 Author

Developed as part of a Module 11 assignment on data visualization using Matplotlib.

