# LEGO Set Explorer (1970–2022 Data Analysis)

An interactive Microsoft Power BI report built to help users discover the perfect LEGO set while analyzing catalog data across five decades (1970–2022). Whether you are looking for a gift within a specific age range and budget, or exploring historical trends across themes, piece counts, and pricing, this explorer provides full interactive visibility into the LEGO universe.



---

## 📌 Executive & Dataset Summary
* **Total Sets Analyzed:** ~18,460 sets across 152 themes and 17 theme groups.
* **Timeframe Analyzed:** 1970 to 2022 (annual catalog growth from 41 sets in 1970 to 967 sets in 2022).
* **Key Metrics:** Average set price of **$37.53** with over **3.29 million total pieces** released.
* **Core Findings:**
  * **Piece Count Distribution:** Over 75% of manufactured sets contain between 1–249 pieces, with high-piece-count sets (>2,000 pieces) sharply increasing in frequency post-2015 for adult builders.
  * **Age & Price Correlation:** Recommended minimum age strongly correlates with higher piece counts and higher retail price points (e.g., 18+ sets under *Icons* or *Ultimate Collector Series*).

---

## 🛠️ Tools & Technologies
* **BI Tool:** Microsoft Power BI Desktop
* **Data Visualizations:** KPI Cards, Interactive Slicers, Data Tables, Custom Image Cards, Decomposition Tree Visuals
* **Data Sources:** Maven Analytics LEGO Dataset (1970–2022)
* **Version Control:** Git & GitHub

---

## 📊 Dashboard Architecture & Pages

### Page 1: Interactive Set Explorer
* **Top KPIs:** Displays aggregated metrics including Total Sets, Average Piece Count, and Average Retail Price.
* **Dynamic Slicers:** Multi-criteria filtering across **Theme Group** (e.g., *Licensed*, *Action/Adventure*, *Technical*), **Theme** (e.g., *Star Wars*, *Icons*, *Technic*), and **Age Range** (e.g., *5 to 9*, *10 to 17*, *Over 18*).
* **Detailed View Pane:** Selecting an individual set (e.g., *Cat D11 Bulldozer*, *AT-AT*, *Millennium Falcon*) dynamically updates set details—displaying piece count, retail price band, release year, age rating, and set imagery.

![LEGO Set Explorer - Main Dashboard](/phot_1.png)

---

### Page 2: Catalog Breakdown (Decomposition Tree)
* **Root Metric:** Breaks down the global set count across catalog hierarchies.
* **Exploratory Dimensions:** Enables root-cause breakdown along:
  1. `category` (e.g., Normal, Extended, Collection, Book)
  2. `themeGroup` (e.g., Action/Adventure, Modern Day, Historical, Licensed)
  3. `theme` (e.g., Ninjago, Legends of Chima, Star Wars)
  4. `name` (Individual product listings)

![LEGO Set Explorer - Decomposition Tree](/photo_2.png)

---

## 💡 Conclusion & Key Takeaways

The **LEGO Set Explorer** transforms over five decades of raw catalog data into an actionable visual discovery tool. By combining dynamic multi-criteria filtering with hierarchical breakdown capabilities, the report allows collectors and casual shoppers to easily pinpoint their ideal set while providing clear analytical visibility into how LEGO's pricing, piece counts, and thematic offerings have evolved over time.