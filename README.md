# 🌍 Carbon Footprint Analysis - Croatia

University project for the course *Programiranje za analizu podataka* (Programming for Data Analysis).

This project explores the potential of reducing Croatia’s carbon footprint by identifying optimal locations for solar and wind power plants using publicly available climate and emissions data.

## 📊 Project Overview

The goal was to collect and analyze climate data (wind, sunlight exposure) and CO₂ emissions to recommend areas in Croatia where renewable energy sources would have the most impact.

### ✅ Project Tasks

1. **📥 Data Collection**
   - Climate data from [meteo.hr](https://meteo.hr)
   - Wind and sun exposure maps
   - GeoJSON data for Croatian counties
   - CO₂ emission statistics

2. **🗃️ Database Creation**
   - Created a SQLite database with structured tables for:
     - `climate` — wind speed, sunlight hours, etc.
     - `emissions` — CO₂ emissions by region, year, sector

3. **🔍 Data Analysis**
   - Cross-referenced data to identify locations with:
     - Highest solar and wind potential
     - High emissions that could benefit from renewable energy

4. **🗺️ Visualization**
   - Interactive Folium map showing regions with:
     - Only solar panel potential (🟡)
     - Only wind turbine potential (🔵)
     - Both (🟢)
   - Popup markers with solar & wind values per county
   - Visual summary of regional potential

5. **🚀 Final Output**
   - All data and results presented in a Jupyter Notebook
   - SQLite database with structured data
   - Exported interactive HTML map: `croatia_renewables_map.html`

## 🧰 Tools & Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `folium`
- `GeoPandas`
- `sqlite3`
- `requests`, `BeautifulSoup`
- `selenium`
- `shapely`
- `json`

## 🧠 Note

This is a demonstration of how publicly available data can be processed and visualized to support data-driven environmental decisions. While some datasets and graphics were externally sourced and partially pre-processed, the integration, analysis logic, and visualization approach were fully developed as part of the course.

## 💡 Inspiration

This project is an example of how thoughtful use of data can contribute toward building a greener, more sustainable future 🌱
