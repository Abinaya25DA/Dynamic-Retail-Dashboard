# Dynamic-Retail-Dashboard
## 📌 Project Overview

This project showcases the development of a **Dynamic Retail Dashboard using Microsoft Excel**, aimed at empowering retail businesses with actionable insights from the sales data. The dashboard is built to be fully interactive and user-friendly, enabling both technical and non-technical users to explore retail performance with ease. It integrates three core datasets such as **orders table**, **returns table** and **people table** and tracks **key performance indicators (KPIs)** such as total sales, profit, quantity sold, number of orders, and profit margin to support strategic decision-making.

Using **Power Query**, the data is cleaned, transformed, and merged to create a robust backend model. The front-end dashboard uses **PivotTables, slicers, and charts** to present insights in a visual and filterable format.

---

## 📂Sample Datasets 
### 🧾ORDERS Table :
  The order table captures transactional sales data (order ID, sales, profit, quantity, etc.)
| Order ID | Order Date | Ship Date | Customer Name | Segment | City | State | Country | Market | Region | Category | Sales | Quantity | Profit | 
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| CA-2012-124891 | 31-07-2020 | 31-07-2020 | Rick Hansen | Consumer |	New York City	| New York | United States | US | East | Technology | 2309.65 | 7 |	762.1845 |
| IN-2013-77878 | 05-02-2021 | 07-02-2021 | Justin Ritter | Corporate	| Wollongong	| New South Wales	| Australia | APAC | Oceania | Furniture | 3709.395	| 9 | -288.765 |
| IN-2013-71249 | 17-10-2021 | 18-10-2021 | Craig Reiter | Consumer	| Brisbane | Queensland	| Australia | APAC | Oceania | Technology | 5175.171 | 9 | 919.971 |   

### 🔁RETURNS Table :
  The return table tracks returned orders and helps identify loss impact
| Returned |	Order ID	|Market|
| :---: | :---: | :---: |
|Yes	|MX-2013-168137	|LATAM |
|Yes	|US-2011-165316	|LATAM |
|Yes	|ES-2013-1525878	|EU |
|Yes	|CA-2013-118311	|United States |
|Yes	|ES-2011-1276768	|EU |

### 👥PEOPLE Table :
  The people table maps regional managers to specific geographic zones
| Person | Region |
| :---: | :---: |
|Anna Andreadi	|Central |
|Chuck Magee	|South |
|Kelly Williams	|East |
|Matt Collister	|West |
|Deborah Brumfield	|Africa |

---

## 📊**KPI Table**
These KPIs are dynamically calculated and displayed in a centralized KPI panel for quick reference, alongside supporting visuals like bar charts, trend lines, and category-wise breakdowns.


<img width="420" height="145" alt="image" src="https://github.com/user-attachments/assets/762e64d7-1ca5-4d63-b223-7614047a4953" />

---

## 🌟 Project Goals

- Visualize and track sales performance across regions, categories, and time periods

- Identify profit-driving and loss-making segments

- Enable real-time analysis of return trends and their business impact

- Provide a simple yet effective BI alternative using only Excel
  
---

## ⚙️ Technical Highlights

- ✅ Built entirely in Microsoft Excel

- 🔄 Data transformation using Power Query

- 📊 Visuals via PivotTables, Charts, and Slicers

- 🌐 Connects to GitHub-hosted datasets for auto-refresh capability
  
---
  
## 🧠 Problem Statements Solved

  The dynamic retail dashboard answers several business questions, providing in-depth insights into key performance area:
  
1.**KPIs** - Total sales, Total Profit, Total Quantity, No of Orders, Profit Margins

  <img width="889" height="65" alt="image" src="https://github.com/user-attachments/assets/f5a62283-ba78-4315-a725-33cdd5403f2a" />



2.**Market Analysis** - Understanding overall sales across different market areas

<img width="299" height="186" alt="image" src="https://github.com/user-attachments/assets/259e1f5f-a528-4b6e-b493-4756b2128d68" />



3.**Category-wise Profit** - Breakdown of profit by product category

<img width="270" height="185" alt="image" src="https://github.com/user-attachments/assets/8e17093a-56bb-4eb0-a70b-630f4cae765c" />



4.**Segment-wise Sales Share %** - Breakdown of sales by customer segment 

<img width="279" height="194" alt="image" src="https://github.com/user-attachments/assets/9ad791fb-f48f-44cf-a679-a2d7f6bfe624" />



5.**Sales by Top 10 Country** - sales performance based on top 10 countries

<img width="349" height="191" alt="image" src="https://github.com/user-attachments/assets/08218ba3-d9ff-4094-8614-385404a72826" />



6.**Top 5 Regions** - The best performing regions based on sales

<img width="307" height="224" alt="image" src="https://github.com/user-attachments/assets/834a32d0-b575-4341-8943-6b4cfd22ca2c" />



7.**Bottom 5 Regions** - The least performing regions based on sales

<img width="282" height="239" alt="image" src="https://github.com/user-attachments/assets/d70bf9f6-09c9-483a-b112-4e9852e83c7a" />



8.**Yearly Sales Trends** - Understanding how sales evolve over the year

<img width="599" height="35" alt="image" src="https://github.com/user-attachments/assets/4ecc4af4-24aa-4a97-ba4c-99b0e72c9d51" />


---

## 📊Visuals
This repository includes:

Visual examples for each solved problem statement.


Snapshots of the final dashboard with all components.


<img width="1225" height="582" alt="image" src="https://github.com/user-attachments/assets/9e54533e-2f95-4c58-adeb-28026e420e34" />



---

## ✅ Conclusion
The **Dynamic Retail Dashboard** demonstrates how powerful insights can be extracted from raw data using just Microsoft Excel. By combining structured datasets, dynamic visuals, and automated transformations, this project delivers a practical and scalable solution for retail analytics. Whether used by sales managers, analysts, or business leaders, the dashboard empowers users to make data-driven decisions, identify trends, and optimize performance — all within a familiar Excel environment.




