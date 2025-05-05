# E-Commerce Platform Performance Analysis

> **Author:** Swetha Julakanti  
> **Project Type:** Business Intelligence & Data Visualization  
> **Tools:** Power BI Desktop (Feb 2024 Edition)  
>  
---

## 📌 Project Overview

This Power BI dashboard provides an interactive analysis of operational performance, customer behavior, and delivery metrics across three major e-commerce platforms: **Swiggy Instamart**, **Blinkit**, and **JioMart**. The dashboard is structured with KPI cards, visual summaries, and slicers for platform-wise filtering, helping stakeholders understand key trends in sales, sentiment, and delivery efficiency.

---

## 🧰 Tools and Technologies

- **Power BI Desktop** – Report development & interactive visualization  
- **Power Query** – ETL pipeline for data cleaning and transformation  
- **DAX** – For dynamic KPIs and calculated measures  
- **Git + GitHub** – Version control and documentation  

---

## 📊 Dataset Description

The dataset includes records from three e-commerce platforms with fields such as:

- Product category and platform
- Order and delivery dates
- Delivery status and refund requests
- Customer feedback sentiment
- Revenue, units, and order quantity
- Service ratings and delivery time

---

## 🧹 Data Cleaning & Enrichment (ETL)

Using Power Query:
- Removed null or blank records  
- Renamed and reformatted columns  
- Extracted delivery performance metrics  
- Derived new fields like:
  - `Order Delay Status`  
  - `Sentiment Label`  
  - `Delivery Time (hrs)`  

---

## ⚙️ DAX Measures Developed

- Total Revenue  
- Total Orders  
- Average Delivery Time  
- Refund Rate  
- Positive/Negative Sentiment Count  
- Delayed Orders %  
- Average Service Rating  
- Delivery Delay Rate  
- Platform-Wise KPIs  

---

## 🖥️ Dashboard Structure

The report is organized into the following sections:

### 1. Executive Summary  
- Platform-wise KPIs (Orders, Revenue, Ratings)  
- Revenue by Category  
- Order Delay and Refund Overview  

  <img width="700" alt="Dashboard Screenshot" src="https://github.com/user-attachments/assets/54f6e759-4548-47d9-935c-8db0cfae097e" />


### 2. Delivery & Refund Analysis  
- Refund Requests Distribution  
- Delivery Delay Rate  
- Average Delivery Time and Ratings  

### 3. Customer Sentiment Analysis  
- Feedback Type Breakdown  
- Positive vs Negative Feedback  
- Category-wise Sentiment Distribution  

---

## 💡 Key Insights

- All three platforms contribute nearly equally to overall revenue (~19.6M–19.8M)  
- **Personal Care** and **Grocery** are the highest-selling categories  
- **13.67%** of total orders were delayed  
- **54%** of orders had no refund requests  
- Customer sentiment is overwhelmingly **positive**, with over 84.6K positive reviews

---

## 🔍 Evaluation & Results

- Dashboard is responsive and filters apply instantly  
- Design supports both high-level overviews and granular drill-down  
- Data model supports future data refreshes and scalability  

---

## 🧠 Lessons Learned

- Maintaining a clean data model ensures fast loading  
- DAX formulas for delay % and refund rates helped uncover key inefficiencies  
- Integrating customer sentiment improves actionable insights for business decisions  

---

## 🧭 Future Enhancements

- Add **real-time order tracking** via APIs  
- Integrate **regional breakdown** via maps  
- Extend analysis to include **marketing campaign ROI**  
- Publish via **Power BI Service** for live online access  

---

## 📂 Repository Structure

```bash
📦 E-Commerce_Platform_Performance_Analysis
├── README.md
├── Ecommerce_Dashboard.pbix
├── datasets/
│   └── ecommerce_sample.csv
├── screenshots/
│   └── ecommerce_dashboard_overview.png

