# SalesAnalysisProject

## 📌 Project Objective

This project aims to analyze and visualize company sales data using both Python and Power BI. The goal is to uncover insights into regional sales performance, product category trends, profitability, and customer behavior. The dashboards are interactive and business-friendly, helping stakeholders make data-driven decisions.

## 🧠 Problem Statement Overview

This analysis solves key business problems like identifying declining regions, top-performing markets, underperforming products, and customer purchase patterns. The project is split into two phases:

## 🐍 Phase 1: Data Processing & EDA (Python)

Conducted extensive data preprocessing, cleaning, and exploratory analysis using:

* **Pandas** for data manipulation and wrangling
* **Matplotlib & Seaborn** for visual EDA and pattern detection
* **Feature Engineering** for deriving meaningful fields (e.g., profit margin, order value per region, etc.)
* Created summary statistics and distribution plots to guide dashboard creation

![image](https://github.com/user-attachments/assets/7975af17-e8ae-45ef-94a3-18e842a06047)
![image](https://github.com/user-attachments/assets/f0674815-6442-42a7-b43c-70b53cd7b3b1)
![image](https://github.com/user-attachments/assets/71729e8f-dd9c-48a8-8287-69e4d0b5bd5f)
![image](https://github.com/user-attachments/assets/b0329fe6-da9c-4e25-8098-df8aaa53fa21)
![image](https://github.com/user-attachments/assets/3008c921-80b0-4d55-b6c0-5f2f4c69b43a)
![image](https://github.com/user-attachments/assets/9ba79c7c-6e21-4931-8a3b-7ac8e55139e8)

## 📊 Phase 2: Dashboarding (Power BI)

### 🧭 1. Overview Page
* Displays total revenue, profit, profit margin %, total orders, and RPO KPIs
* Line chart showing monthly revenue fluctuations
* Line chart depicting monthly profit patterns
* Tab navigation bar enables easy access to all dashboards

![image](https://github.com/user-attachments/assets/59a1a549-d8d4-4f9a-b742-ac29a356531e)

### 🌍 2. Regional Analysis
* Donut chart showing sales distribution by region
* Bar chart comparing average order quantity across regions
* Treemap highlighting the top 5 most profitable states
* Bar chart of revenue generated from each region
* Bar chart showing profit breakdown by region
* Bar chart comparing total orders from different regions

![Screenshot 2025-06-29 161704](https://github.com/user-attachments/assets/0ee63af0-615e-4363-8229-19c40244c1da)

### 📦 3. Product Insights
* Horizontal bar chart of top 5 most profitable products
* Bar chart showing products that generated the most revenue
* Bar chart listing highest selling products by order quantity
* Scatter plot visualizing profit margins across all products
* Stacked bar chart of top profitable products segmented by region

![Screenshot 2025-06-29 161726](https://github.com/user-attachments/assets/bf736905-185e-4639-bf7a-788b3908bb4c)

### 🏪 4. Channel Performance
* Donut chart showing revenue share across Wholesale, Distributor, Export
* Profit margin visualization by channel
* Total profit comparison among sales channels
* RPO (Revenue per Order) analyzed for each channel
* Sales volume distribution shown by channel

![Screenshot 2025-06-29 161752](https://github.com/user-attachments/assets/cd179e13-e5c5-4eb9-be14-a00f2b678a6f)

### ⏳ 5. Trends Over Time
* Line graph depicting revenue trends from 2014 to 2018
* Sales trend chart based on order quantities over time
* Order trend analysis showing volume fluctuations across years
* Profitability trends highlighting year-on-year profit shifts

![Screenshot 2025-06-29 161814](https://github.com/user-attachments/assets/8d821df7-47e9-4d4d-ba37-182bbf66aa22)

## 🧭 Landing Page

* Central navigation hub to access all dashboards
* Filter-driven interaction and responsive UI
* Clean, corporate-style design with consistent theming

![image](https://github.com/user-attachments/assets/04aeca5d-890a-4feb-b759-9d186cbace0a)

## 💡 Key Features

* 📌 Seamless Python + Power BI integration
* 📈 EDA-driven dashboard design
* 🔄 Drill-through filters and slicers
* 📤 Exportable raw data
* 🎨 Professional visual aesthetics
* ⚡ Fast-loading with optimized DAX measures

## 🧰 Tech Stack

* **Python** (Pandas, Matplotlib, Seaborn)
* **Power BI Desktop**
* **DAX** (Data Analysis Expressions)
* **Power Query** for transformation
* **GitHub** for version control

## 🔧 How to Use

1. Clone this repository
2. Open the `.pbix` file in Power BI Desktop
3. Navigate using the Landing Page
4. Use filters, slicers, and tooltips for deeper insights
5. Export from the Raw Data tab if needed
6. For Python preprocessing steps, refer to the `.ipynb` Jupyter Notebook

## 🚧 Limitations

* Dataset is simulated and may not reflect real-world complexity
* Advanced forecasting models were not included (can be added later)
