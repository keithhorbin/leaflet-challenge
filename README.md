# USGS - Earthquake Visualization

### Background

The USGS is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes. 

In this project I am building a new dashboard that will allow visualization of USGS earthquake data which is updated every 5 minutes for the prior 7 days. 

### Technical

- Create a map using Leaflet that plots all of the earthquakes for the prior 7 days based on their longitude and latitude
- Data supplied via JSON from the USGS website. URL is called into the dashboard so refreshed data will auto sync. 
- Data markers reflect the magnitude of the earthquake in their size and color
  - Earthquakes with higher magnitudes appear larger and darker in color
- Popups provide additional information about the earthquake when a marker is clicked 
- Legend provides context for all map data points 

### Output

In order to run this locally you will need a Mapbox supplied API key and will have to update the config file with it. 

Below is sample output if you provide an API key and build the code. 



![Capture](C:\Users\Admin\Desktop\Homework\leaflet-challenge\Capture.PNG)