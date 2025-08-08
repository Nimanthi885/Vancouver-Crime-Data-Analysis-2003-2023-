# 📊 Vancouver Crime Data Analysis (2003–2023)

This repository explores 20 years of crime incident data from Vancouver, BC. The goal is to extract actionable insights through data cleaning, exploration, visualization, and mapping — supporting informed decision-making in law enforcement, urban planning, and public safety.

---

## 📁 Dataset Overview

- **Source**: Vancouver Open Data Portal
- **Period Covered**: 2003 – November 2023
- **Records**: Geotagged crime incidents
- **Main Fields**:
  - `TYPE`: Crime type
  - `YEAR`, `MONTH`, `DAY`, `HOUR`, `MINUTE`: Time of occurrence
  - `NEIGHBOURHOOD`: Location classification
  - `X`, `Y`: UTM coordinates (converted to Lat/Lon)
  - `Latitude`, `Longitude`: For geospatial plotting

---

## 🧰 Tools & Libraries

- **Language**: Python
- **Libraries**: `pandas`, `seaborn`, `matplotlib`, `folium`, `scikit-learn`, `geopandas`, `utm`
- **Visualization**: Jupyter Notebook, Power BI

---

## 🧪 Analysis & Results

### Temporal Trends
- **Crime peaked** in the early 2010s, with gradual changes after 2020.
- **Most crimes** occurred in the evening (6 PM–12 AM).
- **Fridays and Saturdays** showed the highest incident rates.
- **Summer months (July–August)** had noticeable spikes.

### Crime Types
- Most frequent:
  - Theft
  - Mischief
  - Break & Enter
- These made up a significant share of total incidents.

### Geospatial Insights
- Downtown Vancouver, Mount Pleasant, and Grandview-Woodland were **hotspots**.
- Heatmaps revealed strong spatial clustering near the city center.

---

## 🗺️ Visualizations

### ✅ Jupyter Notebook Highlights
- Crime counts by type, hour, weekday, and month
- Top 10 neighbourhoods by incidents
- Heatmap using Folium
- Line and bar plots using Seaborn and Matplotlib

### ✅ Power BI Dashboard Features
- KPI cards: total crimes, top neighborhood/type
- Time trend: year & month
- Heat matrix: hour vs. day of week
- Interactive filters: year, neighborhood, type
- Geomap with density


