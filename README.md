# Nykaa Marketing Campaign Performance Analysis & ROI Optimization (2024-2025)

## 📌 Project Overview & Problem Statement
In a highly competitive e-commerce landscape, maximizing the efficiency of marketing spend is crucial for sustainable growth. This project analyzes a comprehensive marketing dataset modeled after **Nykaa’s** digital ecosystem spanning 2024-2025. 

The objective is to evaluate marketing campaign performance, track customer acquisition across multiple digital channels, and optimize the Return on Investment (ROI). By processing a massive scale of data (**5 Billion Impressions and 79 Million Conversions**), this project provides data-driven strategies for budget reallocation and audience targeting.

---

## 🛠️ Tech Stack & Workflow Pipeline

### 1. Data Cleaning & Exploratory Data Analysis (EDA) — Python
Before building the dashboard, raw campaign logs were processed using Python (`Pandas`, `NumPy`, `Matplotlib/Seaborn`) to ensure data integrity and discover initial patterns:
* **Data Cleaning:** Addressed missing values, verified uniform text casing, and eliminated duplicate records.
* **Type Transformation:** Converted date formats into uniform datetime objects for proper time-series rendering. 
* **Feature Engineering:** Calculated explicit metrics such as total cost structures, granular conversion rates, and exact ROI values per campaign segment.
* **Statistical EDA:** Plotted distributions to identify performance anomalies, outliers, and baseline correlation matrices between spends and revenue.

### 2. Data Modeling & Visualization — Power BI
The cleaned data was imported into Power BI to create an executive-ready, interactive dashboard:
* **Data Modeling:** Established relationships between dimensional tables (Channels, Campaigns, Audiences) and the core Fact table.
* **DAX Formulas:** Developed custom measures for consistent KPI reporting (e.g., dynamic average ROI calculations and aggregated lead funnels).
* **UI/UX Design:** Implemented a clean, brand-aligned visual theme tailored to Nykaa's corporate identity, utilizing high-level KPI cards and modular navigation charts.

---

## 📊 Core Performance Metrics (Executive Summary)
* **Total Revenue:** ₹37 Billion (bn)
* **Total Marketing Spend (Cost):** ₹24.68 Million (M)
* **Average ROI:** 3.20K
* **Total Conversions:** 79 Million (M)
* **Total Leads Generated:** 148 Million (M)
* **Total Click-Throughs:** 388 Million (M)
* **Total Impressions:** 5 Billion (bn)

---

## 💡 Key Business Insights Discovered

### 1. Channel Performance Analysis
* **Conversion Consistency:** Total conversations are distributed remarkably evenly across digital touchpoints, with **YouTube (16.82%)**, **Email (16.71%)**, **Instagram (16.63%)**, and **Facebook (16.51%)** performing at neck-and-neck volume.
* **ROI Variance:** Despite equal conversion volumes, cost efficiencies vary. Marketing types like **Social Media** and **SEO** drive highly competitive ROI figures alongside standard **Email** campaigns.

### 2. Time-Series Trends & Seasonality
* **The June Dip:** A sharp contraction in revenue and total conversions is visible in June, dropping significantly below the yearly baseline. This marks a critical period where marketing engagement hits a cyclical lull.
* **Q4 Festive Surge:** Revenue and conversions experience an aggressive recovery starting in late Q3, peaking sustainably throughout Q4 (October–December). This aligns perfectly with cultural festive shopping seasons in India.

### 3. Audience Segmentation & Engagement
* **Target Segments:** Customer engagement scales equally across primary target groups, including **College Students, Premium Segments, Youth, and Working Professionals**, pointing to broad market penetration.
* **Engagement Threshold:** The overall marketing distribution maintains a healthy, consistent engagement score benchmark of **1.19M**.

---

## 📈 Strategic Recommendations
1. **Capitalize on Seasonality:** Aggressively scale up ad spend and run high-impact influencer campaigns leading into October to ride the Q4 wave. Conversely, minimize active spend in June; instead, focus on organic SEO maintenance during this low-conversion window.
2. **Reallocate Budget based on ROI:** Since Email and Social Media drive massive ROI relative to cost, shift capital away from underperforming static paid ads and reallocate toward highly targeted email workflows and automated WhatsApp customer interactions.

---

