# AI Green Transportation 🚦🌱
AICTE Internship Project — Sustainable Transportation using AI

---

## 📌 Project Overview
This project aims to reduce carbon emissions in urban transportation by suggesting the most eco-friendly routes between two locations in Bengaluru using real road network data.

The project provides:
- Interactive shortest-route & low-emission route maps
- CO₂ emission comparison charts
- Real usable route planning for any location within Bengaluru

---

## 📆 Weekly Progress

### 🟢 Week 1 — Shortest Route Planner
- Bengaluru road network downloaded from OpenStreetMap
- Users can input any valid location in Bengaluru
- Shortest driving route calculated using NetworkX
- Generated interactive HTML map using Folium  
📂 Files located inside `week1/` folder

---

### 🟡 Week 2 — Low-Emission Route Optimization & CO₂ Analysis
- Added emission-weighted routing using real-world road type characteristics
- Calculated & compared CO₂ emissions
- Generated distance & emission comparison bar charts
- Created combined dual-route map for better visualization  
📂 Files located inside `week2/` folder

#### 🔍 Objective
Enhance routing with sustainability consideration by:
- Reducing CO₂ emissions via optimized routing
- Comparing shortest vs eco-friendly route
- Improving environmental impact awareness

#### 🚦 Features Implemented
✔ Any Bengaluru location input  
✔ Shortest route visualization (Blue)  
✔ Low-emission route visualization (Green)  
✔ Traffic & speed-based emission modeling  
✔ Dual-route map + static comparative image  
✔ Fully automated map and graph generation  

#### 🧠 Technical Highlights
| Component | Technology |
|----------|------------|
| Map Data | OSMnx + OpenStreetMap |
| Routing Engine | NetworkX |
| Visualization | Folium |
| Charts | Matplotlib |
| Geocoding | Geopy |

#### 📂 Week-2 Folder Structure
week2/
├─ week2_AI_Green_Transportation.ipynb
├─ week2_shortest_route_map.png
├─ week2_low_emission_route_map.png
├─ week2_distance_comparison.png
├─ week2_emission_comparison.png
└─ week2_combined_route_image.png

#### 📊 Output Summary
- Shows measurable emission reduction using alternate routes
- Interactive maps help visualize transport sustainability
- Supports Smart & Green Mobility objectives (UN SDG-11)

---

## ▶️ How to Run Project
```bash
pip install osmnx networkx folium geopy matplotlib scikit-learn
jupyter notebook

Open the notebook from respective week folder & run all cells.

🌱 Status

🔹 Week-1 Completed
🔹 Week-2 Completed
◻ Week-3: Final Project Report + PPT (Upcoming)

👨‍💻 Author

Vipin Sharma
AICTE Internship — 2025

