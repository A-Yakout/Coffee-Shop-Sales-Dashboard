# ☕ Coffee Shop Sales Dashboard

## 📌 Project Overview

As the owner of a growing chain of coffee shops, I needed a reliable and data-driven way to understand the performance of our stores, identify sales trends, and make informed decisions. I asked our analyst to build a reporting solution that would answer essential business questions and be easy to present to stakeholders.

This project involved:
- Cleaning and preparing raw transactional data using **SQL**
- Performing **Exploratory Data Analysis (EDA)** to uncover trends and patterns
- Creating an interactive **Power BI dashboard** for stakeholders

📊 [View the Dashboard]([https://github.com/A-Yakout/Coffee-Shop-Sales-Dashboard/blob/main/Coffe%20Shop%20Sales%20Dashboard.png?raw=true](https://github.com/A-Yakout/Coffee-Shop-Sales-Dashboard/blob/main/Coffe%20Shop%20Sales%20Dashboard.png))

---

## 🎯 Business Requirements

The business requirements for this project included:

1. **Clean and standardize the data** to ensure consistency and accuracy.
2. **Eliminate duplicate transactions** and handle any missing or null values.
3. **Track total sales and revenue by location** to evaluate store performance.
4. **Understand peak business hours** to optimize staffing and operations.
5. **Identify the most profitable days, months, and product categories**.
6. **Monitor revenue trends over time** to help forecast and plan promotions.
7. **Deliver a clear, visual dashboard** that can be used in management meetings.

---

## 🧹 Data Cleaning (SQL)

The data cleaning process included:

- Converting `transaction_date` and `transaction_time` to appropriate formats
- Formatting `unit_price` as a decimal
- Removing duplicate records using CTE and `ROW_NUMBER()`
- Checking and confirming absence of `NULL` values
- Adding a calculated `Revenue` column:  
  `Revenue = transaction_qty * unit_price`

---

## 📊 Exploratory Data Analysis (EDA)

Insights generated through SQL analysis:

- 🏬 Store performance by transaction count
- 📅 Revenue trends by **month**, **day**, and **quarter**
- 🕒 Sales patterns by **hour of day**
- 🔁 Month-over-month revenue comparison using window functions
- 🛍️ Product category and type performance

These insights were visualized in the Power BI dashboard to support business decisions.

---

## 🛠️ Tools Used

- **SQL Server** – Data cleaning and transformation
- **Power BI** – Data visualization and dashboard design

---

## 📂 Dataset Overview

The dataset includes:

- Store locations and IDs  
- Product details (category, type, and pricing)  
- Transaction timestamps and quantities  
- Sales revenue per transaction  

---

## ✅ Project Outcome

The dashboard provided a clear, visual representation of business performance. It helped identify:

- Top-performing stores  
- Busiest hours and days  
- Revenue trends across time  
- Strategic opportunities for growth

This empowered the business to make smarter, data-driven decisions and optimize operations across all locations.

---

## 👤 Contact

Made with ❤️ by **Abdelrhman Yakout**  
📎 [LinkedIn Profile](https://www.linkedin.com/in/abdelrhman-yakout-3099a932a/)

