# 📊 E-Commerce Sales Analysis

An interactive Power BI dashboard analyzing e-commerce sales data — covering revenue, profit, customer demographics, and payment behavior for orders placed throughout 2018.

## 📁 Project Overview

This project explores order-level sales data from an Indian e-commerce platform, combining order details (customer, location, date) with product-level transaction data (category, amount, profit, payment mode) to uncover sales trends and business insights.

| Metric | Value |
|---|---|
| Total Orders | 500 |
| Total Line Items | 1,500 |
| Total Sales | ₹4,37,771 |
| Total Profit | ₹36,963 |
| Total Quantity Sold | 5,615 units |
| Date Range | Jan 2018 – Dec 2018 |
| States Covered | 19 |
| Cities Covered | 25 |
| Product Categories | 3 (Electronics, Clothing, Furniture) |
| Sub-Categories | 17 |
| Payment Modes | 5 (COD, UPI, Debit Card, Credit Card, EMI) |

## 🗂️ Files in this Repository

| File | Description |
|---|---|
| `Orders.csv` | Order-level data — Order ID, Order Date, Customer Name, State, City |
| `Details.csv` | Product/transaction-level data — Order ID, Amount, Profit, Quantity, Category, Sub-Category, Payment Mode |
| `E-commerce Sales Dashboard.pbix` | Power BI dashboard file with interactive visuals built on the combined dataset |

The two CSV files are joined on **Order ID** to build a complete picture of each transaction.

## 📈 Key Insights

- **Electronics** is the top-performing category by revenue (₹1,66,267), followed by Clothing (₹1,44,323) and Furniture (₹1,27,181).
- **Clothing** delivers the highest profit (₹13,325) despite lower sales than Electronics — suggesting stronger margins.
- **Maharashtra** and **Madhya Pradesh** are the top two states by sales, together contributing close to half of total revenue among the top states.
- **Cash on Delivery (COD)** is by far the most common payment mode (684 transactions), followed by UPI (331) — reflecting typical e-commerce payment preferences in the Indian market.
- Data spans the full 2018 calendar year, allowing for month-over-month and seasonal trend analysis.

## 🛠️ Tools Used

- **Power BI** — data modeling, DAX measures, and interactive dashboard/report visuals
- **CSV / Excel** — raw source data

## 🚀 How to Use

1. Clone or download this repository.
2. Open `E-commerce Sales Dashboard.pbix` in [Power BI Desktop](https://www.microsoft.com/en-us/power-platform/products/power-bi/desktop) (free download).
3. Explore the interactive visuals — filter by category, state, payment mode, or date range.
4. To rebuild the model from scratch, import `Orders.csv` and `Details.csv` into Power BI and join them on the `Order ID` column.

## 📌 Dashboard Highlights

The `.pbix` file includes visuals such as:
- Sales & Profit by Category / Sub-Category
- Sales trend over time (monthly/quarterly)
- Top states and cities by revenue
- Payment mode distribution
- Order and quantity summaries with slicers for interactive filtering

## 📄 License

This project is open for learning and portfolio purposes. Feel free to fork and adapt it for your own analysis.

---
*Built as a data analytics portfolio project to demonstrate skills in data modeling, DAX, and dashboard design using Power BI.*
