# Get_forest_pulse 🌍

**Team:** GET  
**NASA Space Apps Challenge 2025**

---

## 🌍 Project Overview

*Get_forest_pulse* is an interactive and animated visualization project showing deforestation and fire dynamics in Cameroon. By combining Terra satellite images (MODIS True Color) and MODIS Active Fire data, the project allows users to visualize:

- Forest cover loss from 2001 to 2022  
- Active fire hotspots year by year  
- Combined forest loss and fire impact to highlight overall environmental effects  

The project provides an **interactive interface** where users can **click on the map to select a location**, then get **current weather information** and generate visualizations for that point.

---

## 🎯 Objectives

- Automatically download MODIS True Color and Active Fire images for Cameroon  
- Generate GIF and MP4 animations showing forest loss, fire hotspots, and their combination  
- Provide an interactive exploration tool via a Leaflet web map  
- Deliver a ready-to-use tool for presentations, pitch videos, or educational projects  

---

## ⚙️ How It Works

1. **Interactive Web Interface:**  
   Users select any point on the world map (focus on Cameroon).  
2. **“Send Location” Button:**  
   - Retrieves the GPS coordinates of the selected point  
   - Calls the OpenWeatherMap API to display current weather at that location  
3. **Python All-in-One Script (`forest_pulse_all_in_one.py`):**  
   - Automatically downloads MODIS True Color and Active Fire images for each year  
   - Generates animated GIFs:  
     - Forest cover (forest_loss_cameroon.gif)  
     - Fire hotspots (fires_cameroon.gif)  
     - Combined forest + fires (forest_fire_cameroon.gif)  
   - Converts GIFs to MP4 videos for easy integration in presentations or pitch videos  

---

## 📊 Data Sources

- **MODIS Terra Corrected Reflectance True Color** (NASA GIBS / Worldview)  
- **MODIS Terra Active Fire True Color** (NASA GIBS / Worldview)  
- **OpenWeatherMap API** for real-time weather  

All data are publicly available.

---

## 🎬 Usage

1. Open `index.html` in a web browser to access the interactive map.  
2. Click on a location and press **Send Location** to view local weather.  
3. Run `forest_pulse_all_in_one.py` to automatically generate GIF and MP4 animations for Cameroon.  
4. Use the animations for presentations, pitch videos, or educational projects.

---

## 🌱 Impact

- Raises awareness of deforestation and wildfires in Cameroon  
- Shows the link between forest loss and fire activity  
- Provides an interactive, visual tool for education and scientific communication  

---

## 📜 License

Open-source project under the **MIT License**. NASA Earthdata imagery is publicly available.

---

## 🏆 Team

**GET**  
NASA Space Apps Challenge 2025
