---

# 🧾 Power BI Retail Sales Analytics Dashboard (Live PostgreSQL Connection)

## 📊 Overview

This Power BI dashboard provides an interactive and real-time view of **Product Sales Analytics** using a live connection to a **PostgreSQL** database. It helps stakeholders analyze total sales, profits, customer ratings, sales by product categories and subcategories, and performance across countries and states.

---

## 🛠️ Features

- 💸 **Total Sales, Profit & Discounts** metrics
- 🌍 **Country-wise** sales breakdown (Canada, Germany, India, UK, USA)
- 🛍️ **Top Performing Categories** (Books, Clothing, Sports, Electronics, Home & Kitchen)
- 🗂️ **Subcategory Analysis** by country
- 🧾 **Payment Method Distribution** (Cash, Credit Card, Online)
- 👤 **Age Group Filter**
- 🏙️ **State-wise Sales** with category filter
- 📈 Real-time updates via live PostgreSQL connection

---

## 🧬 Data Source

- **Database**: PostgreSQL
- **Connection Mode**: *DirectQuery* (Live connection)
- **Table Structure**: Includes tables for `sales`, `products`, `customers`, `countries`, and `payments`.

---

## 🧱 Requirements

- Power BI Desktop (latest version)
- PostgreSQL ODBC driver
- PostgreSQL credentials (host, port, username, password, database)

---

## ⚙️ How to Use

1. **Clone or Download the Repository**  
   Clone this project or download the `.pbix` Power BI report file.

2. **Install PostgreSQL ODBC Driver**  
   Download and install the latest [PostgreSQL ODBC Driver](https://odbc.postgresql.org/).

3. **Open in Power BI Desktop**  
   Open the Power BI report `.pbix` file.

4. **Update Database Connection**  
   - Go to `Transform Data` → `Data Source Settings`.
   - Edit the PostgreSQL connection settings (hostname, database, username, password).
   - Click `Apply` to reconnect using your own credentials.

5. **Refresh Data**  
   Since the report uses DirectQuery, it will automatically pull fresh data with each interaction.

---

## 📂 Folder Structure

```
Product-Sales-Analytics/
├── README.md
├── Product_Sales_Analytics.pbix
└── SQL_Scripts/
    └── create_tables.sql
    └── sample_data.sql
```

---

## 📸 Dashboard Preview
![Screenshot 2025-04-13 164416](https://github.com/user-attachments/assets/689d48f2-4119-4c75-b68c-533f1598a197)
*Interactive view of sales performance by country, category, subcategory, and payment method.*

---

## 🔒 Security

Ensure your PostgreSQL instance is secured and that the user account used for Power BI has read-only access if needed.

---

## 👨‍💻 Author

Created by [Allapu Srivarshan]  
Contact: [allapuramesh68@gmail.com]

---
