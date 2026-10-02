# Grace Stores Sales Analysis 📈

## Project Overview

**Grace Stores Sales Analysis** is a Power BI business intelligence project developed to analyze sales performance across products, regions, salespersons, customers, and time.

The project transforms transactional sales data into an interactive dashboard that helps identify revenue patterns, high-performing products and regions, customer contributions, salesperson performance, and monthly sales trends.

---

## Objective

The main objective of this project is to use sales data to:

* Measure overall sales and revenue performance.
* Identify top-performing products and customers.
* Compare revenue generated across regions.
* Evaluate salesperson performance.
* Analyze monthly revenue trends.
* Identify periods of high and low sales.
* Provide data-driven recommendations for improving sales performance.

---

## Business Problem

Grace Stores needs a clear understanding of its sales performance in order to identify where revenue is coming from and where improvements may be needed.

Without a centralized analysis, it can be difficult to determine:

* Which products generate the most revenue.
* Which regions contribute the most to sales.
* Which customers generate the highest revenue.
* Which salespersons perform strongly.
* Which months experience higher or lower sales.
* Where management should focus its sales and marketing efforts.

This project addresses these challenges by providing an interactive Power BI dashboard for monitoring and analyzing sales performance.

---

## Dataset Overview

The dataset contains 909 rows of transactional sales records with fields including:

| Column          | Description                              |
| --------------- | ---------------------------------------- |
| **Salesperson** | Employee responsible for the sale        |
| **Product**     | Product sold                             |
| **Region**      | Geographical sales region                |
| **Customer**    | Customer associated with the transaction |
| **Date**        | Date of the transaction                  |
| **Item Cost**   | Cost associated with each item           |
| **No. Items**   | Quantity of items sold                   |
| **Total Cost**  | Total transaction cost                   |

The dataset covers transactions across multiple products, customers, regions, salespersons, and dates.

---

## Data Cleaning and Preparation

The dataset was prepared using Power Query before visualization in Power BI. The preparation process included:

1. Checking the dataset structure to understand the available fields and their data types.
2. Checking date fields to ensure transaction dates were correctly recognized as dates.
3. Reviewing numerical columns such as Item Cost, No. of Items, and Total Cost for appropriate numerical formatting.
4. Checking categorical fields such as Product, Region, Customer, and Salesperson for consistency.
5. Reviewing missing or inconsistent values before analysis.
6. Creating appropriate measures and aggregations for revenue, item quantity, and other dashboard KPIs.
7. Formatting monetary values in British pounds (£) for clear presentation.

---

## Analysis

### 1. Revenue by Salesperson

The **Revenue by Salesperson** horizontal bar chart compares individual salesperson performance to identify differences in revenue contribution across the sales team.

The highest-performing salesperson generated approximately **£0.48M**, while the remaining salespersons generated between approximately **£0.18M and £0.37M**.

<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/a80321b5-c1d3-4802-bd7c-cb11e365d889" />


---

### 2. Revenue by Product

The **Revenue by Product** bar chart compares product revenue to identify the products contributing most to overall sales.

* **Coach:** £1.6M
* **Showcase:** £0.7M
* **Chair:** £0.6M
* **Coffee Table:** £0.3M
* **Dinner Table:** £0.2M

Coach generated the largest share of product revenue, while Dinner Table generated the lowest.

<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/09442e7e-d8be-4952-a2d9-3b00d2404c22" />


---

### 3. Revenue by Region

The **Revenue by Region** doughnut chart compares revenue across geographical regions to identify the regions contributing most to overall sales.

* **North East:** £1.21M
* **South West:** £1.09M
* **North West:** £0.56M
* **South East:** £0.50M

North East generated the highest revenue, followed closely by South West.

<img width="691" height="356" alt="image" src="https://github.com/user-attachments/assets/a82581ed-1b26-408b-96a9-2a06be7fe007" />


---

### 4. Revenue by Month

The **Revenue by Month** line chart tracks monthly revenue throughout the year to identify seasonal patterns and periods of stronger or weaker sales performance.

| Month     | Revenue |
| --------- | ------: |
| January   |   £219K |
| February  |   £250K |
| March     |   £295K |
| April     |   £275K |
| May       |   £356K |
| June      |   £310K |
| July      |   £288K |
| August    |   £256K |
| September |   £245K |
| October   |   £274K |
| November  |   £267K |
| December  |   £330K |

Revenue reached its highest point in **May at approximately £356K**, followed by **December at £330K**. January recorded the lowest monthly revenue at approximately **£219K**.

