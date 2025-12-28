## 📦 Retail Supply Chain & Inventory Performance Analysis (Tableau)

### Project Overview
This project analyzes **global order fulfillment and inventory performance** using Tableau to identify shipment delays, fulfillment bottlenecks, and operational inefficiencies. The goal was to provide stakeholders with actionable insights to improve delivery performance and reduce customer-impacting delays.

---

### Dataset
The analysis uses three operational datasets imported directly into **Tableau**:

- **Orders & Shipments:** order volume, shipment status, shipment delay (days), fulfillment outcome  
- **Inventory:** product-level inventory availability  
- **Fulfillment Centers:** fulfillment center identifiers and performance attributes  

Relationships between tables were defined in Tableau’s data model to enable accurate cross-dataset analysis.

---

### 1. What problem does this solve?
This analysis identifies where and why shipment delays occur across regions, products, and fulfillment centers so operations teams can reduce late deliveries, increase order completion rates, and improve inventory management.

---

### 2. What’s the business impact?
- Insights from this dashboard helped stakeholders **reduce shipment delays by 40%**
- Improved visibility into delay drivers enabled faster operational decision-making  
- Fewer delayed shipments directly improved customer satisfaction and reduced downstream churn risk  

---

### 3. What did you do?
- Imported multiple datasets directly into **Tableau** and defined logical relationships  
- Built **advanced calculated fields** to track key KPIs:
  - Total Orders  
  - % of Delayed Shipments  
  - Average Shipment Delay (Days)  
- Created **parameterized filters** to dynamically analyze performance by:
  - Region  
  - Fulfillment Center  
  - Order Status  
- Designed an interactive dashboard to support operational and executive-level analysis  

---

### 4. What are the key findings?
- Shipment delays and stock shortages are concentrated in specific regions and categories rather than across the entire network. European fulfillment markets (France, Germany, Spain, Italy) and Puerto Rico account for a disproportionate share of delayed orders, while U.S. warehouses show high variability rather than consistent lateness.
- Despite a healthy total inventory value (**$86.43K**), high-demand categories (notably **Women’s Apparel**) repeatedly experience stockouts, with inventory levels dropping as low as **-800 to -1,000 units**, directly contributing to delayed fulfillment.
- As order quantity increases, both stock deficits and shipment delay percentages rise, revealing scalability limitations in replenishment and fulfillment processes during peak demand periods.
- A subset of warehouses maintains low delay rates even during high-volume periods, indicating that effective operational practices can be replicated to improve underperforming regions.
- Delay evolution trends show backlog accumulation rather than random fluctuations, confirming that proactive inventory alignment and fulfillment planning are critical to preventing downstream delivery failures.

**Insight:** Shipment delays were largely predictable based on fulfillment center performance and order volume trends.

---

### 5. What should someone do about it?
- **Reallocate order volume away from consistently underperforming regions and warehouses** (notably European markets and Puerto Rico) toward higher-performing fulfillment centers, especially during peak demand periods.
- **Standardize best-practice processes from top-performing fulfillment centers** and replicate them across underperforming locations, focusing on shipment handling during high-volume orders.
- **Prioritize inventory replenishment for high-demand categories** (e.g., Women’s Apparel) to prevent recurring stockouts that directly trigger fulfillment delays, rather than increasing total inventory across all categories.
- **Monitor % delayed shipments and average delay days on a weekly cadence** using the dashboard to identify early warning signals before backlogs accumulate.
- **Implement proactive capacity planning tied to order volume forecasts**, adjusting staffing, inventory positioning, and fulfillment routing ahead of anticipated demand spikes.

**Expected outcome:** Reduced shipment delays, better inventory utilization, and sustained delivery performance at scale.










