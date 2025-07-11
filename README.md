# 🚗 GPS Toll-based System Simulation

A web-based simulation tool built with Streamlit and Folium to calculate toll charges based on the GPS route between major cities in Tamil Nadu, India. The application also visualizes the vehicle route, toll zones, and heatmap data on an interactive map.

---

## ✨ Features

- Select vehicle type and source/destination locations
- Calculate toll charges based on:
  - Distance traveled inside toll zones
  - Fixed fee per toll zone
  - Vehicle type (penalty/exemption applied)
- Interactive map with:
  - Start and end markers
  - Route polyline
  - Toll zones overlay
  - Traffic heatmap

---

## 📦 Tech Stack

- [Streamlit](https://streamlit.io/) – Web UI framework
- [Folium](https://python-visualization.github.io/folium/) – Map rendering
- [Shapely](https://shapely.readthedocs.io/) – Geometry operations
- [Geopy](https://geopy.readthedocs.io/) – Geographic calculations
- [GeoPandas](https://geopandas.org/) – (Optional) Geospatial operations
- [SimPy](https://simpy.readthedocs.io/) – (Planned) Simulation environment

---

## 🔧 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/harris2267/GPS_Tollbased_system.git
cd gps-toll-simulation
python -m venv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate
pip install -r requirements.txt
pip install streamlit folium shapely geopandas geopy simpy pandas
streamlit run app.py
```
