# 💻 Laptop Price & Feature Analysis Dashboard

An end-to-end data analytics project combining **Python** for data preprocessing and **Power BI** for interactive business intelligence — helping users understand how laptop specifications influence pricing and identify the best value-for-money options.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![PowerBI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-000000?style=for-the-badge&logo=microsoft&logoColor=white)

📂 **[View Full Project / Dashboard File (Google Drive)](https://drive.google.com/file/d/1nd9sRo2ffCOTqClwQ5lWDlxwzkLTmtGF/view?usp=sharing)**

---

## 📌 Project Summary

The **Laptop Price & Feature Analysis Dashboard** is an end-to-end data analytics project that transforms raw laptop listing data into actionable insights. Using Python for cleaning and feature engineering, and Power BI for interactive visualization, the dashboard helps users explore how specifications like RAM, storage, processor, and GPU influence laptop pricing — without having to manually sift through hundreds of listings.

## 🎯 Purpose of the Project

This project answers key questions such as:

- Which laptop brands offer the best value?
- How much does RAM affect price?
- Is SSD storage worth the additional cost?
- Which processor generation provides the best price-to-performance ratio?
- Which configurations are most suitable for students or professionals?

## ❗ Problem Statement

Laptop buyers often face challenges because:

- There are many brands and configurations to compare.
- Prices vary widely even for similar specifications.
- Raw datasets are difficult to interpret without analysis.
- Choosing the best laptop within a budget requires comparing multiple factors at once.

This dashboard transforms raw laptop data into clear, actionable insights.

## 👥 Target Users

| | | |
|---|---|---|
| 🎓 Students | 💼 Professionals | 🎮 Gamers |
| 🖥️ IT Procurement Teams | 🏪 Electronics Retailers | 📝 Laptop Reviewers |
| 🛒 E-commerce Analysts | 📊 Business Analysts | 📈 Data Analysts |

## 🔄 Workflow

```
Laptop Dataset
      │
      ▼
Python (Pandas & NumPy)
      │
      ▼
Data Cleaning
      │
      ▼
Feature Engineering
      │
      ▼
Export Clean Dataset
      │
      ▼
Power BI
      │
      ▼
Data Modeling
      │
      ▼
DAX Measures
      │
      ▼
Interactive Dashboard
      │
      ▼
Business Insights
```

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **Python** | Data preprocessing and feature engineering |
| **Pandas** | Data manipulation and cleaning |
| **NumPy** | Numerical operations |
| **Power BI** | Dashboard creation |
| **Power Query** | Data import and transformation |
| **DAX** | KPI calculations and dynamic measures |
| **Data Visualization** | Interactive charts and reports |
| **Business Intelligence** | Decision support and insights |

## 🧹 Data Cleaning

**Missing Values**
- Removed incomplete records where appropriate
- Filled missing values using suitable strategies
- Ensured overall data consistency

**Inconsistent Values**
- Corrected brand naming inconsistencies
- Fixed price formatting issues
- Standardized storage notation
- Resolved processor naming variations

**Standardization**
- Currency symbols
- Price values
- RAM units
- Storage units
- Screen sizes

## ⚙️ Feature Engineering

**Storage Type**
Derived from raw storage information into `SSD`, `HDD`, or `Hybrid` — used to compare pricing differences based on storage technology.

**RAM Categories**
Converted raw RAM values into grouped categories (`4 GB`, `8 GB`, `16 GB`, `32 GB+`) to enable grouped analysis and filtering.

**Price per GB**
```
Price per GB = Laptop Price / Storage Capacity
```
Used to evaluate storage value across laptops.

**Performance Segments**
Created `Budget`, `Mid-range`, and `Premium` categories to simplify product segmentation and comparison.

## 📊 Dashboard Pages

### 1️⃣ Overview Dashboard

- **KPI Cards** — Average laptop price, total laptop models, most popular brand
- **Brand-wise Price Comparison** — Bar charts comparing average price by brand and premium vs. budget positioning
- **SSD vs HDD Distribution** — Shows SSD laptops dominate the market and generally command higher prices
- **Top Value-for-Money Models** — Ranks laptops based on pricing relative to specifications, useful for students, budget-conscious buyers, and procurement teams

### 2️⃣ Feature Impact Analysis

- **RAM vs Price** — Scatter plot showing higher RAM generally correlates with higher prices, with outliers highlighting exceptional value or poor deals
- **Storage vs Price** — Analyzes the relationship between capacity, storage technology, and pricing
- **Processor Impact** — Compares Intel Core i3/i5/i7/i9 and AMD Ryzen 3/5/7/9 to determine how processor choice affects pricing
- **GPU Analysis** — Evaluates integrated vs. dedicated graphics, useful for gamers, designers, and video editors

## 🎛️ Interactive Features

- Filter by brand
- Filter by RAM
- Filter by storage
- Compare configurations side-by-side
- Drill down into specific segments

## 📐 DAX Measures

Dynamic DAX measures power the premium/budget segmentation and update automatically based on slicer selections:

- Average Price
- Total Models
- Premium Model Count
- Budget Model Count
- Average Price by Brand
- SSD Percentage
- Price per GB
- Average RAM
- Average Storage
- Brand Market Share

## 📈 Business Insights

- SSD-equipped laptops typically have higher prices than HDD models.
- RAM capacity and processor generation are the strongest pricing factors.
- Some brands offer better price-to-performance value than others.
- Mid-range laptops often provide the best balance of performance and cost for students and professionals.

## 🌍 Real-World Applications

- E-commerce pricing analysis
- Inventory planning
- Product benchmarking
- Consumer buying guides
- Retail sales strategy
- Competitive analysis
- Procurement decision-making

## 💼 Skills Demonstrated

**Programming:** Python, Pandas, NumPy

**Data Analytics:** Data cleaning, data preprocessing, feature engineering, exploratory data analysis (EDA)

**Business Intelligence:** Power BI, DAX, KPI design, interactive dashboards, data visualization

**Analytical Thinking:** Trend analysis, pricing analysis, comparative analysis, business storytelling

## 🤝 Connect With Me

**Sahil Sathe**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sahil-sathe)

📎 LinkedIn: [www.linkedin.com/in/sahil-sathe](https://www.linkedin.com/in/sahil-sathe)

---

⭐ If you found this project useful, consider giving it a star on GitHub!
