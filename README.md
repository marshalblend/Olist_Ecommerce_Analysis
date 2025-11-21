# 🇧🇷 Olist E-Commerce Data Analysis & Business Dashboard

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) | ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white) | ![Seaborn](https://img.shields.io/badge/Seaborn-406A72?style=flat&logo=seaborn&logoColor=white) | ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white) |


## 🌟 Project Overview

This project is a comprehensive Exploratory Data Analysis (EDA) of  **Olist Brazilian E-Commerce Public Dataset**. The goal was to transform raw data into actionable business intelligence to uncover trends in customer behavior, identify key drivers of satisfaction, and assess overall business health.

The analysis is presented through a series of detailed charts and a final retention heatmap, providing insights for the Sales, Marketing, and Logistics teams.


## ⚙️ Tech Stack & Methodology

* **Languages:** Python
  
* **Libraries:** Pandas (Data Wrangling), NumPy (Numerical Operations), Matplotlib & **Seaborn** (Visualization)

* **Methodology:**
    1.  **Data Acquisition & Cleaning:** Merging 8+ distinct datasets (customer, order, item, review, payment) and handling missing values.
    2.  **Feature Engineering:** Calculating key metrics like **Cohort Month**, **Retention Period**, and **Delivery Slack** (Estimated vs. Actual Delivery).
    3.  **Advanced Analysis:** Implementing cohort analysis to calculate and visualize the customer retention matrix.



## 📈 Key Findings & Visualizations



* **Customer Retention (Cohort Heatmap):** Low Overall Repeat Purchase Rate: The analysis showed that over 90% of customers are single-purchase buyers, confirming a significant challenge in customer loyalty. Repeat customers were few (around 3%−5% of the total base). There is a critical need to invest in post-sale engagement and loyalty programs to convert one-time buyers into repeat customers. 

    
* **Monthly Sales Trend** Analysis revealed two critical seasonal peaks: a significant Q4 revenue surge (October–November), likely driven by holiday demand, and a strong Q2 ramp-up (March–May) followed by a sharp June dip. This dictates a need for proactive Q4 inventory scaling and targeted promotions to counteract the predictable Q3 (June) decline.  


* **Product Performance** Analysis of product category performance shows that Health & Beauty, Watches and Gifts (jewelry), and Bed Bath & Table are the top three revenue drivers for the business. Conversely, categories like Cool Stuff and Garden Tools were identified as low-yield segments.


## 🧭 Repository Contents

| File/Folder | Description |
| :--- | :--- |
| `olist_project.ipynb` | **The primary code source** containing all cleaning, feature engineering, and visualization steps, including the Cohort Analysis. |
| `olist_customers_dataset.csv, olist_order_items_dataset.csv, olist_order_payments_dataset.csv, olist_orders_dataset.csv, olist_products_dataset.csv, product_category_name_translation.csv` | Original raw data files provided by Olist. |
| `product_cat_revenue.png, monthly_sales_trend.png, customer_retention_matrix.png` | **Charts/Images**: Key visualizations for revenue, sales trends, and customer behavior. |


