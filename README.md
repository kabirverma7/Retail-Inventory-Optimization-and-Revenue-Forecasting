
# 🛒 Retail Inventory Optimization & Sales Forecasting

This project focuses on analyzing sales and inventory data from a retail business, identifying overstock/stockout risks, and forecasting product demand using time series modeling. The goal is to drive efficient inventory planning and reduce lost revenue.

---

## 📊 Dataset

- **Synthetic Dataset** generated for 50 products across 5 regions over 1 year.
- Key Columns: `date`, `region`, `product_id`, `category`, `units_sold`, `price_per_unit`, `revenue`, `inventory_level`
- [Download dataset here](./data/retail_sales_data.xlsx)

---

## 🧰 Tools & Technologies

- **Python**: pandas, matplotlib, seaborn, prophet
- **Power BI**: Dashboarding & KPI visualization
- **Excel**: Data preview & initial checks
- *(Optional)* SQL for filtering and joins

---

## 🔄 Project Workflow

### 1. 📦 Data Cleaning & EDA
- Converted dates, handled missing values, standardized product & region names
- Analyzed product-wise sales, seasonal trends, and regional performance

### 2. 📈 Time Series Forecasting
- Used Facebook Prophet to predict 30-day product sales
- Identified products with high volatility and seasonal spikes

### 3. 📦 Inventory Turnover Analysis
- Calculated turnover ratios: `units_sold / average_inventory`
- Flagged overstocked and understocked products

### 4. 📊 Power BI Dashboard
- Visualized:
  - Daily/Monthly Sales
  - Forecasted vs Actual Units Sold
  - Inventory Health by Product/Region
- Filters: Region, Product ID, Category, Date

---

## 📌 Key Insights

- 🔺 **10% of products** account for **60% of revenue**
- ⚠️ Several products show **high stock but low sales** → Overstock risk
- 📉 Understocked fast-sellers causing **lost sales**
- 📅 Forecasts help **prevent seasonal stockouts**

---

## 📂 Folder Structure

```
retail-inventory-forecasting/
│
├── data/
│   └── retail_sales_data.xlsx
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda_visualizations.ipynb
│   └── 03_sales_forecasting.ipynb
├── dashboard/
│   └── PowerBI_dashboard.pbix
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

1. Clone this repo
2. Install requirements: `pip install -r requirements.txt`
3. Run notebooks step-by-step
4. Open `.pbix` file in Power BI for dashboard

---

## 📫 Contact

**Kabir Verma**  
[LinkedIn](https://linkedin.com/in/kabir-verma-1132b724a) | [GitHub](https://github.com/kabirverma7)

---
