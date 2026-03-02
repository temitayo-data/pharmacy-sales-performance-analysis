# Pharmacy Sales Performance Analysis

## Project Overview

This project presents an end-to-end Business Intelligence analysis of pharmacy sales data using Power BI. The objective was to evaluate revenue growth, profitability, geographic contribution, product performance, and promotion effectiveness across multiple business dimensions.

The dashboard is structured into two core sections:
- Executive Overview
- Performance & Operational Analysis

---

## Data Model

The analysis is built using a star schema model:

- **Fact Table:** Sales transactions (Revenue, Cost, Margin, Units Sold, Promotion Flag)
- **Dimension Tables:**
  - Date
  - Pharmacy (Country, Region, Type)
  - Product (Category, Brand)

Key measures were created using DAX for revenue, profit, growth rate, and performance contribution analysis.

---

## Executive Insights

### 1. Business Growth & Monthly Trends

- Total Revenue: **$8.63M**
- 2025 Revenue: **$4.41M**
- Previous Year Revenue: **$4.22M**
- Year-over-Year Growth: **4.43%**

Revenue, profit, and units sold fluctuate monthly but move consistently together, indicating stable margin performance and healthy operational structure. December shows stronger year-end performance compared to January.

---

### 2. Geographic Performance

- **Germany** leads in both revenue ($1.57M) and profit ($439K).
- **Austria** ranks lowest in revenue ($0.68M) and profit ($192K).
- Revenue and profitability are concentrated in stronger markets, with noticeable performance gaps between countries.

---

### 3. Pharmacy Type Performance

- **Urban pharmacies dominate performance**, generating $1.15M in profit and 212K units sold.
- Urban locations lead in both current and previous year revenue.
- Urban stores act as primary growth drivers for the business.

---

## Product Portfolio Insights

### 4. Category Performance

- **Prescription category leads revenue and profit** ($2.8M revenue, $613K profit).
- OTC and Personal Care categories fall into high-volume, high-profit segments.
- Prescription products generate strong margins but at lower volume levels.
- Medical Devices show low volume and low profitability, indicating potential review opportunity.

---

## Promotion Effectiveness

- Non-promoted products generate significantly higher profit ($2.24M) and volume (394K units).
- Promoted products contribute limited profit ($0.18M) and lower volume (52K units).
- Promotions currently show weak return on margin and may require strategic reassessment.

---

## Operational Performance Observations

- Revenue and profit alignment suggests stable cost control.
- Growth is driven primarily by Urban locations and strong-performing markets.
- Product profitability varies significantly across categories, indicating the need for portfolio balancing.

---

## Strategic Recommendations

1. Prioritize expansion and investment in Urban pharmacies.
2. Strengthen presence in high-performing markets such as Germany.
3. Optimize product mix by focusing on high-volume, high-margin categories (OTC & Personal Care).
4. Re-evaluate promotional strategies to ensure profitability protection.
5. Review underperforming product categories (e.g., Medical Devices) for cost optimization or repositioning.

---

## Tools Used

- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query
- Star Schema Data Modeling

---

## Author

Temitayo  
Business Intelligence & Data Analytics Portfolio Project
