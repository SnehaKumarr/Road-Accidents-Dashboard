# Road Accident Analysis Dashboard  

## Overview  
This Power BI dashboard provides insights into **road accidents and casualties** for the years **2021 and 2022**. It allows users to analyze accident trends, severity, vehicle types involved, and accident conditions (road type, light, and location).  

The dashboard aims to provide help to stakeholders (e.g., traffic authorities, policymakers, safety analysts) by letting them identify key problem areas and make **data-driven decisions** for road safety improvements.  

---

## Objectives  
This dashboard is designed to analyze:  
- Yearly comparison of casualties and accidents (Current Year vs Previous Year).  
- Breakdown of casualties by **severity, vehicle type, road type, area, and time of day**.  
- Trends and **geographical insights** for better decision-making.  

---

## Key Features  

### Primary KPIs  
- **Total Casualties** (Current Year & YoY growth)  
- **Total Accidents** (Current Year & YoY growth)  
- **Casualties by Severity** (Fatal, Serious, Slight)  

### Secondary KPIs  
- **Casualties by Vehicle Type** (Car, Bus, Van, Motorcycle, Agricultural, etc.)  
- **Casualties by Road Type** (Single Carriageway, Dual Carriageway, Roundabout, Slip Road, etc.)  
- **Casualties by Area/Location & Day/Night condition**  

### Visuals & Insights  
- **Monthly Trend**: Comparison of casualties for Current Year vs Previous Year.  
- **Urban vs Rural Accidents** (distribution %).  
- **Casualties by Light Condition** (Day vs Dark).  
- **Geographical Map** of accidents (location-wise insights).  

---

##  Tech Stack  
- **Power BI Desktop** → for data modeling, visualization, and dashboard creation  
- **DAX (Data Analysis Expressions)** → for calculated measures and KPIs  
- **Power Query** → for data transformation and cleaning  
- **Data Source** → Road accident dataset (CSV/Excel/Database) for 2021 & 2022  
- **Map Visualization (Bing Maps)** → for plotting accident locations  
---

---

## Data Source  

The dashboard is built using road accident datasets for **2021 and 2022**.  
From the raw dataset, only the following **important fields** are used for analysis and KPIs:  

- **Accident Date** → Used for monthly/yearly trend analysis  
- **Accident_Severity** → Categorized into Fatal, Serious, and Slight  
- **Vehicle_Type** → Used for breakdown of casualties by vehicle type  
- **Road_Type** → To analyze casualties by different road types  
- **Urban_or_Rural_Area** → For urban vs rural casualty comparison  
- **Light_Conditions** → To differentiate accidents by day vs night  
- **Weather_Conditions** → Used as a slicer/filter  
- **Road_Surface_Conditions** → Used as a slicer/filter  
- **Number_of_Casualties** → Key metric for total casualties  
- **Number_of_Vehicles** → Contextual measure of accident scale  
- **Latitude / Longitude** → To plot accident locations on the map  

### Derived / Calculated Fields (via DAX)  
- **CY Accidents Count** → Current Year total accidents  
- **CY Casualties** → Current Year total casualties  
- **PY Accidents** → Previous Year total accidents  
- **PY Casualties** → Previous Year total casualties  
- **YoY Accidents** → Year-over-Year change in accidents (%)  
- **YoY Casualties** → Year-over-Year change in casualties (%)  

These fields were cleaned and transformed in **Power Query**, and KPIs were built using **DAX** in Power BI.  

---


---

## Insights  

The Road Accident Analysis Dashboard highlights key patterns and trends across accident data for **2021 and 2022**:  

### Casualties by Vehicle Type  
- **Cars** are responsible for the highest number of casualties across both years.  
- **Motorcycles** and **buses** show a smaller share but are associated with more **severe/fatal** accidents compared to cars.  
- **Agricultural vehicles** and **goods vehicles** contribute minimally but indicate risk on rural roads.  

###  Casualties by Road Type  
- **Single Carriageways** account for the majority of casualties, highlighting them as the most accident-prone road type.  
- **Dual Carriageways** and **Roundabouts** show lower casualty counts but still present risks during high-traffic conditions.  
- **Slip Roads** have the least casualties, likely due to lower traffic volumes.  

### Urban vs Rural Distribution  
- Around **62% of total casualties** occurred in **urban areas**, likely due to higher population density and vehicle volume.  
- **Rural areas** contributed to the remaining share, often with higher severity accidents because of higher driving speeds.  

### Day vs Night Accidents  
- **Daytime accidents** account for ~**73%** of casualties, showing peak traffic exposure hours.  
- **Nighttime accidents** (~27%) are fewer in number but show a higher severity rate due to poor visibility and fatigue.  

### Light & Weather Conditions  
- Majority of accidents occurred in **daylight and normal weather**, suggesting human error and traffic density as leading causes.  
- Fewer accidents happened in fog, snow, or heavy rain, but those that did often had **higher severity**.  

### Monthly Trends  
- Accident trends show seasonal fluctuations, with peaks during **summer months** and declines in **winter**.  
- **Year-over-year analysis** reveals a drop in **fatal casualties by 33.3%**, showing some improvement in road safety measures.  

### Severity of Casualties  
- **Slight casualties** form the largest portion, followed by **serious**, and then **fatal**.  
- The downward trend in fatal casualties is a **positive indicator**, but serious and slight injuries remain high, needing targeted interventions.  


---

## Key Takeaways  
1. **Cars on single carriageways in urban areas during daytime** are the most common accident scenario.  
2. **Nighttime and rural accidents**, although fewer, are more severe.  
3. **Weather is not the main driver** of accidents — traffic density and road type are more critical.  
4. **Fatal casualties decreasing** is a positive sign, but slight and serious casualties need stronger prevention strategies.  

---

## Screenshots
<img width="1199" height="677" alt="Snapshot of the Dashboard" src="https://github.com/user-attachments/assets/576ac764-32ed-4fdc-bc8a-364916c12813" />


---
## Author  
Sneha Kumar (NIT Raipur)
