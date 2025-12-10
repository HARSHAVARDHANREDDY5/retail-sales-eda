# Retail Sales EDA

This repository contains an Exploratory Data Analysis (EDA) project on a retail sales dataset.  
The goal is to understand sales patterns across products, customers, regions, and time.

---

## 1. Dataset

- **Source:** Public retail / superstore sales dataset (similar to the classic Sample Superstore data).
- **Rows:** ~9,800
- **Columns:** 18
- **Example fields:**
  - Order Date, Ship Date
  - Ship Mode
  - Customer ID, Customer Name, Segment
  - Country, City, State, Postal Code, Region
  - Product ID, Category, Sub-Category, Product Name
  - Sales

The raw dataset used in this project is stored in `data/raw/train.csv`.

---

## 2. Objectives

Key questions explored in this analysis:

- Which **categories** and **sub-categories** generate the highest total sales?
- Which **regions, states, and customer segments** contribute most to revenue?
- Who are the **top customers** by sales?
- How do **sales evolve over time** (monthly trend)?
- Are there any clear patterns by **shipping mode** or **customer segment**?

---

## 3. Project Structure

```text
retail-sales-eda/
│
├─ data/
│   └─ raw/
│       └─ train.csv
│
├─ notebooks/
│   └─ 01_retail_sales_eda.ipynb
│
├─ images/
│   ├─ total_sales_by_category.png
│   └─ monthly_sales_trend.png
│
└─ README.md
