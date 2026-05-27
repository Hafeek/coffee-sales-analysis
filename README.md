# coffee-sales-analysis

# Coffee Shop POS Sales Analytics Dashboard | Excel

### 📌 Problem Statement
Analyzed retail POS data for a coffee shop to track product performance, daily sales trends, and transaction patterns using Excel Pivot Tables & Charts.

### 🛠️ Tools Used
- **Excel:** Pivot Tables, Pivot Charts, Slicers, Data Modeling
- **Domain:** Retail Analytics, POS Data, Food & Beverage KPIs

### 📊 Key Metrics & Insights

#### **Dashboard Components**
| Component | Type | Business Meaning |
| --- | --- | --- |
| Total Bills Trend | Line Chart | Peak traffic at Store/Date 71 with ~3000 transactions |
| Product Sales | Bar Chart | Brazilian Coffee & Chocolate items = top sellers ~15K units |
| Category Share | 3D Pie Chart | Coffee Brazilian Lg & Rg dominate revenue mix |
| Day Filter | Slicer | Saturday selected – used for weekend analysis |
| Transaction Filter | Slicer | Drill down to txn_id 3293-3298 for order audit |

#### **Critical Business Insights**
1. **Top Products:** `Coffee Brazilian Lg` & `Coffee Brazilian Rg` are highest selling SKUs with 33K+ units combined  
   → **Action:** Ensure inventory for Brazilian coffee beans. Launch ‘Brazilian Week’ promo.

2. **Traffic Peak:** Bills spiked at point 71 vs avg 2000  
   → **Action:** If 71 = Store ID, replicate its layout. If 71 = Date, check marketing event.

3. **Category Mix:** High SKU variety seen in pie chart with 15+ slices  
   → **Action:** Do 80/20 analysis. Delist bottom 20% products to reduce waste.

4. **Weekend Focus:** Dashboard filtered for Saturday  
   → **Action:** Indicates weekend rush. Schedule 2x baristas on Sat.

### 🎯 Recommendations for Store Manager
1. **For Brazilian Coffee:** Bundle with Croissant to lift low-selling bakery items.
2. **For Peak Hours:** Use transaction_id slicer to find exact time of 3000-bill spike.
3. **For Menu:** Remove bottom 5 products using pie chart data to cut costs.

### ⚠️ Data Quality Observations
Identified 3 issues showing Excel data modeling skills:
1. `Sum of Length` used instead of `Sum of Sales/Quantity` – metric incorrect.
2. `Sum of store_id` = 0 – IDs should not be summed. Use Count or Revenue.
3. Chart titles generic 'Total' – should be descriptive like 'Sales by Product'.
Fixed version would use proper measures and KPI names.

### 📂 Files in Repo
1. `coffee_pos_data.xlsx` – Raw POS dataset + Dashboard
2. `dashboard.png` – Screenshot for recruiters
3. `improved_version.xlsx` – Fixed with correct measures

### 🎯 Skills for TCS/HCL/Infosys Retail Analytics Roles
POS Data Analysis, Excel Pivots, Slicers, KPI Tracking, Data Quality Audit, Category Management, Business Storytelling

---
**Connect:** [Your LinkedIn] | **Note:** Project demonstrates Excel dashboarding + data audit skills for retail clients like Starbucks, CCD, Barista.
