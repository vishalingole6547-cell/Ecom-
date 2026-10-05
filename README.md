# 🛒 E-Commerce Sales & Profit Analysis – Power BI Dashboard

## 📊 Project Overview

This project is an **E-Commerce Sales & Profit Analysis Dashboard** built using **Microsoft Power BI**.

The dashboard provides an interactive view of **sales, profit, orders, customers, regional performance, product-category performance, and shipping efficiency**. It is designed to help identify major profit drivers, understand regional performance, and highlight areas where shipping costs may be affecting profitability.

The dashboard reports approximately **$2M in total sales, $801K in profit, 11K orders, and 4K customers**.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Analyze overall **sales and profit performance**
- Identify the strongest and weakest **product categories**
- Compare performance across different **regions and states**
- Analyze **order and customer volume**
- Evaluate **shipping costs and shipping efficiency**
- Identify categories contributing significantly to profit
- Understand the impact of shipping costs on profitability
- Provide actionable business insights through interactive Power BI visuals

---

## ❓ Business Questions

This dashboard answers the following business questions:

1. What are the total sales and total profit?
2. How many orders and customers does the business have?
3. Which product categories generate the highest sales?
4. Which categories generate the highest profit?
5. Which regions contribute the most sales and profit?
6. Which states are the major contributors to regional performance?
7. What is the shipping cost percentage?
8. What is the average shipping cost per order?
9. Which categories have the highest shipping cost per unit?
10. How does shipping cost affect profit after shipping?
11. Which markets or categories require further investigation?
12. Where can the business improve profitability?

---

## 📌 Key Performance Indicators (KPIs)

| KPI | Value |
|---|---:|
| 💰 Total Sales | **$2M** |
| 📈 Total Profit | **$801K** |
| 🛍️ Total Orders | **11K** |
| 👥 Total Customers | **4K** |
| 🚚 Shipping Cost % | **30.42%** |
| 📦 Shipping Cost per Order | **$40.7+** |
| 💵 Profit After Shipping | **$335.8K** |
| 📦 Shipping Cost per Unit | **$6.23+** |

The dashboard's shipping page specifically reports a **30.42% shipping cost percentage** and approximately **$335.8K profit after shipping**.

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI Desktop**
- Power Query
- Data Transformation
- Data Modeling
- DAX
- Interactive Slicers
- KPI Cards
- Bar/Column Charts
- Map Visualizations
- Tables & Matrix Visuals
- Dashboard Navigation

---

## 📊 Dashboard Pages

### 1. 🏠 E-Commerce Overview

The main dashboard provides an overview of:

- Total Sales
- Total Profit
- Total Orders
- Total Customers
- Sales by Category
- Profit by Category
- Region filter
- Category filter

The category analysis covers:

- Food
- Disposables
- Grooming
- Electronics
- Supplements
- Pet Food
- Cleaning Supplies



---

### 2. 🌎 Regional Analysis

The Regional Analysis page evaluates sales, profit, and orders across regions and states.

Regional performance shown in the dashboard includes:

| Region | Sales | Profit | Orders |
|---|---:|---:|---:|
| Central | $377,403 | $176,625 | 3,450 |
| East | $533,429 | $266,602 | 4,480 |
| Other | $4,604 | $2,328 | 54 |
| West | $615,590 | $355,916 | 3,447 |

The report also provides state-level performance, including California, Nevada, Washington, Arizona, Oregon, New Mexico, Utah, Idaho, Montana, and Wyoming.

---

### 3. 🚚 Shipping Analysis

The Shipping Analysis page focuses on shipping efficiency and its impact on profitability.

Key metrics include:

- Shipping Cost %
- Shipping Cost per Order
- Profit After Shipping
- Shipping Cost per Unit
- Total Quantity
- Shipping Cost by Category
- Shipping Cost per Unit by Category

The dashboard shows shipping cost per unit varying across categories, with Supplements and Food among the higher-cost categories displayed.

---

### 4. 💡 Business Insights

The dashboard identifies several important business insights.

#### Overall Performance

Sales and profit are concentrated in certain categories. **Food and Disposables** contribute strongly to both sales and profit, while several smaller categories contribute substantially less.

