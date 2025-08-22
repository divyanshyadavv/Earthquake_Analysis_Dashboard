# Earthquake Analysis Dashboard
This project presents an in-depth analysis of **global earthquakes of magnitude ≥6.0** recorded between 1900 and 2013.  
The goal was to identify key seismic patterns across magnitude, depth, geography, and time **Tableau**.


**Dataset**
- **Source:** Publicly available earthquake data (USGS)  
- **Records:** ~8,300 earthquakes  
- **Columns include:**  
  - Date & Time  
  - Latitude, Longitude  
  - Depth (km)  
  - Magnitude & Type  
  - Place  


**Key Insights**
1. **Magnitude Distribution**  
   - Most earthquakes fall in the **6.0–7.0** range.  
   - Very strong quakes (>8.5) are rare.  

2. **Depth Characteristics**  
   - The majority are **shallow (<100 km)**, which are usually the most damaging.  
   - A smaller fraction occur at depths of **>300 km**, often in subduction zones.  

3. **Temporal Patterns**  
   - Records increase significantly after the **1960s**, mainly due to advances in seismic detection technology.  
   - No seasonal patterns were found — earthquakes occur consistently throughout the year.  

4. **Geographic Distribution**  
   - Most quakes occur along tectonic boundaries, especially the **Pacific Ring of Fire** (Japan, Chile, Indonesia, Alaska).  
   - Deep-focus earthquakes cluster around the **Fiji-Tonga subduction zone**.  

5. **Measurement Methods**  
   - Older quakes were measured using `mb/ms`, while modern quakes use the more reliable `mw` scale.  


**Visualizations**
Tableau Dashboard
[Dashboard](Dashboard.png)

- Magnitude & Depth Histograms  
- Relationship between Depth and Magnitude  
- Yearly and Monthly trends  
- Geographic heatmap of quakes by place


