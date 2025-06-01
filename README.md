# 🇮🇳 Indian Sales Dashboard – Python + Tableau Project

An interactive Sales Dashboard built using **Python** and **Tableau**, based on synthetic retail sales data across Indian regions and cities.

---

## 🛠️ Tools & Technologies Used

- 🐍 **Python**: Data generation using Faker and Pandas
- 📊 **Tableau**: Interactive dashboard creation
- 💾 **CSV**: Used as a bridge between Python and Tableau

---

## 🧪 Python Data Generation

The dataset (`indian_sales_data.csv`) was created using Python with the help of the `Faker` library to simulate realistic retail transactions. Each row represents a fictional order with:

- Order ID
- Customer Name
- City / Region
- Order Date
- Product Category / Subcategory
- Quantity
- Sales and Profit (randomized)
- Payment Mode


## 📊 Dashboard Features (Built in Tableau)

- 💰 **KPI Cards**: Total Sales, Profit, Orders
- 📈 **Sales Trend**: Monthly sales line chart
- 🗃️ **Sales by Category/Subcategory**: Bar or Treemap view
- 🏙️ **Top 10 Cities by Sales**: Ranked bar chart
- 📌 **Region-wise Profit**: Color-coded bar chart (Red-Green)
- 🗺️ **City-wise Map View**: Bubble map sized by sales
- 🔍 **Interactive Filters**: Region, Category, Subcategory, Date range

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `indian_sales_data.csv` | Synthetic retail sales dataset (Python-generated) |
| `sales_dashboard.twbx` | Tableau packaged workbook |
| `README.md` | Project overview and documentation |

---


## 🚀 How to Run the Project

1. Clone or download this repo
2. Open `sales_dashboard.twbx` in [Tableau Public](https://public.tableau.com](https://public.tableau.com/shared/66DQ6XS63?:display_count=n&:origin=viz_share_link)
3. Explore charts, maps, KPIs, and filters
4. To regenerate data, run Python script 

---

