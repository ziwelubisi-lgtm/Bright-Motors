

# 🚗 Bright Motors Car Sales Data Analysis

## 📌 Overview

This project analyzes car sales data for **Bright Motors** to uncover key business insights, improve pricing strategies, and evaluate sales performance. The goal is to transform raw transactional data into meaningful visualizations and actionable recommendations.

---

## 📊 Objectives

* Identify **pricing efficiency** (MMR vs Selling Price)
* Evaluate **seller performance**
* Analyze **sales trends** across different variables
* Detect **undervalued and overvalued vehicles**
* Support data-driven decision-making

---

## 🗂️ Dataset Description

The dataset contains detailed vehicle sales records with the following columns:

| Column Name    | Description                   |
| -------------- | ----------------------------- |
| `year`         | Vehicle manufacturing year    |
| `make`         | Brand of the vehicle          |
| `model`        | Model name                    |
| `trim`         | Trim level                    |
| `body`         | Vehicle body type             |
| `transmission` | Transmission type             |
| `vin`          | Vehicle Identification Number |
| `state`        | Location of sale              |
| `condition`    | Vehicle condition rating      |
| `odometer`     | Mileage                       |
| `color`        | Exterior color                |
| `interior`     | Interior color                |
| `seller`       | Seller name                   |
| `mmr`          | Market Mean Retail price      |
| `sellingprice` | Actual selling price          |
| `saledate`     | Date of sale                  |

---

## 🛠️ Tools & Technologies

* **SQL** – Data cleaning and transformation
* **Google Looker Studio / Power BI / Tableau / Excel** – Data visualization
* **GitHub** – Version control and collaboration

---

## 🔄 Data Preparation

Key preprocessing steps:

* Converted all text fields to **lowercase** for consistency
* Removed duplicates and handled missing values
* Rounded numerical values to **2 decimal places**
* Standardized date formats
* Ensured consistent grouping for case-insensitive analysis

---

## 📈 Key Analyses & Visualizations

### 💰 Pricing Efficiency

* **Visual:** Clustered Bar Chart
* **X-axis:** Make / Model
* **Y-axis:** MMR vs Selling Price
* **Insight:** Identify underpriced and overpriced vehicles

---

### 🧾 Seller Performance

* **Visual:** Bar Chart / Table
* **X-axis:** Seller
* **Y-axis:** Number of Sales / Total Revenue
* **Insight:** Top-performing sellers and revenue drivers

---

### 📅 Sales Trends

* **Visual:** Time Series Line Chart
* **X-axis:** Sale Date
* **Y-axis:** Total Sales / Revenue
* **Insight:** Seasonal patterns and demand fluctuations

---

### 🚘 Vehicle Insights

* Sales distribution by:

  * Make & Model
  * Body Type
  * Transmission
* Helps identify **most popular vehicle categories**

---

## 🔍 Key Insights

* Certain vehicles consistently sell **above MMR**, indicating high demand
* Some sellers outperform others significantly in both **volume and revenue**
* Mileage and condition strongly influence pricing
* Specific brands and models dominate overall sales

---

## 📌 Business Recommendations

* Adjust pricing strategy for **undervalued vehicles**
* Focus inventory on **high-performing makes/models**
* Provide incentives or training for **low-performing sellers**
* Use historical trends to **forecast demand**

---

## 📁 Project Structure

```
car-sales-analysis/
│
├── data/
│   └── car_sales.csv
│
├── sql/
│   └── data_cleaning.sql
│
├── dashboards/
│   └── looker_dashboard_link.txt
│
├── visuals/
│   └── charts.png
│
└── README.md
```


## 📎 Future Improvements

* Add predictive modeling for price optimization
* Integrate real-time sales data
* Build an interactive web dashboard

---

## 👤 Author

**Makaziwe Lubisi**
Data Analyst | Aspiring Data Scientist

---


Just tell me 👍
