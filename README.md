# Inventory-Supply-Chain-Management-Dashboard-Power-BI-
Created an interactive Power BI dashboard to visualize inventory levels, order fulfillment status, and key supply chain metrics (fill rate, backorder rate, DSI). Improved operational visibility and data-driven decision-making, reducing weekly reporting time by ~30%

<img width="1147" height="637" alt="image" src="https://github.com/user-attachments/assets/841c0c71-430e-4406-a5e6-f0bdb096fe76" />

# Inventory & Supply Chain Management Analysis (Power BI)

This project is an end-to-end **Supply Chain & Inventory Analytics** dashboard built in **Power BI**.  
It analyzes multi-year sales and operations data across regions, product categories and warehouses, and surfaces key KPIs like **warehouse utilization, DSI, inventory turnover, transportation cost, lead time and backorders**.

---

## 📊 Project Overview

The goal of this project is to give supply-chain stakeholders a **single interactive view** of:

- How efficiently warehouse capacity is being used  
- How quickly inventory is turning into sales  
- Where logistics costs are concentrated  
- How lead times differ by product category  
- How often orders are backordered or delayed  

The dashboard helps answer questions like:

- *“Which regions drive the highest logistics cost?”*  
- *“How fast do we sell inventory on average?”*  
- *“Which categories have the longest lead times?”*  
- *“What is our backorder rate and fulfillment performance?”*

---

## 🗂 Dataset

The analysis is based on a synthetic but realistic supply-chain dataset with:

- **1,200 records** (orders)  
- Years: **2020–2024**  
- **4 Regions:** North, South, East, West  
- **4 Product Categories:** Accessories, Clothing, Electronics, Furniture  

Key columns include:

- Units Sold  
- Inventory Level & Warehouse Capacity  
- Transportation Cost  
- Cost of Goods Sold (COGS)  
- Average Inventory  
- Lead Time (days)  
- Order Status (Fulfilled / Pending / Canceled)  
- Backorder flag (Yes/No)  
- Order Accuracy (True/False)

Files in this repo:

- `Inventory and Supply Chain Management Analysis.pbix` – Power BI report file  
- `Inventory_SupplyChain_Dataset.csv` – underlying dataset  
- `README.md` – project documentation (this file)  
- `images/dashboard.png` – exported screenshot of the main report page (optional)

---

## 📌 Dashboard Features

The main Power BI report page contains:

### 1. KPI Cards

- **Warehouse Utilization %**  
- **Days Sales of Inventory (DSI)**  
- **Inventory Turnover**

### 2. Warehouse Utilization Gauge

- Visualizes current warehouse utilization vs. 0–100% range.

### 3. Transportation Cost by Region & Category

- Clustered bar/column chart showing **Sum of Transportation Cost** split by region and category.

### 4. Units Sold by Year

- Line/area chart tracking **Units Sold (2020–2024)** to highlight growth trends.

### 5. Average Lead Time by Category

- Donut chart showing **Average Lead Time (days)** for each product category.

### 6. Count of Backorders by Order Status

- Column chart displaying **Backorder counts** across Fulfilled, Pending and Canceled orders.

### 7. Inventory Level by Category & Region

- Bar chart visualizing **Inventory Level** split by category (Clothing, Electronics, Furniture, Accessories) and region (East, North, South, West).

Each visual is fully interactive, with slicers for **Region** and **Category**.

---

## 📈 Key Statistics & Insights

From the dataset (rounded):

- **Average Warehouse Utilization:** ~**34–35%**  
  → Significant opportunity to use existing capacity better or consolidate warehouses.

- **Days Sales of Inventory (DSI):** ~**15.6 days**  
  → On average, inventory is sold within ~2 weeks.

- **Inventory Turnover:** roughly **23–31x per year** (depending on calculation)  
  → Indicates a fast-moving inventory profile.

- **Units Sold Growth (2020–2024):**  
  - 2020: **~54.9K units**  
  - 2024: **~198.4K units**  
  → Approx. **3.6× growth** in units sold over 5 years.

- **Backorders:**
  - **116 out of 1,200 orders (~9.7%)** experienced backorders.
  - Majority of backorders eventually move to **Fulfilled**, followed by Pending and Canceled.

- **Transportation Cost by Region (all categories):**
  - North: ~**2.50M**  
  - West: ~**2.44M**  
  - East: ~**2.27M**  
  - South: ~**2.07M**  
  → North & West are the most expensive logistics regions.

- **Average Lead Time by Category:**
  - Accessories: **16.6 days**  
  - Clothing: **15.3 days**  
  - Electronics: **15.7 days**  
  - Furniture: **15.5 days**  
  → Accessories have slightly longer lead times; potential optimization area.

These insights can drive decisions around **capacity utilization, stock allocation, supplier performance and logistics optimization**.

---

## 🛠️ How to Run the Report

1. **Clone or download** this repository.
2. Open `Inventory and Supply Chain Management Analysis.pbix` in **Power BI Desktop**.
3. If required, update the file path for `Inventory_SupplyChain_Dataset.csv`:
   - Home → Transform data → Data source settings → Change source.
4. Refresh the data:
   - Home → **Refresh**.
5. Interact with the slicers (Region, Category) and visuals to explore the data.

---

## 💼 Resume-Ready Summary (Optional)

You can describe this project on your resume as:

> **Inventory & Supply Chain Management Dashboard (Power BI)** – Built an interactive Power BI dashboard on a 1,200-record multi-year dataset (2020–2024) covering sales, inventory, transportation cost, lead time and backorders across 4 regions and 4 product categories. Created DAX measures for warehouse utilization, days sales of inventory (DSI), inventory turnover, backorder rate and logistics cost. Identified key insights including ~34% average warehouse utilization, ~15.6 days DSI, 3.6× growth in units sold (2020–2024) and ~9.7% backorder rate, with transportation cost highest in the North and West regions.

This hits ATS-friendly keywords such as:  
**Power BI, DAX, data modeling, inventory turnover, days sales of inventory, backorder rate, transportation cost, warehouse utilization, supply chain analytics, KPI dashboard.**

---

## 📫 Contact

If you have feedback or ideas for extending this dashboard (e.g., service level KPIs, forecast vs. actual, or more advanced DAX), feel free to open an issue or fork the repo.