<img width="697" height="332" alt="image" src="https://github.com/user-attachments/assets/883be907-6d93-4ab3-aab5-83ea73acda85" />


---

### 5. Revenue by Customer

The **Revenue by Customer** bar chart compares revenue generated by each customer category to identify the customers contributing most to overall sales.

* **Home Town:** £0.74M
* **Home Spaze:** £0.70M
* **FurniChar:** £0.68M
* **PaperFly:** £0.64M
* **Rentical:** £0.62M

Home Town generated the highest revenue, while Rentical generated the lowest among the five customer categories.

<img width="700" height="435" alt="image" src="https://github.com/user-attachments/assets/ef51c96a-ee54-46f3-8f2f-e3519f0b9a93" />


---

## Dashboard Summary

The Power BI dashboard provides an interactive overview of Grace Stores' sales performance through KPI cards, bar charts, a doughnut chart, and a monthly trend line.

### Dashboard KPIs

The dashboard provides three main KPI cards:

* **9K** – Total Items Sold
* **£3.37M** – Total Revenue
* **5** – Customers 

Users can filter the dashboard by **Product** and **Region**, allowing them to explore how revenue changes across different segments.

The dashboard combines:

* Overall sales KPIs
* Salesperson performance
* Product revenue
* Regional revenue
* Monthly revenue trends
* Customer revenue contribution

This makes it possible for stakeholders to quickly identify major revenue drivers and investigate areas requiring attention.

<img width="1392" height="780" alt="image" src="https://github.com/user-attachments/assets/ad526368-a3ae-452a-956d-a6fc9e4c8e9e" />


---

## Key Insights

1. **Revenue Performance**
   Grace Stores generated approximately **£3.37M in total revenue** from around **9K items sold**.

2. **Product Performance**
   **Coach** was the highest-revenue product at approximately **£1.6M**, considerably ahead of the other products.

3. **Regional Performance**
   **North East** generated the highest regional revenue at approximately **£1.21M**, followed by South West at **£1.09M**.

4. **Customer Contribution**
   **Home Town** generated the highest customer revenue at approximately **£0.74M**, while Rentical generated approximately **£0.62M**.

5. **Monthly Performance**
   Revenue peaked in **May at £356K**, while January recorded the lowest revenue at **£219K**.

6. **End-of-Year Performance**
   December recorded strong revenue of approximately **£330K**, indicating increased sales activity toward the end of the year.

7. **Salesperson Performance**
   The top salesperson generated approximately **£0.48M**, while the remaining salespersons showed varying levels of revenue contribution.

8. **Revenue Concentration**
   Revenue is concentrated around a few key products and regions, particularly Coach and the North East/South West regions.

---

## Recommendations

### 1. Focus on High-Performing Products

Maintain sufficient stock of high-revenue products such as Coach while investigating opportunities to improve sales of lower-performing products.

### 2. Strengthen High-Performing Regions

Continue supporting the North East and South West regions while identifying the factors contributing to their stronger revenue performance.

### 3. Improve Lower-Performing Regions

Investigate the causes of lower revenue in the South East and North West and consider targeted promotions, customer outreach, or sales initiatives.

### 4. Learn from Top Salespersons

Analyze the strategies and customer approaches used by higher-performing salespersons and share successful practices across the sales team.

### 5. Prepare for Peak Sales Periods

Increase inventory and marketing preparation before high-performing months such as May and December to take advantage of increased demand.

### 6. Investigate Low-Sales Periods

Analyze the reasons behind lower revenue in January and September and introduce targeted promotions or campaigns where appropriate.

### 7. Strengthen Customer Relationships

Develop retention and cross-selling strategies for high-revenue customers such as Home Town and Home Spaze.

### 8. Improve Low-Performing Product Sales

Review pricing, promotion, demand, and customer preferences for products such as Dinner Table and Coffee Table to identify opportunities for improvement.

---

## Tools Used

* **Microsoft Power BI**
* **Power Query** – Data cleaning and transformation
* **DAX** – Measures and calculations
* **Power BI Visualizations** – Dashboard development and data storytelling

---

## Project Conclusion

The Grace Stores Sales Analysis demonstrates how Power BI can transform transactional sales data into useful business insights. The analysis identified important differences in product, regional, customer, salesperson, and monthly revenue performance.

The dashboard shows that **Coach, the North East region, Home Town customer category, and May sales period** are significant contributors to the observed revenue performance. These findings can support decisions around inventory planning, sales strategies, regional marketing, customer management, and seasonal campaign planning.

Overall, the project demonstrates the use of **data cleaning, data modeling, KPI development, interactive visualization, trend analysis, and business insight generation** to support data-driven decision-making.

