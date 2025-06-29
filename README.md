# SalesAnalysisProject

📊 Sales Analysis Dashboard (Python + Power BI Project)

📌 Project Objective
This project aims to analyze and visualize company sales data using both Python and Power BI. The goal is to uncover insights into regional sales performance, product category trends, profitability, and customer behavior. The dashboards are interactive and business-friendly, helping stakeholders make data-driven decisions.

🧠 Problem Statement Overview
This analysis solves key business problems like identifying declining regions, top-performing markets, underperforming products, and customer purchase patterns. The project is split into two phases:

🐍 Phase 1: Data Processing & EDA (Python)
Conducted extensive data preprocessing, cleaning, and exploratory analysis using:
Pandas for data manipulation and wrangling
Matplotlib & Seaborn for visual EDA and pattern detection
Feature Engineering for deriving meaningful fields (e.g., profit margin, order value per region, etc.)
Created summary statistics and distribution plots to guide dashboard creation
![image](https://github.com/user-attachments/assets/e821127b-c2f9-4fb3-bb9a-9de1ffa78454)


📊 Phase 2: Dashboarding (Power BI)
🧮 1. Regional Sales Overview
Sales and Profit performance by Region, Sub-Region, and State

KPIs: Total Sales, Profit, Profit Margin %

Heatmap and bar visuals to highlight strong/weak geographies

🛍️ 2. Product Category & Segment Analysis
Breakdown of sales by Category, Sub-Category, and Segment

Identified high-performing and low-performing product lines

Used treemaps and stacked bar charts

🧾 3. Customer Purchase Behavior
Insights into average order values

Repeat vs one-time buyers

Monthly and quarterly trends to assess seasonality

💰 4. Profitability Deep Dive
Profit Margins by Channel and Product

Highlighted loss-making areas

Data labels and visual annotations included

📥 5. Raw Data Explorer
Table showing order-level details: customer, product, region, sales, discount, profit

Supports export for further analysis

Drill-through enabled for customer- or product-level insights

🧭 Landing Page
Central navigation hub to access all dashboards

Filter-driven interaction and responsive UI

Clean, corporate-style design with consistent theming

💡 Key Features
📌 Seamless Python + Power BI integration

📈 EDA-driven dashboard design

🔄 Drill-through filters and slicers

📤 Exportable raw data

🎨 Professional visual aesthetics

⚡ Fast-loading with optimized DAX measures

🧰 Tech Stack
Python (Pandas, Matplotlib, Seaborn)

Power BI Desktop

DAX (Data Analysis Expressions)

Power Query for transformation

GitHub for version control

🚧 Limitations
Dataset is simulated and may not reflect real-world complexity

Advanced forecasting models were not included (can be added later)

🔧 How to Use
Clone this repository

Open the .pbix file in Power BI Desktop

Navigate using the Landing Page

Use filters, slicers, and tooltips for deeper insights

Export from the Raw Data tab if needed

For Python preprocessing steps, refer to the .ipynb Jupyter Notebook
