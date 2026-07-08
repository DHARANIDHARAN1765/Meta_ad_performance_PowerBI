# 📊 Meta Ad Performance Analysis Dashboard

> **An end-to-end Power BI dashboard that analyzes Meta (Facebook & Instagram) advertising performance using campaign, ad, audience, and event-level data to measure ROI, optimize budget allocation, and improve marketing decisions.**

---

# 📖 Project Overview

The **Meta Ad Performance Analysis Dashboard** is a Business Intelligence project developed using **Power BI** to monitor and evaluate advertising campaigns running on **Facebook and Instagram**.

The dashboard provides a complete marketing funnel analysis, starting from **Impressions → Clicks → Engagements → Purchases**, helping marketing teams understand campaign performance, audience behavior, conversion efficiency, and budget utilization.

The project enables business users to identify high-performing campaigns, optimize advertising spend, understand customer demographics, analyze geographic trends, and improve Return on Investment (ROI) through data-driven decision making.

---

# 🎯 Business Objective

The objective of this project is to help the marketing team answer critical business questions such as:

- Which campaigns generate the highest engagement?
- Which ad formats deliver the best ROI?
- Which audience segments convert the most?
- Which countries perform better?
- When should ads be displayed?
- How effectively is the advertising budget being utilized?

---

# 📌 Business Requirements

The dashboard was designed based on the following business requirements:

- Monitor campaign performance across Facebook and Instagram
- Track complete marketing funnel performance
- Compare campaign reach and conversions
- Measure advertising effectiveness using KPIs
- Analyze customer demographics
- Analyze country-wise engagement
- Evaluate ad format performance
- Optimize advertising budget
- Identify the best-performing time for advertisements

---

# 🛠️ Technology Stack

- Power BI Desktop
- Power Query
- DAX
- Data Modeling
- Star Schema
- Microsoft Excel

---

# 📂 Dataset Overview

The project uses four interconnected datasets representing Meta advertising data.

| Table | Description |
|--------|-------------|
| **ad_events** | Stores every impression, click, share, comment and purchase event |
| **ads** | Contains ad creative details, targeting information and ad formats |
| **campaigns** | Stores campaign budgets and campaign details |
| **users** | Contains demographic and geographic information |

---

# ⭐ Data Model

The dashboard follows a **Star Schema**.

### Fact Table

- ad_events

### Dimension Tables

- ads
- campaigns
- users
- Date Table

This model improves query performance and simplifies report development.

---

# 📊 KPIs Created

The dashboard includes the following business KPIs:

- Impressions
- Clicks
- Shares
- Comments
- Purchases
- Engagements
- CTR (Click Through Rate)
- Engagement Rate
- Conversion Rate
- Purchase Rate
- Total Budget
- Average Budget per Campaign

---

# 📈 KPI Formulas

### Click Through Rate (CTR)

CTR = (Clicks / Impressions) × 100

---

### Engagement Rate

Engagement Rate = (Engagements / Impressions) × 100

---

### Conversion Rate

Conversion Rate = (Purchases / Clicks) × 100

---

### Purchase Rate

Purchase Rate = (Purchases / Impressions) × 100

---

# 📊 Dashboard Pages

## 1️⃣ Executive Overview

Provides a high-level summary of advertising performance.

Includes:

- Total Impressions
- Clicks
- Purchases
- Engagements
- Total Budget
- CTR
- Engagement Rate
- Conversion Rate
- Purchase Rate

---

## 2️⃣ Audience Analysis

Analyzes customer engagement by

- Gender
- Age Group

Helps marketers identify the highest-performing audience segments.

---

## 3️⃣ Geographic Analysis

Displays campaign performance by country using an interactive map.

Countries include

- India
- United States
- Brazil
- Germany
- United Kingdom

---

## 4️⃣ Time Analysis

Shows

- Weekly Engagement Trends
- Hourly Engagement Trends
- Calendar Heat Map

Used to determine the best time to run advertisements.

---

## 5️⃣ Ad Performance Analysis

Compares different ad formats.

Includes

- Video Ads
- Stories
- Image Ads
- Carousel Ads

Helps identify the highest ROI ad format.

---

# 📊 Dashboard Visualizations

The report contains

- KPI Cards
- Donut Chart
- Clustered Bar Chart
- Map Visual
- Calendar Heat Map
- Stacked Column Chart
- Area Chart
- Matrix Visual
- Slicers
- Interactive Filters

---

# 📈 Key Insights

### Awareness Stage

- 216K Impressions
- Strong campaign reach

---

### Engagement Stage

- 25.4K Clicks
- 29K Total Engagements
- CTR = 11.76%
- Engagement Rate = 13.56%

These metrics indicate highly engaging ad creatives and effective audience targeting.

---

### Conversion Stage

- 1.3K Purchases
- Conversion Rate = 5.21%
- Purchase Rate = 0.61%

Although engagement is high, the purchase funnel shows a significant drop-off, indicating opportunities for optimization.

---

### Audience Insights

- Females generate the highest engagement.
- Users aged 18–30 are the most active audience.

---

### Geographic Insights

Highest engagement comes from

- India
- United States
- Brazil

Higher purchasing potential observed in

- Germany
- United Kingdom

---

### Time Insights

Highest engagement occurs during

- Afternoon
- Evening

Campaign performance peaks during promotional periods.

---

### Ad Format Insights

Performance Ranking

1. Video Ads
2. Stories
3. Carousel Ads
4. Image Ads

Video ads achieved the highest engagement and conversion efficiency.

---

# 💡 Business Recommendations

Based on dashboard insights:

- Improve landing page experience.
- Strengthen retargeting campaigns.
- Increase investment in Video and Stories advertisements.
- Schedule campaigns during afternoon and evening hours.
- Focus high-volume campaigns on India and Brazil.
- Run premium campaigns for Germany and the UK.
- Optimize offers and checkout experience to improve purchase rate.

---

# 📂 Repository Structure

```
Meta-Ad-Performance-Analysis/
│
├── Dataset/
│   ├── ad_events.csv
│   ├── ads.csv
│   ├── campaigns.csv
│   └── users.csv
│
├── PowerBI/
│   └── Meta_Ad_Performance.pbix
│
├── Images/
│   ├── Dashboard.png
│   ├── Audience.png
│   ├── Geography.png
│   ├── TimeAnalysis.png
│   └── AdPerformance.png
│
├── README.md
│
└── LICENSE
```

---


# 🚀 Business Impact

This dashboard transforms raw Meta advertising data into actionable business insights, enabling marketing teams to monitor campaign performance, optimize budget allocation, improve audience targeting, and increase return on investment through data-driven decision-making.

---



⭐ **If you found this project useful, please consider giving it a Star!**
