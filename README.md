#  QGIS Mapping Portfolio – Asia Mozahim Adnan

This repository showcases four GIS projects created using QGIS. Each project applies different geospatial techniques including 3D visualization, isochrones analysis, population density mapping, and elevation contouring — all focused on regions of Iraq.

---

##  Projects Overview

### 1.  Walking and Driving Accessibility in Baghdad

This project analyzes accessibility zones around a central bus station in Baghdad using isochrones mapping.

- Created isochrone buffers for both walking (500, 1000, 1500 meters) and driving (3000, 5000, 10,000 meters)
- Used QuickOSM plugin to import road and bus data from OpenStreetMap
- Applied Buffer, Reproject Layer, and Symbology tools
- Background basemap: OSM Standard

  ![Image](https://github.com/user-attachments/assets/d919b255-8c29-4a0a-a4f4-896e31f90760)

  
> Goal: Show how far people can travel on foot or by vehicle from a key public transport hub.

---

### 2.  3D Map of Qandil Mountain

Focused on Qandil Mountain in Northern Iraq, this project visualizes terrain elevation using QGIS's 3D tools.

- Located the mountain using LatLon Tools
- Added roads and nearby features with QuickOSM
- Basemap: Google Satellite
- Downloaded DEM data from OpenTopography
- Created a Hillshade layer for enhanced terrain effect
- Rendered the entire scene in 3D Map View


![Image](https://github.com/user-attachments/assets/fb482338-8089-46d6-a10a-ad30b3b34014)


> Goal: Highlight Qandil Mountain's topography and surroundings in a realistic 3D visualization.

---

### 3.  Iraq Population Density Map

A thematic map showing population density across Iraq.

- Started with a shapefile of Iraq's administrative boundaries
- Used Field Calculator to add:
  - area column (in km²)
  - density column (population / area)
- Applied Graduated Symbology based on density values
- Used color gradient to represent varying density levels


![Image](https://github.com/user-attachments/assets/63b09de5-f5e1-4297-af12-32e5dac87e16)



> Goal: Visualize how population distribution varies across Iraq’s regions.

---

### 4.  Contour Map – Northern Iraq

This project shows elevation changes in Northern Iraq using contour lines and a color ramp.

- Used Singleband Pseudocolor Renderer to visualize DEM raster
- Created Contour lines from elevation data
- Enhanced readability with proper labeling and layout tools


![Image](https://github.com/user-attachments/assets/ac53be38-d975-4249-a5e5-b322348c8541)


> Goal: Provide a detailed look at terrain elevation and slope changes in Northern Iraq.
---

## Tools & Technologies

- QGIS 3.x
- QuickOSM Plugin
- OpenStreetMap, Google Satellite, OpenTopography
- Field Calculator, Buffer Tool, Raster Analysis
- 3D Map View, Print Layout

---

## Author

Asia Mozahim Adnan  
🗺️ Oil & Gas Administration Graduate | Building GIS & Data Skills  
📍 Basra, Iraq    
🌐 [LinkedIn – Asia Mozahim](https://www.linkedin.com/in/asia-mozahim)

---

## License

This project is open-source and intended for educational and portfolio purposes.
