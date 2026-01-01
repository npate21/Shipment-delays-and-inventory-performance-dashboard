## 📦 Retail Supply Chain & Inventory Performance Analysis (Tableau)

### Project Overview
This project analyzes global order fulfillment and inventory performance using Tableau to identify shipment delays, fulfillment bottlenecks, and operational inefficiencies across a fictional retail supply chain. The analysis provides actionable insights that would enable operations teams to improve delivery performance and reduce customer-impacting delays.

---

### Dataset
The analysis uses three operational datasets imported directly into **Tableau**:

- **Orders & Shipments (30K+ records):** order status, shipment timing, fulfillment outcomes, customer/warehouse geography
- **Inventory (4.2K records):** product-level stock availability by month and warehouse
- **Fulfillment (118 records):** product-warehouse fulfillment time benchmarks

Relationships between tables were defined in Tableau’s data model to enable accurate cross-dataset analysis.

---

### 1. What problem does this solve?
This analysis identifies where and why shipment delays occur across regions, products, and fulfillment centers so operations teams can reduce late deliveries, increase order completion rates, and improve inventory management.

---

### 2. What’s the business impact?
- Provides visibility into delay patterns across 30K+ orders and $86.43K inventory.
- Enables data-driven decisions on warehouse reallocation and inventory replenishment priorities.
- Supports operational planning by revealing correlation between order volume spikes and fulfillment constraints.
  
---

### 3. What did you do?
- Imported three datasets into **Tableau** and established relationships using Product Name as the linking field
- Built **advanced calculated fields** to track key KPIs:
  - Total Orders  
  - % of Delayed Shipments  
  - Average Shipment Delay (Days)
  - Inventory Deficit/Surplus by Product Category
- Created **parameterized filters** to dynamically analyze performance by:
  - Warehouse Country 
  - Product Category (Top N)
  - Time Period
- Designed two interactive dashboards:
  - **Shipment Analysis Dashboard**: geographic delay patterns, delay evolution over time, order quantity correlation
  - **Inventory Analysis Dashboard**: supply vs. demand visualization, stock level trends, fulfillment time metrics

---

### 4. What are the key findings?
-  61% of orders experienced delays with an average of 0.5 days late. However, this overall average conceals extreme regional variation—European markets (France, Germany, Spain, Italy)    and Puerto Rico show consistently higher delays while some U.S. warehouses ship early, offsetting the network average.
-  **Inventory-fulfillment misalignment**: Despite healthy total inventory value ($86.43K) and average fulfillment time of 5.3 days, high-demand categories (notably Women's Apparel)       experience stockouts reaching -814 units, directly causing fulfillment delays.
-  **Order volume correlation**: As order quantity increases, both inventory deficits and delay percentages rise, revealing scalability limitations in replenishment and fulfillment        processes during peak demand periods.
-  **Performance variability**: Top-performing warehouses maintain low delay rates even during high-volume periods, indicating that effective operational practices exist and could be      replicated to improve underperforming regions.

**Insight:** Shipment delays were largely predictable based on fulfillment center performance and order volume trends.

---

### 5. What should someone do about it?
- **Reallocate order volume away from consistently underperforming regions and warehouses** (notably European markets and Puerto Rico) toward higher-performing fulfillment centers, especially during peak demand periods.
- **Standardize best-practice processes from top-performing fulfillment centers** and replicate them across underperforming locations, focusing on shipment handling during high-volume orders.
- **Prioritize inventory replenishment for high-demand categories** (e.g., Women’s Apparel) to prevent recurring stockouts that directly trigger fulfillment delays, rather than increasing total inventory across all categories.
- **Monitor % delayed shipments and average delay days on a weekly cadence** using the dashboard to identify early warning signals before backlogs accumulate.
- **Implement proactive capacity planning tied to order volume forecasts**, adjusting staffing, inventory positioning, and fulfillment routing ahead of anticipated demand spikes.

**Expected outcome:** Reduced shipment delays, better inventory utilization, and sustained delivery performance at scale.










