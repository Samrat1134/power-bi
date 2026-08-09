# power-bi
Interactive Power BI dashboard for Superstore sales analytics with What-If simulation, AI decomposition tree, and drill-through capabilities.

# 📊 Superstore Sales Analytics Dashboard

## 🚀 Live Demo

![Power BI Dashboard Preview](screenshot1.png)
*(Replace with your actual screenshot file name)*

---

## 📌 Project Overview

This is an **enterprise-grade Power BI dashboard** built for a retail company to monitor sales performance, profitability, and regional trends. It transforms raw transaction data into **actionable business intelligence** through interactive visualizations, real-time simulations, and drill-through capabilities.

**Key Metrics:**
- 💰 **Total Sales:** $2.30 Million
- 📈 **Total Profit:** $286,400
- 📦 **Total Orders:** 5,000+
- 📊 **Profit Margin:** 12.4%

---

## 🎯 Problem Statement

The management team needs a **single, centralized, interactive dashboard** to answer critical business questions:

- What is our **total revenue and profit**?
- Which **products and regions** are driving the most sales?
- How is our sales performance **trending over time**?
- Which **customer segments** are most profitable?
- How would changing **discounts** impact overall profitability?

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Data visualization and interactive reporting |
| **Power Query (M Language)** | Data cleaning, transformation, and ETL |
| **DAX (Data Analysis Expressions)** | Custom measures, time intelligence, and calculations |
| **Star Schema** | Data modeling for optimal performance |

---

## 📊 Dataset

| Detail | Information |
|--------|-------------|
| **Source** | Sample Superstore (publicly available dataset) |
| **Rows** | ~10,000 transactions |
| **Time Period** | 2014 – 2017 |
| **Key Columns** | Sales, Profit, Quantity, Discount, Category, Sub-Category, Region, Segment, Order Date |

---

## 📈 Dashboard Features

### Page 1: Executive Summary

| Visual | What It Shows |
|--------|---------------|
| **KPI Cards** | Total Sales ($2.3M), Total Profit ($286K), Total Orders (5K), Profit Margin (12.4%) |
| **Sales Trend (Line Chart)** | Year-over-year sales growth from 2014 to 2017 |
| **Sales by Category (Bar Chart)** | Technology leads, followed by Furniture and Office Supplies |
| **Sales by Region (Bar Chart)** | West region leads, followed by East, Central, and South |
| **Interactive Slicers** | Filter by Year, Region, Category, and Segment |

### Page 2: Geographic Performance *(if built)*
- **Map visualization** showing sales by state
- Color-coded by profit margin
- Compare sales and profit across regions

### Page 3: Product Detail (Drill-Through Page)
- **Transaction-level table** showing:
  - Order ID
  - Order Date
  - Customer Name
  - Category
  - Sub-Category
  - Product Name
  - Sales, Profit, Quantity, Discount
- **Right-click drill-through** from any Category or Sub-Category bar

### Advanced Interactive Features

| Feature | Description |
|---------|-------------|
| **What-If Parameter** | Interactive slider (0–50%) to simulate discount changes and project revenue impact |
| **Drill-Through** | Right-click any Category or Sub-Category to view transaction-level details |
| **Dynamic Titles** | Headers update based on slicer selections |
| **Interactive Slicers** | Filter by Region, Category, Segment, and Year |

---

## 🔍 Key Business Insights

| Insight | Finding |
|---------|---------|
| **Top-Performing Category** | **Technology** generates the highest sales ($0.6M+) |
| **Top Region** | **West** region contributes ~35% of total revenue |
| **Largest Customer Segment** | **Consumer** segment accounts for nearly half of total orders |
| **Sales Growth** | Steady growth from 2015 to 2017 with a sharp increase in 2017 |
| **Discount Impact** | Discounts >20% negatively impact profit margins |

---

## 📸 Screenshots

### Page 1: Executive Summary
![Executive Summary](screenshot1.png)

### Product Detail Drill-Through Table
![Product Detail](screenshot3.png)

### What-If Simulator
![What-If Simulator](screenshot2.png)

---

## 🚀 How to View the Dashboard

### Option 1: Download and Open
1. Download the `.pbix` file from this repository.
2. Open it using **Power BI Desktop** (free version).
3. Interact with slicers and visuals to explore the data.

### Option 2: View Online (If Published)
- [Click here to view the live dashboard] *(Add your Power BI Service link if published)*

---

## 📁 Repository Structure

---

## 🎯 Interactive Features in Action

### What-If Parameter (Discount Simulator)
- Adjust the **Discount Adjustment Slider** (0% – 50%)
- Watch **Projected Sales** update in real-time
- Compare projected vs. actual sales performance

### Drill-Through Analysis
- Right-click any **Category** or **Sub-Category** bar
- Select **"Drill through → Product Detail"**
- View all transactions for that specific category

### Dynamic Filters
- Click any **Year** (2014–2017) to filter all visuals
- Click any **Region** (Central, East, South, West) to focus on specific areas
- Click any **Category** (Furniture, Office Supplies, Technology) to analyze specific products
- Click any **Segment** (Consumer, Corporate, Home Office) to understand customer behavior

---

## 📝 Author

**[Your Name]**

- 🔗 [LinkedIn](https://linkedin.com/in/yourprofile)
- 🔗 [GitHub](https://github.com/yourusername)
- 📧 your.email@example.com

---

## 📜 License

This project uses the **Sample Superstore** dataset, which is publicly available for educational and analytical purposes.

**Dataset Source:** Sample Superstore (public dataset)  
**License:** Educational and Analytical Use Only

---

## ⭐ If You Found This Useful

- ⭐ Star this repository to show your support!
- 🔗 Share it with others who might find it helpful.
- 📩 Reach out if you have any questions or suggestions.

---

## 🗓️ Project Status

✅ **Completed** – Version 1.0

- [x] Data cleaning and transformation (Power Query)
- [x] Star Schema data model
- [x] DAX measures and KPIs
- [x] Interactive dashboard (3 pages)
- [x] What-If Parameter (Discount Simulator)
- [x] Drill-Through functionality
- [x] Dynamic titles
- [x] Interactive slicers
- [x] Professional formatting and branding

---

*Built with ❤️ using Power BI*

