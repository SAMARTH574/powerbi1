# Renewable Energy Production Analysis – Power BI Dashboard

## Project Overview

This project analyzes **renewable energy production trends across countries and years** using **Microsoft Power BI**.
The dashboard helps visualize how different renewable energy sources contribute to total electricity generation and how renewable adoption changes over time.

The goal of this project is to demonstrate **data analytics, visualization, and dashboard design skills** using Power BI.

---

## Dataset Description

The dataset used in this project contains renewable energy production data with the following fields:

| Column Name          | Description                               |
| -------------------- | ----------------------------------------- |
| country              | Name of the country                       |
| year                 | Year of energy production                 |
| population           | Population of the country                 |
| solar_generation_twh | Solar energy generation in terawatt-hours |
| wind_generation_twh  | Wind energy generation in terawatt-hours  |
| hydro_generation_twh | Hydropower generation in terawatt-hours   |
| renewables_share     | Percentage share of renewable energy      |

These variables allow analysis of renewable energy contribution by **country, energy type, and year**.

---

## Tools & Technologies

* **Microsoft Power BI Desktop**
* **Data Visualization**
* **DAX (Data Analysis Expressions)**
* **Data Modeling**

---

## Dashboard Features

The Power BI dashboard includes the following visualizations:

### 1. Total Renewable Energy Production

Displays total renewable generation using solar, wind, and hydro sources.

### 2. Renewable Energy by Source

Shows contribution of:

* Solar
* Wind
* Hydropower

This helps identify which renewable source dominates energy production.

### 3. Country Comparison

A bar chart comparing renewable energy production across different countries.

### 4. Yearly Trend Analysis

A line chart showing renewable energy growth over time.

### 5. Renewable Energy Share

Displays the percentage share of renewables in total energy production.

---

## Data Processing Steps

1. Import dataset into **Power BI Desktop**.
2. Clean and validate data types.
3. Create calculated measures using **DAX**.
4. Build relationships if required.
5. Design interactive visualizations.
6. Apply filters and slicers for exploration.

Example DAX measure used:

```
Total Renewable = 
SUM(Solar_Generation_TWh) +
SUM(Wind_Generation_TWh) +
SUM(Hydro_Generation_TWh)
```

---

## Insights from the Dashboard

Key insights that can be obtained from this dashboard include:

* Growth trends in renewable energy adoption.
* Countries producing the highest renewable energy.
* Which energy source (solar, wind, hydro) contributes the most.
* Changes in renewable share over time.

---

## How to Use the Dashboard

1. Open the file **re2.pbix** in **Power BI Desktop**.
2. Use slicers to filter by:

   * Country
   * Year
3. Interact with charts to explore renewable energy patterns.

---

## Project Purpose

This project demonstrates skills in:

* Data visualization
* Business intelligence reporting
* Energy data analysis
* Interactive dashboard development

It can be used as a **portfolio project for data analytics roles**.

---

## Future Improvements

Possible enhancements:

* Add **more renewable sources** (biomass, geothermal).
* Integrate **real-world energy datasets**.
* Add **forecasting models** for renewable energy growth.
* Deploy dashboard to **Power BI Service** for sharing.
