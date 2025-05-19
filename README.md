## **🚗 Uber Pickups Data Analysis - New York City**

## **Overview**

This project explores and visualizes Uber pickup data in New York City using Python libraries such as **pandas**, **numpy**, **matplotlib**, and **seaborn**. The goal is to understand pickup trends, identify high-traffic periods and locations, and analyze base-level activity.


---

## **Table of Contents**

1. Data Set
2. Data Cleaning
3. Exploratory Data Analysis
4. Dependencies

---


## **  📂 Data Set**

The dataset contains trip-level records with features such as:
- `Dispatching_base_num`: ID of the base dispatching the vehicle
- `Pickup_date`: Date and/or time of the pickup
- `Affiliated_base_num`: Base to which the driver is affiliated
- `locationID`: Location code for pickup 
- `Latitude` and `Longitude`: Geolocation of the pickup point
  

---

## **🧹 Data Cleaning**

Basic cleaning steps included:
- Parsing datetime fields
- Handling missing values
- Renaming columns for clarity
- Data type conversion
- Creating additional time-based columns (e.g., month, hour, weekday)


---

## **📊 Exploratory Data Analysis**

1. **Monthly Pickup Trend**  
   Identified which months had the highest volume of Uber pickups.

2. **Hourly Rush Patterns**  
   Analyzed hourly distribution of pickups to detect peak demand times.

3. **Most Active Base Numbers**  
   Found the base numbers with the highest number of active pickups.

4. **Pivot Table Summaries**  
   Used pivot tables to summarize pickups by date, hour, base, and location.

---


## **Dependencies**

* Python 3.x
* Libraries:

  * `pandas`
  * `numpy`
  * `matplotlib`
  * `seaborn`
 
