# 🗺️ [Ukraine Security Incidents Mapping / Spatial Analysis of Urban Data]

## 📌 Project Overview
[Цей проєкт демонструє базові навички просторового аналізу та картографії за допомогою QGIS. Основна мета — візуалізація географічних даних та категоризація об'єктів на основі їхніх атрибутів.]

## 🛠️ Tools & Technologies Used
* **GIS Software:** QGIS (Long Term Release)
* **Data Formats:** CSV, Raster Basemaps
* **Key Skills:** Spatial Data Visualization, Geocoding (X/Y Data), Symbology Customization, Data Categorization

## 📂 Data Sources
* [Власноруч згенерований датасет у форматі CSV із координатами українських міст.]
* **Basemap:** [Google Road Map via QuickMapServices plugin.]

## 🚀 Methodology (Steps Taken)
1. **Data Import:** [Імпортовано CSV-файл із координатами (Lon/Lat) з використанням системи координат WGS 84 (EPSG:4326).]
2. **Layering:** [Накладено векторний шар із точками поверх растрової базової карти України.]
3. **Symbology & Categorization:** [Налаштовано унікальну символіку (SVG маркери) для кожної точки на основі атрибуту "Місто". Змінено масштаб та кольори для кращої читабельності.]
4. **Labeling:** [Додано динамічні підписи з таблиці атрибутів із використанням текстового буфера (halo) для контрасту.]

## 📊 Results
[Створено інтерактивну карту з чіткою ієрархією даних. Нижче наведено скриншот фінального макета.]

![Map Result](https://github.com/rudykoleh/qgis-spatial-mapping/blob/main/ukraine_cities_map_symbols.png)

## 💡 Key Takeaways
[Цей проєкт закріпив розуміння систем координат, роботи з шарами та налаштування категорійної символіки для гуманітарного або безпекового аналізу.]
