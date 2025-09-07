# 📊 Marketing Campaign Dashboard (Power BI)

## 📌 Project Overview
This project is a **Power BI Dashboard** built to analyze and visualize customer marketing data.  
It helps uncover insights about customer demographics, spending behavior, product preferences, and campaign performance.  

The dashboard provides **decision-making support** for marketing teams by showing which campaigns performed best, which products drive revenue, and how different customer groups behave.  

---

## 🔎 Dataset
The dashboard is built using a marketing dataset that includes:
- **Customer Demographics**: Age, Marital Status, Education, Income
- **Spending Behavior**: Amount spent on Wines, Fruits, Meat, Fish, Sweet Products, Gold
- **Campaign Performance**: Accepted Campaigns (1–5) and Response
- **Customer Engagement**: Website visits, purchases, complaints

---

## 📊 Dashboard Pages

### 🔹 Page 1: Customer Overview
- KPI Cards → Total Customers, Average Age, Average Spending, Average Tenure
- Charts:
  - Age Distribution (Histogram)
  - Marital Status Breakdown
  - Education Level Distribution

### 🔹 Page 2: Spending Analysis
- KPI Cards → Sum of Total Spendings, Average of Total Spendings, High Spenders
- Charts:
  - Spending by Product Category (Bar/Column Chart)
  - Income vs Spending (Scatter Plot)
  - Distribution of Spending Categories
  - Age Group(Slicer)

### 🔹 Page 3: Campaign Performance
- KPI Cards → Total Accepted Campaigns, Average Income
- Charts:
  - Pie Chart → Accepted Campaigns 
  - Pie Chart → Number of Purchases
 
### Page 4: Customer Segmentation
- Charts:
  - Line Chart → Sum of Age and Total spending by Marital Status
  - Tree Map → Count of ID Age Group and Education
  - Matrix → Marital Status, Age Group

---

## 🚀 Features
- **Interactive slicers** for filtering by product category, education, marital status, and campaign.
- **Dynamic KPI cards** to track high spenders, campaign response, and total revenue.
- **User-friendly visuals** for quick insights.

---

## 🛠️ Tools & Technologies
- **Power BI Desktop**
- **DAX** (for KPIs and calculated measures)
- **Data Cleaning** (Power Query)


---

## 📥 How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/marketing-dashboard.git
