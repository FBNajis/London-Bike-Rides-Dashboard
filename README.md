# London Bike Rides Dashboard

**Author:** Umar Khairur Rahman

---

## Table of Contents
* [Project Overview](#project-overview)
* [Dashboard Preview & Live Link](#dashboard-preview--live-link)
* [Key Dashboard Features & Insights](#key-dashboard-features--insights)
* [Dataset Used](#dataset-used)
* [Technologies Used](#technologies-used)
* [Repository Contents](#repository-contents)
* [Contact](#contact)

---

## Project Overview

This project aims to analyze London's bike-sharing data to understand how various factors, especially weather conditions, affect the number of bike rides. The raw data is processed using Python and then visualized using Tableau to create an interactive dashboard. This dashboard is designed to provide in-depth insights into bike usage trends, correlations with temperature and wind speed, and seasonal patterns, thereby helping to understand the behavior of bike-sharing service users in London.

---

## Dashboard Preview & Live Link

You can access and interact directly with the dashboard via Tableau Public:

➡️ **[View Interactive Dashboard on Tableau Public](https://public.tableau.com/views/LondonBikeRides-MovingAverageTempvsWindHeatmap/Dashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**

Below is a preview of the dashboard:

![London Bike Rides Dashboard Preview](London%20Bike%20Rides%20Dashboard.png)

---

## Key Dashboard Features & Insights

The dashboard presents various visualizations to uncover important insights from the bike ride data:

* **Main KPIs:** Displays aggregate metrics such as Total Rides, Average Temperature, and Average Wind Speed.
* **Moving Average Analysis:** Visualizes the trend of bike ride counts over time using a moving average to smooth out short-term fluctuations.
* **Temperature vs. Wind Speed Heatmap:** Shows the correlation between temperature and wind speed against the number of bike rides, identifying ideal weather conditions for cycling.
* **Interactive Filters:** Allows users to filter data by Weather Situation, Season, and Holiday for more specific analysis.
* **Key Insights:** From the dashboard, it can be concluded that the number of bike rides tends to increase with warmer temperatures and lower wind speeds. Usage peaks during the summer and drops sharply in the winter.

---

## Dataset Used

This analysis is based on a primary CSV files:

1.  **`london_merged.csv`**: Contains time-series data from 2023 to 2025, including the hourly count of bike rides, temperature, wind speed, humidity, and other relevant variables such as holidays and weekends. This data has undergone cleaning and feature engineering using a Jupyter Notebook.

---

## Technologies Used

* **Python (Jupyter Notebook):** Used for initial data processing, cleaning, and feature engineering.
* **Tableau Desktop & Tableau Public:** Used for creating, designing, and publishing the interactive dashboard.
* **CSV:** The file format used for storing the dataset.

---

## Repository Contents
* `london_merged.csv`: The main dataset used for the analysis.
* `london_bikes.ipynb`: Jupyter Notebook containing the Python code for data processing.
* `London Bike Rides - Moving Average & Temp vs Wind Heatmap.twbx`: The Tableau workbook file containing the dashboard.
* `London Bike Rides Dashboard.png`: A preview image of the dashboard.
* `README.md`: This project explanation.

---

## Contact

**Umar Khairur Rahman**
* Tableau Public Profile: [umar.rahman](https://public.tableau.com/app/profile/umar.rahman)
* GitHub: `https://github.com/FBNajis`
* LinkedIn: `https://www.linkedin.com/in/umar-khairur-rahman-168739258/`

---
