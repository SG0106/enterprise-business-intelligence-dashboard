# 📌 Business Rules & KPI Definitions

## 🧠 Overview

This section defines the business logic and assumptions used to calculate key metrics across the Enterprise BI 360 dashboard. These rules ensure consistency in reporting across all departments.

---

## 💰 Revenue Logic

- Net Sales = Gross Sales - Discounts
- All revenue figures are reported in local currency
- Returns (if any) are excluded from Net Sales

---

## 📊 Profitability Logic

- Gross Margin = Net Sales - Cost of Goods Sold (COGS)
- Gross Margin % = (Gross Margin / Net Sales) * 100
- Net Profit includes operational adjustments where applicable

---

## 📈 Time Intelligence Rules

- Year-over-Year (YoY) comparisons are based on full calendar year alignment
- Month-over-Month (MoM) uses same hierarchy level granularity
- YTD calculations reset at the start of each fiscal year

---

## 🎯 Target vs Actual Logic

- Targets are defined at monthly and regional levels
- Variance = Actual - Target
- Achievement % = (Actual / Target) * 100

---

## ⚙️ Data Assumptions

- Data is assumed to be cleaned and validated before loading into Power BI
- Missing values are treated as zero in calculations
- All measures follow consistent filtering logic across dimensions

---

## 📌 Purpose

These rules ensure that all dashboards reflect **consistent, reliable, and business-aligned metrics** across Finance, Sales, Marketing, and Executive reporting views.
