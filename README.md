# 🐦 Bird Species Observation Dashboard

This repository presents an end-to-end **data analysis and visualization project** aimed at understanding bird species distribution, seasonal patterns, and environmental influences across **forest** and **grassland** habitats.  
The dashboard helps identify biodiversity hotspots, species trends, and conservation priorities using real-world observation data.

---

## 📌 Objective

Analyze bird observation patterns across different habitats, times, and environmental conditions to uncover **actionable insights** that support conservation planning and biodiversity monitoring.

---
## 🚀 Pipeline Steps

### 📦 Data Preparation
- Loaded and merged **Forest** and **Grassland** datasets.
- Added `Habitat` column to distinguish sources.
- Converted date columns into `Year` and `Month`.
- Filled missing environmental values (Temperature, Humidity).
- Standardized categorical fields (`Location_Type`, `Observer`, etc.).

### 📊 Exploratory Data Analysis
- Conducted in **Python** using Pandas, NumPy, Plotly, and Seaborn.
- Key visualizations:
  - **Monthly trend analysis** of bird sightings.
  - **Seasonal distribution** patterns.
  - **Top 10 most observed species**.
  - **Habitat-wise species distribution**.
  - **Environmental correlations** (Temperature, Humidity vs. sightings).

### 📈 Dashboard Development
- Built with **Streamlit** for interactivity.
- Filters for:
  - Year
  - Habitat type
  - Location type
  - Observer
- Features:
  - Animated species trend chart (year by year changes).
  - Downloadable filtered dataset.
  - Separate tabs for Trends, Habitat Insights, Environmental Impact, Top Species, and Data Table.

---

## 🔍 Insights

- **Seasonal Peaks:** Bird activity spikes in spring and summer.
- **Habitat Diversity:** Forest and grassland habitats support distinct sets of species.
- **Environmental Influence:** Temperature and humidity correlate with species activity.
- **Top Observed Species:** A few species dominate total observations, indicating habitat preference or higher detectability.

---

## 📦 Dependencies

- Python 3.11+
- Streamlit
- Pandas
- NumPy

---

## 🔗 Live Resource

🌐 Live Dashboard: Add your Streamlit Cloud link here

---

👩‍💻 Author

Harshita Pandey
📧 Email: harshitapandey2910@gmail.com
