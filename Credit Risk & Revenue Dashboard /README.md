# 💳 Credit Risk & Revenue Intelligence Dashboard

A comprehensive 3-page Power BI dashboard project that analyzes customer behavior, default risk, and revenue insights from a synthetic credit dataset. This project was built as part of my Power BI learning journey and focuses on real-world business intelligence use cases — from messy data cleaning to financial risk analysis.

---

## 📌 Project Objectives

- Clean and structure unorganized credit data (with missing, inconsistent, and unstandardized entries)
- Segment customers by age, income, loan type, and region
- Analyze credit default patterns and identify high-risk groups
- Explore revenue performance across customer segments
- Build interactive dashboards for business stakeholders

---

## 📊 Dashboard Pages & Features

### 🟢 1. Executive Overview

- ✅ Total Customers, Revenue, Avg Credit Score, Default Rate
- 📊 Pie chart: LoanType Distribution
- 📍 Bar chart: Revenue by Region

### 🔴 2. Credit Risk Analysis

- 📉 Funnel Chart: Application → Approval → Default journey
- 📊 Risk segmentation by Age Group and Income Group
- 🗺️ Region-wise default heatmap
- 🎯 Default rate KPIs with slicers for loan type & region

### 🔵 3. Revenue Intelligence

- 💰 Total & Average Revenue per customer (KPI Cards)
- 🧭 Revenue split by Default status
- 📍 Revenue share by LoanType
- 📈 Region-based revenue analysis
- 🔎 Filterable by AgeGroup, IncomeGroup, Region

---

## 🧽 Data Cleaning & Transformation Highlights

- Cleaned and replaced typos like `"Noth"` → `"North"` using Power Query
- Converted inconsistent loan types & default flags into proper categorical values
- Replaced nulls using domain-aware imputation (e.g., replacing revenue/score with group averages)
- Created custom segments:
  - `AgeGroup` (Young, Mid-age, Senior)
  - `IncomeGroup` (Low, Middle, High)
- Added calculated columns and DAX measures to enable risk and performance KPIs

---

## ⚙️ Tools Used

- **Power BI Desktop**
- **Power Query (M Language)** – for data cleaning and transformation
- **DAX** – for calculated measures, KPI logic, funnel visualization
- **GitHub** – project version control and portfolio showcase

---

## 💡 Key Insights

- Mid-age customers (25–44) had the **highest number of defaults**
- Regions like **North** and **East** showed higher default concentration
- **Auto loans** had a higher share of defaults than personal loans
- Revenue potential remained high even among segments with higher risk, indicating the need for **balanced risk-reward strategies**

---


## 🙋‍♀️ About Me

I'm a B.Tech Bioinformatics undergrad specializing in **AI-powered Data Analytics**. I’m on a mission to become a full-time Data Analyst and am actively learning by building impactful dashboards from real-world inspired datasets.

🔗 Portfolio: [Power BI Projects Repo](https://github.com/nikkiii23/powerbi-portfolio.git)
