# Sales & Customer Intelligence Dashboard

> A comprehensive Power BI project providing data-driven insights into Sales, Returns, Customer Behavior, and Regional Performance

---

## 📋 Project Overview

This project delivers a **Final Power BI Report** designed for senior leadership teams to analyze key business metrics across sales performance, customer behavior patterns, and regional trends over a three-year period. The dashboard combines industry best practices in **data modeling** with advanced **DAX calculations** to provide an interactive, mobile-friendly reporting solution.

**Project Name:** Final Project – Sales & Customer Intelligence Dashboard  
**Created:** June 2025  
**Sponsor:** Business Analyst Manager | InsightPro Analytics Pvt Ltd

---

## 🎯 Project Objectives

1. **Build a robust data model** with star schema architecture
2. **Implement advanced DAX formulas** and calculation patterns for comprehensive KPI analysis
3. **Apply Time Intelligence** techniques with filtering and formatting capabilities
4. **Create a fully interactive multi-page** Power BI report with drill-through capabilities
5. **Ensure mobile compatibility** and provide an enhanced user experience across devices

---

## 📊 Dataset Structure

### Dimension Tables
- **Date_Dim** – Temporal data for time-based analysis (YOY, MOM, YTD)
- **Customer_Dim** – Customer attributes and segmentation
- **Product_Dim** – Product catalog and categorization
- **Region_Dim** – Geographic and regional hierarchies

### Fact Tables
- **Sales_Fact** – Transaction-level sales data with revenue metrics
- **Returns_Fact** – Return transactions and return analytics

---

## ✨ Key Features & Deliverables

### Data Modeling
- ✅ Star schema with primary and foreign key relationships
- ✅ Clean data with hidden unnecessary fields
- ✅ Consistent naming conventions and best practices

### DAX Measures & Calculated Columns
- **Measures:** `CALCULATE`, `FILTER`, `ALL`, `SUMX`, `COUNTX`, `AVERAGEX`
- **Advanced Functions:** `SWITCH` for KPI classification, `RELATED` for dimension joins
- **Calculated Columns:**
  - Profit margin classification
  - Customer full names (First + Last)
  - Year-Month formatting

### Time Intelligence
- Year-over-Year (YOY) comparisons
- Month-over-Month (MOM) analysis
- Year-to-Date (YTD) tracking
- Seasonal trend identification

### Dashboard Layout
- **1 Main Dashboard** with executive KPIs
- **2 Detailed Analysis Pages** with drill-down capabilities
- **1 Drill-Through Page** for granular exploration
- **Cards, KPI Cards, Line Charts, Bar & Donut Charts**
- **Trend lines and forecasts** for sales projections
- **Matrix visuals** with conditional formatting
- **Top N Products by Sales** and **Top N Customers by Revenue**

### Interactive Features
- **Slicers:** Product, Customer Segment, Region, Date filters
- **Drill Up/Down** and **Drill-Through filters**
- **Numeric Range Parameters** for custom filtering
- **Custom Buttons & Bookmarks** for seamless page navigation
- **Collapsible Slicer Panel** for optimized space usage
- **Tooltips** with KPI summaries and visual context
- **Advanced Conditional Formatting** in matrix/table views

### Mobile Optimization
- Responsive layout for mobile devices
- Prioritized KPI Cards and Top N visuals
- Touch-friendly navigation controls

### Security
- **Row-Level Security (RLS)** for Region Managers
- Simulated RLS for regional data access control

---

## 📁 Project Structure

```
MS_Power_BI_PR.-Final-Project/
├── README.md                    # Project documentation
├── index.html                   # Embedded Power BI report viewer
└── Data/
    └── img/                     # Supporting images and assets
```

---

## 🚀 Quick Start

### Viewing the Report
1. Open [Sales & Customer Performance Dashboard](https://prath-digital.github.io/MS_Power_BI_PR.-Final-Project/) in a web browser
2. The embedded Power BI report will load automatically
3. Interact with slicers, filters, and drill-through features
4. Switch between pages using navigation buttons

### If Report Doesn't Load
- Click the **"Open in Power BI"** button to access the live report
- Ensure you have access to the Power BI workspace
- Check your internet connection

---

## 📈 Dashboard Pages

| Page | Purpose | Key Visuals |
|------|---------|------------|
| **Executive Summary** | High-level KPIs and metrics | KPI Cards, Trend Charts, Regional Breakdown |
| **Sales Analysis** | Deep dive into sales performance | Line Charts, Bar Charts, Matrix Tables, Top Products |
| **Customer Insights** | Customer behavior and segmentation | Customer Metrics, Segment Analysis, RFM Analysis |
| **Drill-Through** | Granular product/customer details | Detailed records, filtered context |

---

## 🛠️ Technical Stack

- **Power BI Desktop** – Report development
- **DAX (Data Analysis Expressions)** – Calculated measures and columns
- **Star Schema** – Optimized data modeling architecture
- **HTML/CSS** – Web-based report embedding

---

## 📋 Data Requirements

The project expects datasets in Excel format with the following tables:
- Date_Dim
- Customer_Dim
- Product_Dim
- Sales_Fact
- Returns_Fact
- Region_Dim

---

## 🔒 Security & Access Control

- Row-Level Security (RLS) roles for Region Managers
- Data filtering based on user's assigned region
- Simulated security model for demonstration purposes

---

## 📦 Deliverables Checklist

- ✅ Power BI Report (.pbix file)
- ✅ Mobile Layout Preview
- ✅ Documented DAX measures and visuals
- ✅ Web-based embedded viewer (index.html)
- ⏳ Final walkthrough video/demo (optional)

---

## 👥 Project Team

**Business Analyst Manager:** Ananya Mehta  
**Organization:** InsightPro Analytics Pvt Ltd  
**Developer:** Power BI Developer (You)

---

## 📝 Notes

- All data imports should follow the star schema structure
- Ensure proper relationship configuration in Power BI
- Test RLS roles with sample user accounts before deployment
- Validate all DAX calculations against business requirements

---

## 📞 Support & Questions

For issues or questions regarding the dashboard:
1. Review the DAX documentation in the Power BI file
2. Check mobile layout compatibility in Power BI settings
3. Validate data model relationships and cardinality

---

**Last Updated:** December 2025  
**Status:** Active Development  
**Repository:** [Prath-Digital/MS_Power_BI_PR.-Final-Project](https://github.com/Prath-Digital/MS_Power_BI_PR.-Final-Project)
