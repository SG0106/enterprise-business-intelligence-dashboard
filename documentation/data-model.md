# 🗂 Data Model Overview

## 🧠 Purpose

The data model is designed to support an enterprise-level Business Intelligence solution that enables reporting across Finance, Sales, Marketing, Supply Chain, and Executive domains.

It is built to ensure consistency, scalability, and high performance across all Power BI reports.

---

## 📊 Model Architecture

The model follows a **Star Schema design**, which includes:

### 🔷 Fact Table
- Fact Sales  
  Contains transactional-level data used for all KPI calculations such as revenue, profit, and performance metrics.

### 🔶 Dimension Tables
- Dim Customer  
- Dim Product  
- Dim Date  
- Dim Region / Market  

These tables provide descriptive attributes used for filtering, slicing, and grouping data.

---

## 🔗 Relationship Design

- Relationships are primarily **one-to-many (1:*)**
- Filter direction flows from **Dimension → Fact**
- A centralized fact table ensures a clean and efficient model structure
- Avoids many-to-many complexity for better performance

---

## ⚙️ Key Design Decisions

- Star schema used to optimize query performance and simplify DAX logic  
- Date table used for time intelligence calculations  
- Separate dimension tables ensure reusability across multiple business views  
- Model designed to support multiple dashboards from a single dataset  

---

## 📌 Business Impact

This data model enables:

- Fast and responsive dashboard performance  
- Consistent KPI calculations across all report pages  
- Scalable architecture for future business expansion  
- Simplified DAX development and maintenance  
