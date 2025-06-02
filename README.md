# DA-8-IMEI-Property-Portfolio-Dashboard
IMEI Property Portfolio Dashboard was developed to provide a data-driven view into property sales, pricing trends, customer purchasing behavior, and real estate market dynamics. This enables better strategic decision-making for property managers, investors, and stakeholders by delivering a holistic view of property transactions .
Here's a well-structured and insightful `README.md` file for your GitHub repository, based on the image of the Power BI dashboard you provided:

---

# 🏘️ IMEI Property Portfolio Dashboard

![Screenshot (196)](https://github.com/user-attachments/assets/03805445-9cf2-4c32-b18f-80eb33a552d2)

## 📌 Business Statement

The **IMEI Property Portfolio Dashboard** was developed to provide a data-driven view into property sales, pricing trends, customer purchasing behavior, and real estate market dynamics. This enables better strategic decision-making for property managers, investors, and stakeholders by delivering a holistic view of property transactions across multiple categories and timelines.

---

## 🎯 Goals & Objectives

* **Analyze property sales performance** across time, type, size, and category.
* **Identify sales trends and pricing behavior** across different customer segments.
* **Monitor listing and sales status** to optimize inventory and marketing strategies.
* **Enable quick decision-making** with visual insights on property size, type, and price reduction impact.
* **Provide stakeholders with an intuitive interface** to track average property lifecycle, asking prices, and buyer behavior.

---

## Business Questions
1. Count of Property Types:									
   - How many properties belong to each type (Detached, Semi-detached, etc.)?									
  									
2. Average Asking Price by Property Type:									
   - What is the average asking price for each property type?									
									
3. Total and Average Sale Price by Location:									
   - What is the total and average sale price of properties in each location (Town, Village, Countryside)?									
									
4. Average No. of Bedrooms per Property Type:									
   - What is the average number of bedrooms for each property type?									
									
5. Properties Listed vs. Sold:									
   - How many properties were listed and how many were sold?									
									
6. Time on Market Analysis:									
   - What is the average days a property stays on the market before being sold?									
									
7. Price Reduction Analysis:									
   - What percentage of properties sold below the asking price?									
	Create a new column to the data showing the difference btw the sales price and the asking price								
	Create a price reduction tag with the IF function (if the sales price is lesser than the asking price, return reduced, otherwise return not reduced								
	Then set your pivot to show the count of each reduction tag and the percentage of grand total								
									
8. Garden Size and Property Price:									
   - Do properties with larger gardens have higher asking/sale prices?									


## 📊 Key Insights

### 🔹 Overall Metrics:

* **Total Sales Price:** \$13.40M
* **Total Properties Sold:** 56
* **Average Sales Price:** \$309,115
* **Average Property Length of Stay (LOS):** 104 days

### 📈 Sales Trends:

* **Monthly Trend:**

  * Highest sales in **March (\$4.0M)** and **April (\$2.8M)**
  * A sharp decline from May to December
  * Indicates seasonal peaks in Q1

### 🏡 Property Breakdown by Type:

* **Semi-detached:** 18 properties (Most popular)
* **Detached:** 13
* **Bungalow:** 13
* **Terraced:** 10
* **Flat:** 2

### 📍 Sales Price by Category:

* **Town properties** generated the highest revenue.
* **Remote and countryside properties** had comparatively lower sales.

### 🛏️ Average Bedrooms by Type:

* **Detached:** 4 bedrooms
* **Bungalow & Semi-detached:** 3 bedrooms
* **Terraced & Flat:** 2 bedrooms

### 📉 Price Reduction Insights:

* **45% of properties had reduced prices**
* Of these, **25% were still listed** and **20% were sold**
* Indicates price reductions play a key role in moving inventory

### 🏷️ Asking Price by Size:

* **Large Properties:** \$388,684 (highest)
* **Medium Properties:** \$326,466
* **Small Properties:** \$201,514
* **None specified:** \$165,250

### 🔄 Listing Status:

* **75% of properties are sold**
* **25% are still listed**

---

## 📂 Project Structure

```
📁 IMEI-Property-Portfolio
│
├── 📊 Screenshot (196).png   # Power BI Dashboard image
├── 📄 README.md              # Documentation file (this file)
└── 📁 Data/                  # (Optional) Folder for raw/cleaned datasets
```

---

## 🚀 Tools & Technologies

* **Excel**: Used for building the interactive dashboard
* **Power Pivot (Data Modeling)**: Property data categorized by type, size, location, and sales attributes
* **Data Visualization**: Bar charts, donut charts, line charts, and KPI cards

---

## 👤 Developed By

**John David**

📎 [LinkedIn](https://www.linkedin.com/in/john-david-b7b5781b3/)

📧 [Email Me](mailto:adelekejohndavid@gmail.com)

---

## 📌 Summary

This dashboard provides a dynamic and data-rich visual summary of property sales performance. It helps real estate companies, property managers, and investors gain deep insights into sales dynamics and buyer behavior—empowering them to optimize their portfolio management strategies.
