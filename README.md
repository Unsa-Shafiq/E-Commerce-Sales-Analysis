# E-Commerce Sales Analytics

**E-Commerce Performance Analysis | Retail Profitability, Regional Performance & Strategic Insights**
---

## 1. Problem Statement

The Superstore is experiencing inconsistent profitability across products, regions, and customer segments despite steady sales growth.

The objective of this analysis is to identify where the business is generating profit, where it is losing money, and which products, regions, and customer segments require strategic attention.

---

## 2. Objectives

* Identify profitable and loss-making product categories and sub-categories.
* Analyze sales and profitability across regions and customer segments.
* Identify yearly and seasonal sales trends.
* Provide data-driven recommendations for pricing, marketing, and resource allocation.

---

## 3. Dataset Information

The project uses the **Superstore Retail Dataset**, available on Kaggle.

* **Period:** January 2014 – December 2017
* **Records:** 9,789 rows after cleaning
* **Columns:** 23 after cleaning
* **Categories:** Furniture, Office Supplies, Technology
* **Customer Segments:** Consumer, Corporate, Home Office

### Dataset

[Download / View Original Dataset](https://github.com/Unsa-Shafiq/E-Commerce-Sales-Analysis/blob/main/Sample%20-%20Superstore.csv)

---

## 4. Data Cleaning

The raw dataset was cleaned using **Excel**.
The dataset was mostly cleaned, just few cleaning steps were performed for data validation.

Main cleaning steps included:

* Removed three completely empty columns.
* Converted Order Date and Ship Date into proper date formats.
* Corrected missing leading zeros in postal codes.
* Standardized Customer ID casing.
* Corrected inconsistent customer name casing.
* Removed unnecessary whitespace.
* Checked for duplicate rows and missing values.

No duplicate rows or remaining null values were found after cleaning.

### Cleaned Dataset

[Download / View Cleaned Dataset](https://github.com/Unsa-Shafiq/E-Commerce-Sales-Analysis/blob/main/Superstore_Cleaned.xlsx)

---

## 5. Exploratory Data Analysis (EDA)

EDA was performed to understand overall business performance and identify key patterns.

The analysis focused on:

* Overall sales and profit performance
* Sales and profit by category and sub-category
* Regional performance
* Customer segment performance
* Year-over-year sales trends
* Seasonal sales patterns
* Discount impact on profitability
* Shipping mode preferences

The business generated approximately **$2.30M in sales and $286K in profit**, with an overall profit margin of **12.47%**.

---

## 6. Dashboard

An interactive Excel dashboard was created to provide a single-screen view of business performance.

### Dashboard Features

* KPI cards
* Monthly sales trend
* Sales by region
* Sales and profit by sub-category
* Sales by customer segment
* Sales by state
* Sales by shipping mode
* Year and Region slicers

The dashboard allows users to interactively filter the analysis by **year and region**.

### Dashboard Preview

![Superstore Sales Dashboard](https://github.com/Unsa-Shafiq/E-Commerce-Sales-Analysis/blob/main/Dashboard.png)

---

## 7. Key Insights

### Product Performance

* **Technology** is the strongest category, generating $836K in sales and a 17.40% profit margin.
* **Furniture** generates $742K in sales but has only a 2.49% profit margin.
* **Tables, Bookcases, and Supplies** are loss-making sub-categories.
* **Copiers** have a particularly strong 37.20% profit margin.
* **Paper** has the highest sub-category margin at 43.39%.

### Regional Performance

* **West** is the strongest region with a 14.94% profit margin.
* **Central** has the lowest profit margin at 7.92%.
* Central therefore requires further investigation into pricing, discounts, and product mix.

### Customer Segments

* **Consumer** is the largest customer segment, contributing 50.6% of total revenue.
* Corporate and Home Office contribute smaller shares but remain profitable.

### Sales Trends

* Sales increased by **51.5% from 2014 to 2017**.
* 2017 was the strongest year.
* Sales show strong Q4 seasonality, with November 2017 being the highest-sales month.

---

## 8. Recommendations

Based on the analysis:

1. **Reduce excessive discounting** on Tables and Bookcases and review their pricing strategy.
2. **Invest more in Technology**, particularly high-margin products such as Copiers.
3. **Audit Central region performance** to identify pricing and product-mix issues.
4. **Prepare inventory and marketing earlier for Q4** to take advantage of seasonal demand.
5. **Increase focus on Office Supplies**, which provides a strong 17.04% profit margin.
6. **Strengthen Consumer retention strategies**, as Consumers generate more than half of total revenue.
7. Review Same Day shipping costs to ensure premium delivery charges cover additional logistics costs.

---

## 9. Conclusion

The analysis shows that Superstore has strong overall sales growth, but profitability is being reduced by specific products and regions.

The biggest profitability issue is concentrated in **Tables and Bookcases**, where high discounts result in negative profits. At the same time, **Technology and Office Supplies** provide strong opportunities for profitable growth.

The analysis demonstrates how data cleaning, exploratory analysis, and dashboarding can be used to identify business problems and translate them into actionable recommendations.

---

## 10. Tools & Skills

* **Excel:** Pivot Tables, Charts, Slicers, KPI Cards and Dashboard
* **Data Analysis:** Sales, profit, regional, segment, product and trend analysis
* **Business Analytics:** Converting findings into actionable recommendations
* **Data Visualization:** Interactive executive dashboard

---

## Author

**Unsa**

Data Analytics Portfolio Project
