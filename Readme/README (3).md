# 🛍️ E-commerce Sales Analysis — Power BI Dashboard

An interactive Power BI dashboard that analyzes e-commerce sales across states, customers, product categories, sub-categories and payment modes, with quarter and state filters.

> **Built by:** Sunil Luhar — MIS & Data Reporting | Power BI • Excel • SQL • Looker Studio
> **Live dashboard:** [Click here to view](PASTE-YOUR-POWER-BI-PUBLISH-TO-WEB-LINK-HERE)

---

## 📸 Dashboard Preview

![E-commerce Sales Dashboard](screenshots/dashboard.png)

---

## 🎯 Project Objective

To combine two raw data tables (orders and order details) into one dashboard that helps a business user answer questions such as:

- How much are we selling, and how much profit are we making?
- Which states and customers bring the most sales?
- Which categories and sub-categories are the most profitable?
- How do customers prefer to pay (COD, UPI, cards, EMI)?
- How does performance change by month and quarter?

---

## 📊 Key Features

- **KPI cards:** Total Amount, Total Quantity, Total Profit, Average Order Value (AOV)
- **Amount by State:** Bar chart
- **Amount by Customer:** Column chart
- **Quantity by Category:** Donut chart
- **Quantity by Payment Mode:** Donut chart
- **Profit by Month:** Column chart (negative months highlighted)
- **Profit by Sub-Category:** Bar chart
- **Filters:** Quarter buttons (Qtr 1 to Qtr 4) and a State dropdown
- **Custom dark theme** with a consistent color palette

---

## 🔎 Sample Insights (full year 2018, no filters)

- The data covers **500 orders**, **1,500 order lines**, **336 customers** and **19 states**.
- Total amount is **437,771**, total profit is **36,963** and total quantity is **5,615**.
- **Maharashtra** (102,498) and **Madhya Pradesh** (87,463) are the top states by amount, followed by **Uttar Pradesh** (38,362).
- **Clothing** makes up about **63%** of quantity sold, yet **Electronics** earns almost the same profit (13,162 vs 13,325) with only about 21% of the quantity.
- **Printers (8,606)** and **Bookcases (6,516)** are the most profitable sub-categories.
- **Cash on Delivery** is the most used payment mode (about **44%** of quantity), followed by **UPI** (about **21%**).

*(Add your own insights after exploring the quarter and state filters.)*

---

## 🛠️ Tools & Skills Used

| Area | Details |
|---|---|
| Tool | Microsoft Power BI Desktop |
| Data preparation | Power Query (loading CSV files, setting data types) |
| Data modeling | Two related tables (Orders and Details) joined on Order ID |
| Calculations | Total Amount, Quantity, Profit and Average Order Value |
| Visuals | KPI cards, bar, column and donut charts, quarter buttons, state slicer |
| Design | Custom dark theme, consistent colors, clear layout |

---
---

## 📂 Data Description

This project uses a sample dataset for learning and portfolio purposes. It does not contain real customer or company information.

**Orders.csv** (500 rows)

| Column | Meaning |
|---|---|
| Order ID | Unique order number |
| Order Date | Date of the order (day-month-year, year 2018) |
| CustomerName | Name of the customer |
| State | State of the order |
| City | City of the order |

**Details.csv** (1,500 rows)

| Column | Meaning |
|---|---|
| Order ID | Links to the Orders table |
| Amount | Sales amount of the order line |
| Profit | Profit of the order line (can be negative) |
| Quantity | Number of items |
| Category | Clothing, Electronics or Furniture |
| Sub-Category | Product sub-category (17 in total) |
| PaymentMode | COD, UPI, Credit Card, Debit Card or EMI |

---

## ▶️ How to Open the Dashboard

1. Download or clone this repository.
2. Install **Power BI Desktop** (free) from Microsoft.
3. Open `ecommerce_sales_dashboard.pbix`.
4. If Power BI asks for the data source, go to **Home → Transform data → Data source settings** and point both tables to the CSV files in the `data/` folder.

---

📬 Contact

Available for freelance Power BI, Excel and reporting projects on Upwork and Fiverr.

Name: Sunil Luhar
LinkedIn: www.linkedin.com/in/sunil-luhar-b7ab69383
Upwork:(https://www.upwork.com/freelancers/~012da964e093fca48f)
Fiverr: https://www.fiverr.com/s/Q2rQrN1
Email: luharsunil965@gmail.com
