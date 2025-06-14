# 🗽 NYC Yellow Taxi Trip Analysis (Oct–Dec 2023)

This project analyzes NYC Yellow Taxi trip data from **October to December 2023**. It explores patterns across time, geography, pricing, and tipping behavior, using both **Pandas** for initial data processing and **DuckDB** for scalable analytics.

---

## 📁 Project Structure

| File / Folder | Description |
|---------------|-------------|
| **`dataprocess/`** | Core data preprocessing scripts. First, ~10 million rows (Oct–Dec) are processed using **Pandas**, followed by batch operations with **DuckDB**, leveraging modular method encapsulation for efficient handling. |
| **`7004_Time&Geo.ipynb`** | Analyzes differences in trip volume between weekdays and weekends. Visualizes popular pickup zones using heatmaps. |
| **`Order_day&night.ipynb`** | Explores daily patterns, including peak and off-peak periods. Compares weekday vs weekend trip counts. |
| **`Pricing Model Analysis.ipynb`** | Breaks down taxi fare components and their proportions. Identifies high-fare regions. |
| **`Tip Analysis.ipynb`** | Examines tipping behavior, including payment method preferences, tip vs distance correlation, and time-of-day effects on tip amount. |
| **`time_period.ipynb`** | Conducts a deeper exploration of trip volume trends over the full year. Identifies significant drops during holidays. To normalize fluctuations, trip volume is expressed as a percentage of total trips. Also analyzes how peak zones shift across early morning, evening, and late-night hours. |
| **`taxi_zone_lookup.csv`** | Official NYC TLC lookup table mapping **LocationID** to zones, boroughs, and service areas. |
| **`taxi_zone_with_coords.csv`** | Converts **LocationIDs** to geographic coordinates (latitude & longitude) for geospatial visualization. |
| **`LICENSE`** | Project license information. |
| **`README.md`** | This file. Overview of the project and its contents. |

---

## 🛠 Technologies Used

- Python (Pandas, Matplotlib, Seaborn)
- DuckDB (for efficient in-memory SQL queries)
- Jupyter Notebook
- NYC TLC Taxi Trip Data

---

## 📌 Goals

- Discover patterns in taxi usage across time and space.
- Identify peak travel periods and hotspots.
- Understand how pricing and tipping behavior vary by context.
- Build a reproducible pipeline for large-scale urban transportation data analysis.

---

## 📈 Sample Insights

- Tipping is significantly higher in early morning airport trips.
- Weekend hotspots shift toward nightlife districts (e.g., SoHo, East Village).
- Fare composition is dominated by distance-based charges in outer boroughs.

---

Feel free to explore each notebook for detailed visualizations and findings. 🎯

