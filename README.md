# Power-BI-Non-Moving-Inventory-App  

[View on Microsoft AppSource](https://appsource.microsoft.com/en-us/product/power-bi/dhyeyconsultingservicespvtltd1584430919382.non-moving-inventory?tab=Overview)  

[![Watch the Demo](https://img.youtube.com/vi/T_0sLEIHjvY/0.jpg)](https://youtu.be/T_0sLEIHjvY?si=UGXdkSDGTYVogHVT)  

---

## Overview  

Excess and aging inventory can lock up working capital and reduce operational agility. The **Non-Moving Inventory Dashboard** helps supply chain and inventory managers detect slow- and non-moving items by comparing purchase and usage data, aging patterns, and stock buildup.  

This Power BI app brings clarity to stock utilization, supports smarter reordering, and empowers teams to take proactive steps toward stock optimization and clearance.  

---

## Technical Framework  

The dashboard uses a structured model titled **Purchase Data** that captures all critical dimensions needed for stock movement analysis.  

**Key components:**  
- **Data Source:** Excel file or ERP export tracking item-level purchases, usage, and COGS  
- **Data Preparation (Power Query):**  
  - Cleaned and standardized dates  
  - Computed remaining inventory (Purchased – Used)  
  - Assigned purchase age buckets: 0–30, 31–60, 61–90, and 90+ days  
  - Enabled item-level aggregation across months and years  
- **Data Model Dimensions:**  
  - Purchase ID  
  - Purchase Item  
  - Purchase Date  
  - Quantity Purchased  
  - Quantity Used  
  - Inventory Remaining  
  - Purchase Age Bucket  
  - COGS (optional for valuation)  

The model allows age-based filtering and comparison of stock status across time periods.  

---

## Interactive Filters  

The dashboard features key slicers for better data slicing:  
- **Year Filter:** View data for a selected year  
- **Month Filter:** Drill into specific purchase periods  
- **Purchase Item Filter:** Focus on individual SKUs or product lines  

These filters help target specific inventory zones for review, clearance, or reorder pause.  

---

## Dashboard Highlights  

**Column Chart – Quantity Purchased vs. Quantity Used**  
- Compare item-level inflow and outflow  
- Quickly identify products with poor movement or over-purchase  

**Matrix – Inventory by Purchase Age Bucket**  
- View how long stock has remained idle  
- Spot aging clusters that need clearance or process review  

**Line Chart – Purchase Trend Over Time**  
- Time-series view of procurement activity by month and year  
- Track stock buildup trends in relation to usage cycles  

This dashboard is essential for any company aiming to maintain a lean, efficient, and cost-effective inventory system—enabling better purchasing decisions, warehouse space planning, and capital utilization.  

---

## Screenshots  

### Dashboard Overview 
![Purchased vs Used](https://github.com/SuperfiedStudd/Power-BI-Non-Moving-Inventory-App/blob/main/docs/dashboard_overview.png?raw=true)  

### Quantity Bar Graph  
![Quantity Bar Graph](https://github.com/SuperfiedStudd/Power-BI-Non-Moving-Inventory-App/blob/main/docs/quantitygraph.png?raw=true)  

### Quantity Scatter Plot  
![Quantity Scatter Plot](https://github.com/SuperfiedStudd/Power-BI-Non-Moving-Inventory-App/blob/main/docs/quantityplot.png?raw=true)  

---

## How to Use  

This repository is intended as a showcase:  
1. Watch the demo video above for a walkthrough.  
2. Explore the screenshots for dashboard views.  
3. Try the published app directly on [Microsoft AppSource](https://appsource.microsoft.com/en-us/product/power-bi/dhyeyconsultingservicespvtltd1584430919382.non-moving-inventory?tab=Overview).  
   - You can download and play around with the app if you have a school or work account that supports Microsoft apps.  

---

## Why It Matters  

Non-moving stock directly impacts working capital and warehouse efficiency. This dashboard enables businesses to detect slow-moving items early, take corrective measures, and optimize procurement for a leaner inventory model.  

---

## Author  

Developed by **Jasjyot Singh**  
Contact: jasjyotsingh.work@gmail.com  
