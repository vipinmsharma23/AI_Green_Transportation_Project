# AI_Green_Transportation_Week1
Week 1: Shortest Route Mapping in Bengaluru using OSMNX

# AI Green Transportation – Week 1

This repository contains the Week 1 milestone for my AICTE internship project **AI Green Transportation**.

## 🚦 Week 1 Objective
- Select a city (Bengaluru, India)
- Allow user to enter origin and destination
- Download road network from OpenStreetMap using OSMNX
- Compute **shortest driving route**
- Generate **interactive HTML map** output

## 🗺️ City and Sample Inputs
- **City:** Bengaluru, Karnataka, India  
- Users can enter any valid location inside Bengaluru, e.g.:
  - Majestic Bengaluru → Electronic City Bengaluru
  - MG Road Bengaluru → Silk Board Bengaluru

## 🔧 Tech Stack
- Python
- OSMNX (road networks + routing)
- NetworkX (graph shortest path)
- Folium (interactive maps)
- Matplotlib
- Geopy (optional user input geocoding)

## 📂 Files
| File | Description |
|------|-------------|
| `week1_AI_Green_Transportation.ipynb` | Shortest path computation + routing |
| `maps_week1/week1_shortest_route_map_bangalore.html` | Interactive route map |

## ▶️ How to Run
```bash
pip install osmnx networkx folium geopy matplotlib
jupyter notebook week1_AI_Green_Transportation.ipynb

Shortest route successfully calculated between user-selected locations.
Generated and saved an interactive HTML map showing the driving route in Bengaluru.
