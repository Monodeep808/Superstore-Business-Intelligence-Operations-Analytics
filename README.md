# Superstore Management System — Exploratory Data Analysis (EDA)

* Corporate-Grade Exploratory Data Analysis: Built an end-to-end Python data pipeline using Pandas and NumPy to ingest, clean, and analyze a corporate-scale database of 1,000 transactional orders, managing 25 core business features including fulfillment tracking, stock volumes, and profit metrics.

*  Revenue & Profit Optimization: Conducted deep-dive statistical analytics revealing 12.7M in total sales and 3.18M in total profit, isolating Grocery as the top-performing category and identifying Home Office as the highest-value customer segment.

*  Predictive Stock Automation & Logic: Engineered business logic utilizing operational constraints to track regional supply chains, mapping distribution across the North region (the top-performing territory) and scripting conditional triggers to flag low-inventory scenarios (Stock Left < 10) for auto-reordering.

*   Advanced Interactive BI Dashboards: Developed highly responsive visualization suites using Matplotlib, Seaborn, and Power BI, transforming granular multidimensional features like shipping lifecycles, profit margin ratios (25.02% average), and promotional discount tiers into clean corporate dashboards.

## 📊 Business Insights Discovered
*   **Total Sales Realized:** $12.7M
*   **Total Profit Captured:** $3.18M (Healthy **25.02% average profit margin**)
*   **Top Performing Category:** Grocery
*   **Highest Value Territory:** North Region
*   **High-Value Segment:** Home Office

---

## 🛠️ Tech Stack & Architecture
*   **Language:** Python 3.x
*   **Data Manipulation:** Pandas, NumPy
*   **Data Visualization:** Matplotlib, Seaborn
*   **Development Environment:** Jupyter Notebook / VS Code

---

## 📈 Visualizations & Key Findings

### 1. Sales vs. Profit Performance
Evaluating total gross sales alongside bottom-line profit margins across different lines of business. While electronics drive significant volume, grocery operations capture the tightest optimization spread.
![Sales vs Profit]: <img width="800" height="400" alt="Sales vs Profit" src="https://github.com/user-attachments/assets/49b417ba-7289-4f29-a2d9-118037f5013e" />


### 2. Regional Performance Matrix
Mapping order distribution density (bar charts) directly against real-time profit margins (line charts) across core operating territories to pinpoint geographical variance.
![Regional Performance]: <img width="800" height="400" alt="Regional Performance Matrix" src="https://github.com/user-attachments/assets/bdcb3fd8-4291-4ed2-aaed-ec2689bdc352" />


### 3. Discount Decay Curve
An operational analysis tracing the point of diminishing returns where promotional discount adjustments directly decay bottom-line profit performance.
![Discount Decay Curve]: <img width="800" height="400" alt="Discount_decay_curve" src="https://github.com/user-attachments/assets/4b9f8293-c67b-44ea-b12b-2708c15e58e9" />

---

## 📂 Core Features & Project Layout

### 1. Synthetic Data Factory (`data_generator.py`)
To pressure-test enterprise-grade BI logic, a custom synthetic data factory script was engineered. Using programmatic rules, it simulates a production-grade schema across 25 dimensional and operational variables (e.g., Delivery Status, Payment Modes, Stock Levels, and Conditional Automation metrics).

### 2. Exploratory Data Analysis (`EDA_Superstore.ipynb`)
*   **Data Cleansing & Preprocessing:** Handles missing values, optimizes data types, and normalizes financial columns (Sales Amount, Cost Price, Profit) for error-free analytical modeling.
*   **Profitability Analysis:** Pinpoints variations across customer segments and product categories to isolate high-margin units.
*   **Discount Optimization Matrix:** Evaluates how varying discount scales (`Discount (%)`) correlate directly with bottom-line profit erosion.
*   **Logistics & Supply Chain Auditing:** Tracks fulfillment lifecycles (Delivered, Pending, Returned) to expose operational friction points.

### 3. Predictive Reorder Logic
Includes programmed algorithmic logic simulating smart warehouse operations:
*   Triggers conditional automated flags (`Auto Reorder = Yes`) when inventory levels (`Stock Left`) fall below a critical threshold of 10 units.

---

## 📊 Interactive Power BI Dashboard (`EDA Dashboard.pbix`)

In addition to the programmatic Python analysis, an enterprise-grade interactive dashboard was engineered in **Power BI** to provide non-technical stakeholders with self-service business intelligence capabilities.

### Key Dashboard Capabilities:
*   **Dynamic Executive KPI Cards:** Real-time tracking of Total Revenue ($12.7M), Total Net Profit ($3.18M), and overall Profit Margin performance (25.02%).
*   **Fulfillment Cross-Filtering:** Interactive matrix mapping order delivery statuses (*Delivered, Pending, Returned*) to isolate geographical friction points and regional supply chain backlogs.
*   **Transactional Granularity:** Drill-down matrices tracking customer segmentation behavior against target product categories (Grocery, Electronics, Office Supplies, Furniture).

### Dashboard Preview:

1.Superstore Performmance Dahboard: <img width="1335" height="750" alt="Screenshot 2026-07-09 115908" src="https://github.com/user-attachments/assets/f18f194a-9ea4-45b8-9cf7-d7591ab3b20f" />

2. Inventory and Supplier Dashboard: <img width="1352" height="748" alt="Screenshot 2026-07-09 120344" src="https://github.com/user-attachments/assets/d30a2168-f1e8-41df-a7e0-595d1395ccf4" />

3. Customer Insights Dashboard: <img width="1290" height="733" alt="Screenshot 2026-07-09 121152" src="https://github.com/user-attachments/assets/736eeb98-6c49-4fcf-90a2-3249e7659ac5" />

> 💡 **Note:** To interact with the live charts, filters, and slicers, download the `EDA Dashboard.pbix` file from the repository root and open it locally via Power BI Desktop.
