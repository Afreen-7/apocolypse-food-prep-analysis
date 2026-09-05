# Apocolypse Food Prep Analysis Using Excel & Power BI

## Project Overview

This project focuses on analyzing food prices across three major retail stores: **Walmart, Costco, and Target** using the **Apocolypse Food Prep** dataset.

The dataset contains price information for essential food products across different stores and dates.

I used **Microsoft Excel** to organize and analyze the data using PivotTables and then used **Microsoft Power BI** to create a visual dashboard for comparing prices across stores and products.

The main objective of this project was to understand price differences between stores and identify which stores have the highest and lowest aggregated prices for different food products.

---

## Tools & Technologies

- **Microsoft Excel**
  - Data organization
  - PivotTables
  - Data summarization
  - Price comparison

- **Microsoft Power BI**
  - Data visualization
  - Dashboard creation
  - Bar charts
  - Store and product comparison

---

## Dataset

The dataset is named **Apocolypse Food Prep**.

It contains pricing information for essential food products across three stores:

### Stores

- Walmart
- Costco
- Target

### Products

- Rice
- Dried Beans
- Bottled Water
- Canned Vegetables
- Milk

### Dataset Columns

| Column | Description |
|--------|-------------|
| Store | Name of the retail store |
| Product | Name of the food product |
| Price | Price of the product |
| Date | Date of the price observation |

---

## Excel Analysis

I used Microsoft Excel to organize the **Apocolypse Food Prep** dataset and create a PivotTable.

The PivotTable summarizes the **Sum of Price** by store, product, and month.

This helped me compare the overall price levels between Walmart, Costco, and Target.

### PivotTable Summary

| Store | Jan | Feb | Mar | Apr | Grand Total |
|-------|-----:|-----:|-----:|-----:|------------:|
| Costco | $51.39 | $54.72 | $56.13 | $57.68 | $219.92 |
| Target | $54.82 | $56.53 | $58.39 | $59.68 | $229.42 |
| Walmart | $55.72 | $57.84 | $59.94 | $61.13 | $234.55 |
| **Grand Total** | **$161.85** | **$169.09** | **$174.46** | **$178.49** | **$683.89** |

> The values represent aggregated product prices in the dataset and should not be interpreted as sales or revenue.

---

## Power BI Dashboard

After analyzing the data in Excel, I imported the dataset into Power BI and created a dashboard to visualize the price comparisons.

The dashboard contains two main visualizations.

### 1. Total Price by Store

This chart compares the aggregated prices across the three stores.

| Store | Total Price |
|-------|------------:|
| Walmart | $234.55 |
| Target | $229.42 |
| Costco | $219.92 |

**Walmart** has the highest aggregated price, while **Costco** has the lowest.

---

### 2. Product Price Comparison by Store

This visualization compares the aggregated price of each product across Walmart, Costco, and Target.

| Product | Highest Price Store | Aggregated Price |
|---------|---------------------|-----------------:|
| Rice | Walmart | $104.73 |
| Dried Beans | Target | $100.22 |
| Bottled Water | Walmart | $21.45 |
| Canned Vegetables | Costco | $3.40 |
| Milk | Target | $10.35 |

---

## Key Insights

### Store-Level Insights

- **Walmart** has the highest overall aggregated price at **$234.55**.
- **Target** has an aggregated price of **$229.42**.
- **Costco** has the lowest aggregated price at **$219.92**.
- The difference between Walmart and Costco is **$14.63**.

### Product-Level Insights

- **Rice** has the highest aggregated price among the products.
- Walmart has the highest aggregated Rice price at **$104.73**.
- Target has the highest aggregated Dried Beans price at **$100.22**.
- Walmart has the highest aggregated Bottled Water price at **$21.45**.
- Costco has the highest aggregated Canned Vegetables price at **$3.40**.
- Target has the highest aggregated Milk price at **$10.35**.

### Overall Insight

The analysis shows that price levels vary by both **store and product**.

No single store has the highest aggregated price for every product, making product-level comparison useful for understanding differences in retail food pricing.

---

## Project Workflow

```text
Apocolypse Food Prep Dataset
            ↓
     Data Organization
            ↓
       Excel Analysis
            ↓
        PivotTable
            ↓
     Price Comparison
            ↓
      Power BI Import
            ↓
    Dashboard Creation
            ↓
     Insights & Analysis
```
Excel PivotTable

The Excel PivotTable was used to summarize and compare prices across stores and products.

Power BI Dashboard

The Power BI dashboard provides a visual comparison of:

Total price by store
Product price comparison
Store-level price differences
Product-level price differences

Skills Demonstrated

Through this project, I practiced:

Data analysis
Microsoft Excel
PivotTables
Data summarization
Price comparison
Microsoft Power BI
Data visualization
Dashboard creation
Business insights
Data interpretation
Project Structure
apocolypse-food-prep-analysis/
│
├── README.md
│
├── rawdata/
│   └── Apocolypse_Food_Prep.xlsx
│
├── excel/
│   └── Apocolypse_Food_Prep_Analysis.xlsx
│
├── powerbi/
│   └── Apocolypse_Food_Prep_Dashboard.pbix
│
└── images/
    ├── excel-pivottable.png
    └── powerbi-dashboard.png
Conclusion

The Apocolypse Food Prep Analysis project demonstrates how retail food pricing data can be transformed into useful insights using Excel and Power BI.

Excel was used for organizing the data and creating PivotTable-based analysis, while Power BI was used to create an interactive visual dashboard.

This project helped strengthen my practical skills in Excel, PivotTables, data analysis, Power BI, data visualization, and business insight generation.


### A small correction for your Power BI dashboard

I recommend changing:

**`Best Store for Product`**

to:

**`Product Price Comparison by Store`**

because your chart is comparing **prices**, not determining which store is objectively "best."

Also, your first chart can stay as:

**`Total Price by Store`**

That will make the dashboard wording more accurate and professional for your GitHub portfolio
