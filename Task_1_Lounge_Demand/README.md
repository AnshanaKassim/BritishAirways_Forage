# 📌 Task 1: Lounge Demand Modelling (Excel)
### 🎯 Objective:
To develop a scalable model that estimates the proportion of passengers eligible for lounge access across different flight categories, enabling British Airways to forecast lounge demand for future operations. 

### 📊 Approach Created: 
- TOTAL_SEATS as a proxy for total passenger volume.
- Calculated eligibility percentages for: Tier 1 (Concorde Room), Tier 2 (First Lounge) and Tier 3 (Club Lounge). 
- Grouped flights using three key dimensions: Haul type (Short-haul vs Long-haul), Time of day (Morning, Lunchtime, Afternoon, Evening) and Destination region (Europe, North America, Asia, Middle East). 
- Built a lookup table using pivot tables with average eligibility percentages across ~10,000 flights.

### 💡 Key Insights:
- Short-haul European flights show the highest proportions of Tier 2 and Tier 3 eligible passengers.
- Long-haul flights consistently have lower lounge eligibility across all tiers. 
- Regional differences significantly influence eligibility, reflecting variations in customer profiles. 
- Time of day has a relatively smaller impact compared to haul type and region. 
- Tier 1 passengers represent a very small proportion across all categories. 

### 💼 Business Impact: 
- Enables British Airways to forecast lounge demand without relying on fixed schedules. 
- Supports capacity planning and resource allocation for lounges.
- Helps identify high-demand routes and time periods for premium services. 
- Provides a scalable framework for future and uncertain flight schedules 

### 🧠 Justification:
- Flights were grouped by haul type, time of day, and region to capture meaningful differences in passenger behaviour. 
- Historical averages were used to produce robust, data-driven estimates. 
- Using seat capacity as a proxy allows consistent estimation across flights.
- The model is independent of specific flight numbers, making it flexible and reusable for future planning.

### 🛠️ Tools Used:
- Microsoft Excel 
- Pivot Tables 
- Excel formulas (SUM, IFERROR) 
- Data aggregation and segmentation