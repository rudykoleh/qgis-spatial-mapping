# 🗺️ Ukraine Security Incidents Mapping / Spatial Analysis of Urban Data

## 📌 Project Overview
This project demonstrates basic spatial analysis and cartography skills using QGIS. The main goal is the visualization of geographic data and the categorization of objects based on their attributes.

## 🛠️ Tools & Technologies Used
*   **GIS Software:** QGIS (Long Term Release)
*   **Data Formats:** CSV, Raster Basemaps
*   **Key Skills:** Spatial Data Visualization, Geocoding (X/Y Data), Symbology Customization, Data Categorization

## 📂 Data Sources
*   A custom-generated CSV dataset containing the coordinates of Ukrainian cities.
*   **Basemap:** Google Road Map via the QuickMapServices plugin.

## 🚀 Methodology (Steps Taken)
*   **Data Import:** Imported a CSV file with coordinates (Lon/Lat) using the WGS 84 (EPSG:4326) coordinate reference system.
*   **Layering:** Overlaid a vector point layer on top of a raster basemap of Ukraine.
*   **Symbology & Categorization:** Configured unique symbology (SVG markers) for each point based on the "City" attribute. Adjusted the scale and colors for better readability.
*   **Labeling:** Added dynamic labels from the attribute table using a text buffer (halo) for high contrast.

## 📊 Results
Created a clear, visually appealing map with a structured data hierarchy. Below is a screenshot of the final layout.

![Map Result](https://github.com/rudykoleh/qgis-spatial-mapping/blob/main/ukraine_cities_map_symbols.png)


