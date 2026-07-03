# 🗂 Data Model Overview

## 🧠 Overview

The data model in this Enterprise BI 360 solution is designed using a **Star Schema architecture**, ensuring optimized performance, scalability, and consistent KPI calculations across all report pages.

---

## 📊 Model Structure

### Fact Table
- Fact Sales (core transactional data)

---

### Dimension Tables
- Dim Customer
- Dim Product
- Dim Date
- Dim Market / Region

---

## 🔗 Relationships Design

- One-to-many relationships between Dimension and Fact tables
- Single-direction filtering from Dimensions → Fact
- Centralized fact table ensures consistent KPI calculations across dashboards

---

## ⚙️ Design Principles

- Optimized for performance in Power BI
- Reduced model complexity for faster query execution
- Reusable across multiple business domains (Finance, Sales, Marketing, Supply Chain)
- Supports scalable reporting structure

---

## 📌 Business Value of This Model

This data model enables:

- Fast and responsive dashboard performance
- Consistent KPI definitions across departments
- Simplified DAX calculations
- Scalable enterprise reporting structure
