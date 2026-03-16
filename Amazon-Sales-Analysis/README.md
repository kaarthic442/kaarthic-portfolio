# Amazon Sales Analysis Dashboard

## Project Overview

This project analyzes **Amazon product sales data** using **Power BI** to uncover insights related to sales performance, product demand, and customer engagement through reviews.
The dashboard enables stakeholders to monitor revenue trends, evaluate product categories, and identify top-performing products based on sales and reviews.

## Key KPIs

* **YTD Sales:** Total sales generated year-to-date
* **QTD Sales:** Sales generated during the current quarter
* **YTD Products Sold:** Total quantity of products sold
* **YTD Reviews:** Total number of customer reviews received

## Dashboard Components

### 1. Sales Overview

* KPI cards displaying **YTD Sales, QTD Sales, Products Sold, and Reviews**
* **Monthly Sales Trend** line chart showing sales progression throughout the year
* **Weekly Sales Analysis** bar chart to monitor short-term sales fluctuations

### 2. Product Category Analysis

* Table showing **Sales by Product Category**
* Displays:

  * YTD Sales
  * QTD Sales
  * Percentage contribution to total YTD Sales
* Helps identify **which product categories generate the most revenue**

### 3. Product Performance Analysis

* **Top 5 Products by YTD Sales**

  * Highlights the highest revenue-generating products
* **Top 5 Products by YTD Reviews**

  * Shows products with the highest customer engagement

### 4. Filters / Slicers

Interactive filters allow users to dynamically explore the data:

* **Product Category**
* **Quarter (Qtr)**

These slicers update all visuals in the dashboard for deeper analysis.

## Data Model

The model follows a **star schema design**:

**Fact Table**

* `Amazon_Data`

  * Order Date
  * Price (Dollar)
  * Product Category
  * Product Description
  * Shipment
  * Number of Reviews

**Dimension Table**

* `Date Table`

  * Date
  * Month Name
  * Month Number
  * Quarter
  * Quarter Number

A **one-to-many relationship** connects:

* `Date Table[Date]` → `Amazon_Data[Order Date]`

This enables accurate **time-intelligence calculations** like YTD and QTD.

## Key Features

* Time intelligence calculations using **DAX (YTD & QTD measures)**
* Interactive **slicers for filtering by category and quarter**
* **Monthly and weekly trend analysis**
* **Top N product ranking**
* Clean and modern **dark-theme dashboard design**
* Clear comparison of **category performance**

## Tools & Technologies

* **Power BI**
* **Power Query**
* **DAX**
* **Data Modeling**

## Files Included

* `Amazon_Sales_Analysis.pbix`
* `Dashboard Screenshot`
