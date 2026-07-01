# 🌸 Ferns and Petals: Retail Sales Performance Dashboard

✨ **Transforming 1,000+ transactional records into an interactive, decision-ready retail intelligence dashboard.**

This data analytics project processes raw e-commerce/retail data from an occasion-based gifting business, designs an interconnected relational data model, and builds dynamic visual insights tracking over **₹35.2L+** in revenue.

[![Excel](https://img.shields.io/badge/Tools-Microsoft_Excel-217346?style=flat&logo=microsoftexcel&logoColor=white)]()
[![Status](https://img.shields.io/badge/Status-Completed-success?style=flat)]()
[![Dataset Size](https://img.shields.io/badge/Dataset-1000+_Rows-blue?style=flat)]()

---

## 📌 Project Overview
This project explores transactional retail metrics to answer core business questions about sales distribution, top product categories, logistical bottlenecks, and peak seasonal trends. 

The goal is to demonstrate practical business intelligence and data modeling skills:
* **ETL Workflows:** Cleaning, transforming, and formatting raw, messy data formats via Power Query.
* **Data Modeling:** Constructing an optimized relational star/snowflake-adjacent schema.
* **Advanced Metrics:** Writing logical formulas and descriptive DAX/aggregations.
* **UI/UX Dashboard Design:** Developing highly scannable, executive-ready visuals with seamless interactivity.

---

## 🗂 Dataset Architecture
The analytics framework is built on top of three core source tables:

| File | Description | Key Features |
| :--- | :--- | :--- |
| **`orders.csv`** | Transaction-level logs | Order Date, Delivery Date, Quantities, Product IDs |
| **`customers.csv`** | Customer master records | 100+ distinct customer profiles & segments |
| **`products.csv`** | Product master data | 70+ unique SKUs mapped across categories & base prices |

---

## 🔧 Build Log (Step-by-Step Workflow)

### 1. Data Cleaning & Extraction (ETL)
* Imported raw CSV files into an organized layout.
* Addressed blank/missing attributes, unified date structures, and standardized localized currency representations.

### 2. Analytical Computations
* Mapped the average logistics lifecycle, pinpointing an **Order-to-Delivery fulfillment gap of ~5.5 days**.
* Computed comprehensive gross revenue aggregates ($Total\_Revenue = \sum (Quantity \times Price)$) to track overall performance.

### 3. Interactive UI Implementation
* Implemented dynamic, multi-tier **Slicers** for real-time data drilling (by Month, Category, and Status).
* Maintained a strict, cohesive color palette (complemented by deep accents) to maximize visual readability.

---

## 📊 Key Business Insights

### 🏆 Top Performing Categories
* **Soft Toys** 🧸 & **Sweets** 🍬 lead gross profit margins.
* **Colors** 🎨 & **Mugs** ☕ command the highest volume of micro-transactions.

### 📅 Seasonality & Peak Performance
* Maximum transaction volumes heavily correlate with major celebratory timelines such as **Diwali**, **Raksha Bandhan**, and localized **Anniversaries**.
* Timeline analysis helps identify structural inventory management windows to prevent stockouts.

---

## 🖥️ Dashboard Preview

> *Note: Replace the image placeholders below with your actual repository screenshot links once uploaded!*

| 📈 Main Executive Dashboard | 🔍 Filtered Slicer Views |
|---|---|
| ![Dashboard Overview](Screenshot%202026-07-01%20193509.png) | ![Slicers Action](Screenshot%202026-07-01%20195436.png) |

| 📅 Timeline & Revenue Trends | 🥇 Product Leaderboards |
|---|---|
| ![Revenue Trends](Screenshot%202026-07-01%20195754.png) | ![Top Products](Screenshot%202026-07-01%20195816.png) |

---

## 🧠 Core Competencies Demonstrated
* Dynamic Business Reporting & KPI Tracking
* Relational Data Modeling (Connecting Fact & Dimension Tables)
* Trend Analysis & Forecasting Preparation
* User-Centric Dashboard UI/UX Design

---

## 🤝 Contributing & Feedback
Feel free to fork this repository, submit pull requests with enhanced visual templates, or open issues to discuss alternative data modeling strategies. 

⭐ **If you find this business intelligence project helpful or inspiring, please consider giving it a star!**
