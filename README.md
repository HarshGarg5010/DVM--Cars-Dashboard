<h1 align="center">🚗 DVM-CAR | Automotive Sales & Performance Dashboard</h1>

<p align="center">
  <b>Transforming $2.8B of automotive sales data into actionable business insights</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/DAX-0078D4?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Power%20Query-217346?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" />
</p>

<p align="center">
  <a href="[YOUR_POWER_BI_PUBLISH_TO_WEB_LINK]"><b>🔗 View Live Dashboard</b></a> •
  <a href="#-dashboard-preview">Screenshots</a> •
</p>

---

## 📌 Project Overview

**DVM-CAR** is an interactive Power BI dashboard that analyzes **$2.8 billion in sales across 192 car models over 20 years**. It uses interactive visuals, dynamic filters, and DAX-powered KPIs to support strategic decision-making and business performance monitoring.

## 📊 Project at a Glance

| Metric | Details |
|---|---|
| Total Sales Analyzed | $2.8 Billion |
| Car Models | 192 |
| Analysis Period | 20 Years |
| Dashboard Pages | 4 |
| Visualization Tool | Power BI |
| Data Processing | Power Query |
| Calculations | DAX |

## 🖼️ Dashboard Preview

| Executive Sales Overview | Brand & Model Performance |
|---|---|
| ![Overview](images/page1-overview.png) | ![Brand](images/page2-brand-model.png) |

| Regional Sales Analysis | Yearly Sales Analysis |
|---|---|
| ![Regional](images/page3-regional.png) | ![Yearly](images/page4-yearly.png) |

## 🎯 Project Objectives

- Analyze overall automotive sales performance
- Evaluate brand-wise and model-wise sales contribution
- Identify regional sales patterns and performance
- Track yearly sales trends over two decades
- Develop dynamic KPIs for business performance monitoring
- Enable interactive analysis through business filters

## 📈 Dashboard Pages

1. **Executive Sales Overview:** KPI cards, interactive filters, and high-level performance monitoring.
2. **Brand & Model Performance:** brand comparison, top-performing models, and model-level sales contribution across 192 models.
3. **Regional Sales Analysis:** regional comparison, geographic distribution, and high-performing regions.
4. **Yearly Sales Analysis:** 20-year historical trends and year-over-year comparisons.

## 🧮 DAX Measures & KPIs

| KPI | Business Purpose |
|---|---|
| Total Sales | Measures overall revenue generated |
| Average Selling Price | Evaluates average vehicle selling price |
| Profit Margin | Measures profitability performance |
| Total Buyers | Tracks customer/buyer volume |
| Total Units Sold | Measures total vehicle sales volume |

<details>
<summary><b>View sample DAX</b></summary>

```DAX
Total Sales = SUM(Sales[SalesAmount])

Total Units Sold = SUM(Sales[Units])

Average Selling Price = DIVIDE([Total Sales], [Total Units Sold])

Profit Margin % = DIVIDE(SUM(Sales[Profit]), [Total Sales])
```
*(Replace with your actual measures and column names.)*
</details>

## 🔍 Key Insights

> Add 3–5 real findings from your dashboard. Recruiters love this section.

- 🏆 **Top brand/model:** [e.g., Brand X contributed Y% of total sales]
- 🌍 **Top region:** [e.g., Region X led in sales]
- 📈 **Trend:** [e.g., Sales peaked in YEAR and declined afterwards]
- 💰 **Profitability:** [e.g., Average profit margin was X%]

## 🛠️ Tools & Technologies

| Technology | Application |
|---|---|
| Microsoft Power BI | Interactive dashboard development |
| DAX | Calculated measures and KPI development |
| Power Query | Data cleaning and transformation |
| Microsoft Excel | Data preparation and source data management |

## 💼 Skills Demonstrated

Power BI Dashboard Development • Data Cleaning & Transformation • DAX Measures • KPI Development • Data Visualization • Business Intelligence • Exploratory Data Analysis • Business Performance Analysis • Problem-Solving

## 📁 Repository Structure

```
DVM-CAR/
├── DVM-CAR.pbix        # Power BI dashboard file
├── data/               # Source dataset (Excel/CSV)
├── images/             # Dashboard screenshots
└── README.md
```

## 🚀 How to Explore the Project

1. **Quick view:** open the [live dashboard]([YOUR_POWER_BI_PUBLISH_TO_WEB_LINK]).
2. **Full access:**
   - Clone or download this repository
   - Open the `.pbix` file in **Power BI Desktop**
   - Explore the four pages and use the filters to analyze different dimensions

## 👨‍💻 Project Information

- **Project Name:** DVM-CAR – Automotive Sales & Performance Dashboard
- **Domain:** Automotive | Sales Analytics | Business Intelligence
- **Type:** Data Analytics & Business Intelligence

## 📬 Connect With Me

**[Harsh Garg]**
🔗 [LinkedIn]([https://www.linkedin.com/in/harsh-garg-161878291?utm_source=share_via&utm_content=profile&utm_medium=member_android])  • ✉️ [harshgarg5010@gmail.com]

<p align="center"><i>Turning Data into Decisions. Driving Insights through Analytics. 🚗</i></p>