#### Regional Performance

The report highlights **East** as a strong region across sales, profit, and orders, with **Central** also making a substantial contribution. The **Other** region has unusually low values and requires further review.

#### Shipping Efficiency

The dashboard highlights high shipping costs as a potential factor reducing profitability, particularly in categories with high shipment volume. **Food and Supplements** are identified for further review regarding packaging and shipping efficiency.

---

## 🔍 Key Takeaways

- Focus on **profitable growth**
- Monitor regional concentration
- Review weaker markets
- Investigate high shipping costs
- Analyze high-cost categories
- Improve shipping and packaging efficiency
- Monitor dependency on major regions and categories

The dashboard's stated takeaway is to focus on **profitable growth, regional balance, and shipping efficiency**.

---

## 📈 Profit Contribution by Category

The report shows the following profit contribution:

| Category | Profit |
|---|---:|
| Food | $102,212 |
| Disposables | $85,649 |
| Grooming | $52,561 |
| Pet Food | $22,576 |
| Supplements | $19,411 |
| Electronics | $16,258 |
| Cleaning Supplies | $12,256 |



---

## 🗺️ Geographic Analysis

The dashboard provides state-level profit information. California is a major contributor in the displayed data, followed by states such as Nevada, Washington, Arizona, Oregon, and New Mexico.

---

## 🎨 Dashboard Features

### Interactive Filters

Users can filter the dashboard using:

- **Region**
- **Category**
- Clear All Slicers option

### Visualizations

The dashboard includes:

- KPI Cards
- Category Sales Charts
- Category Profit Charts
- Regional Map
- Regional Performance Table
- Shipping Cost Analysis
- Category-level Shipping Analysis
- State-level Profit Analysis

---

## 🔄 Project Workflow

```text
Raw E-Commerce Data
        ↓
Data Cleaning & Transformation
        ↓
Power Query
        ↓
Data Model
        ↓
DAX Calculations
        ↓
Power BI Visualizations
        ↓
Interactive Dashboard
        ↓
Business Insights
```

---

## 📁 Repository Structure

```text
E-Commerce-PowerBI-Analysis/
│
├── README.md
│
├── PowerBI/
│   └── E-Commerce_Analysis.pbix
│
├── Dataset/
│   └── ecommerce_data.xlsx
│
├── Screenshots/
│   ├── dashboard_overview.png
│   ├── regional_analysis.png
│   ├── shipping_analysis.png
│   └── business_insights.png
│
└── Documentation/
    └── ecom_pbi.pdf
```

---

## 📸 Dashboard Preview

Add your dashboard screenshots to the `Screenshots` folder and display them in GitHub using:

```markdown
## Dashboard Preview

![E-Commerce Dashboard](Screenshots/dashboard_overview.png)

![Regional Analysis](Screenshots/regional_analysis.png)

![Shipping Analysis](Screenshots/shipping_analysis.png)

![Business Insights](Screenshots/business_insights.png)
```

---

## 💼 Business Value

This Power BI dashboard converts e-commerce data into an interactive analytical solution that can support:

- Sales performance monitoring
- Profitability analysis
- Regional decision-making
- Product-category analysis
- Shipping cost optimization
- Identification of weaker markets
- Identification of major profit contributors

---

## 🚀 Future Improvements

Potential future enhancements include:

- Monthly and yearly sales trends
- Year-over-year growth analysis
- Customer segmentation
- Product-level profitability
- Profit margin analysis
- Shipping cost optimization analysis
- Top and bottom-performing products
- Customer retention analysis
- Sales forecasting
- Automated Power BI refresh

---

## 👨‍💻 Project Type

**Business Intelligence | Data Analytics | Power BI | E-Commerce Analytics**

---

## ⭐ Conclusion

This project demonstrates how **Power BI, data modeling, interactive visualizations, and business analysis** can be combined to understand e-commerce performance.

The dashboard provides a consolidated view of **sales, profit, orders, customers, regional performance, category performance, and shipping efficiency**, allowing business users to identify important performance areas and opportunities for improvement.
