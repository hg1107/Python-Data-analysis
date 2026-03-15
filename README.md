# 🛒 Online Retail Sales Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-yellow)
![EDA](https://img.shields.io/badge/Project-Exploratory%20Data%20Analysis-green)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

An **Exploratory Data Analysis (EDA)** project that analyzes an **Online Retail transactional dataset** to uncover sales patterns, customer behavior, and revenue insights using **Python and data visualization libraries**.

This project demonstrates **data cleaning, preprocessing, feature engineering, and business insights extraction** from real-world retail data.

---

# 📊 Project Overview

The objective of this project is to analyze an **e-commerce retail dataset** and answer key business questions such as:

* How sales vary across months
* Which days generate the most revenue
* Customer purchasing patterns
* Product sales trends

The dataset contains **transaction-level records** including invoice numbers, product details, quantities, prices, and customer information.

---

# 📂 Project Structure

```
Online-Retail-EDA
│
├── index.ipynb
│   └── Jupyter Notebook containing full analysis
│
├── Online Retail.xlsx
│   └── Dataset used for the analysis
│
└── README.md
    └── Project documentation
```

---

# 📑 Dataset Description

Dataset: **Online Retail Dataset**

The dataset contains transactions of a UK-based online retail company.

| Column      | Description                         |
| ----------- | ----------------------------------- |
| InvoiceNo   | Invoice number for each transaction |
| StockCode   | Product identifier                  |
| Description | Product name                        |
| Quantity    | Number of items purchased           |
| InvoiceDate | Date and time of purchase           |
| UnitPrice   | Price per item                      |
| CustomerID  | Unique customer identifier          |
| Country     | Country where the purchase was made |

---

# ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

# 🧹 Data Cleaning

The raw dataset required several preprocessing steps:

### Removed Duplicate Records

Duplicate rows were removed to avoid incorrect aggregation.

### Handled Missing Values

Rows missing critical fields such as:

* Product Description
* Customer ID

were removed.

### Removed Invalid Transactions

Transactions with:

* Negative quantities
* Negative prices

were filtered out.

### Converted Data Types

Columns were converted into appropriate formats:

* `InvoiceDate → datetime`
* `CustomerID → string`

---

# 🧠 Feature Engineering

Additional features were created to enable deeper analysis.

### Revenue Calculation

```
Revenue = Quantity × UnitPrice
```

### Time-based Features

* Invoice Year
* Invoice Month
* Invoice Day
* Day of Week

These help identify **seasonal and behavioral sales trends**.

---

# 📊 Exploratory Data Analysis

The project includes multiple analytical insights.

### Key Metrics

* Total Revenue Generated
* Total Unique Customers
* Total Unique Products

---

### Monthly Revenue Trend

Sales were aggregated monthly to understand **seasonal growth patterns**.

Visualization: **Line Plot**

---

### Sales by Day of Week

Revenue distribution across days helps identify **peak shopping days**.

Visualization: **Bar Chart**

---

# 📌 Key Insights

Some insights from the analysis include:

* Sales show **strong seasonal trends**
* Certain weekdays generate **higher revenue**
* Data preprocessing significantly improves data quality
* Feature engineering helps reveal **hidden business patterns**

---

# 🚀 How to Run This Project

### 1️⃣ Clone the repository

```
git clone https://github.com/yourusername/online-retail-eda.git
```

### 2️⃣ Install dependencies

```
pip install pandas numpy matplotlib seaborn openpyxl
```

### 3️⃣ Launch Jupyter Notebook

```
jupyter notebook
```

Open:

```
index.ipynb
```

---

# 🎯 Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis
* Data Visualization
* Feature Engineering
* Working with real-world datasets

---

# 🔮 Future Improvements

Possible extensions:

* **Customer segmentation using RFM analysis**
* **Sales forecasting using time-series models**
* **Recommendation system for products**
* **Interactive dashboards using Power BI or Tableau**

---

# 👨‍💻 Author

This project was developed as part of a **Data Analysis portfolio project** to demonstrate practical skills in Python-based data analysis.

If you found this project helpful, consider giving the repository a ⭐.
