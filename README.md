# Traffic-Accident-Analysis-Dashboard

An interactive data visualization dashboard designed to analyze traffic accident data, uncover high-risk trends, and identify key contributing factors such as location, time, day of the week, and environmental conditions.

---

## 📌 Features & Key Metrics

The dashboard provides a comprehensive overview of traffic incidents spanning from **2008 to 2013**, highlighting critical high-level KPIs and detailed categorical breakdowns:

### **High-Level KPIs**

* **Total Casualties:** 2,404K (2.4M+)
* **Total Accidents:** 1,687K (1.6M+)
* **Fatal Casualties:** 43K
* **Serious Casualties:** 2,024K (2.02M+)
* **YOY Accident Change:** +17.64%
* **Casualty Rate:** 142.54%

---

## 📊 Visualizations Included

### 1. Hotspot Location Analysis

* **Type:** Scatter / Cluster Plot
* **Purpose:** Maps the geographic density of accidents to identify high-risk zones, intersections, or regions requiring targeted infrastructure improvements.

### 2. Accidents by Hour of Day

* **Type:** Area / Line Chart
* **Purpose:** Tracks accident frequencies across a 24-hour cycle. Shows distinct peaks during morning and evening rush hours (around 8 AM and 4 PM–6 PM).

### 3. Casualties by Urban vs. Rural

* **Type:** Donut Chart
* **Purpose:** Compares the distribution of casualties across different regional environments, showing that Category 1 (Urban/Rural classification) accounts for nearly 60% of the total.

### 4. Accidents by Day of Week

* **Type:** Bar Chart
* **Purpose:** Tracks weekly trends, revealing that Friday sees the highest volume of incidents, while Sunday experiences the lowest.

### 5. Sum of Accident Severity by Light Conditions

* **Type:** Donut Chart
* **Purpose:** Correlates incident volume and severity with ambient light availability (e.g., daylight vs. darkness/streetlights). Over 75% of recorded severity data is concentrated in the primary lighting category.

### 6. Road Class & Weather Breakdown

* **Type:** Decomposition Tree / Network Flow
* **Purpose:** Breaks down the specific pathways of accidents based on road classifications (`1st_Road_Class`) and specific weather conditions to pinpoint exact risk combinations.

---

## 🛠️ Built With

* **Business Intelligence Tool:** Power BI / Tableau *(Modify based on your specific stack)*
* **Data Sources:** Historical traffic accident registries, road safety data (2008 - 2013).

---

## 🚀 How to Use the Dashboard

1. **Time Filtering:** Use the slider in the top right corner to filter data between the years **2008** and **2013**.
2. **Cross-Filtering:** Click on any specific day of the week (e.g., *Friday*) or a light condition segment to dynamically update the rest of the dashboard for that specific subset.
3. **Drill-Down:** Use the decomposition tree at the bottom center to expand road classes and investigate underlying weather data.


Dashboard Preview:https://github.com/Nayak19navya/Traffic-Accident-Analysis-Dashboard/blob/main/Snapshot%20of%20Dashboard.png.png
