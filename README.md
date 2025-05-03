#### **Weather Trends in Zurich (1994–2024)**

## **A Data Analysis Project using SQL & Power BI**

---

### 🗂️ Project Overview

This project analyzes over 30 years of daily weather data in Zurich, sourced from [data.stadt-zuerich.ch](https://data.stadt-zuerich.ch/). The goal is to identify long-term climate patterns and seasonal trends using structured data analysis and dashboard visualization.

### 📊 Tools Used

- **SQL** (PostgreSQL) – Data cleaning, transformation, and aggregation
- **Power BI** – Dashboard creation and visual analytics
- **Notion** – Documentation and project presentation

---

### 📁 Data Overview

- Time period: **1994–2024**
- Daily variables analyzed:
    - 🌡️ Temperature
    - 🔥 Max Temperature
    - 🌧️ Rain Duration
    - 📈 Atmospheric Pressure
    - ☀️ Solar Radiation


### 🔎 Observations with Research Interest

- The **50 lowest recorded temperatures** occurred **mostly before 2012**, with only **7 exceptions**.
- In contrast, the **50 highest temperatures** all appear **after 2002**, with **only one value** prior to that year.
- Since **2017**, **average solar radiation** has consistently exceeded **140 W/m²**.
    
    Before **2000**, most yearly averages remained **below 120 W/m²**.
    
    ### 🧠 Lessons Learned & Challenges
    
    - Organizing and transforming the dataset in **SQL** helped me understand temporal patterns and allowed for clean monthly, yearly, and daily aggregations.
    - A key challenge was ensuring the **slicer worked across multiple visuals and tables** in Power BI, especially without unpivoting the data. This was solved using **DAX logic** and an auxiliary "measurements" table.
    - I learned how to **combine different time granularities** in a single dashboard (daily, monthly, yearly) and maintain meaningful interactivity.
