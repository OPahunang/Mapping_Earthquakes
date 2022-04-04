# Mapping_Earthquakes

## Overview:

Disaster Reporting Network is a non-profit organization that provides data driven storytelling on disasters around the world. 

The goal of this project is to present an insightful data visualization and with interactive features of world map showing Earthquakes, Tectonic Plates and Major Earthquakes. Three choices of maps are available, streets, satellite and dark. 

Data are retrieved at US Geological Survey real-time earthquake GeoJSON and GitHub for the Tectonic Plates. Using knowledge of JavaScript, Leaflet, Mapbox and geoJSON that made this project feasible.

## Result:

### Deliverable 1

•	The tectonic plate data is added as a second layer group
•	The tectonic plate data is added to the overlay object 

![deliv1-tectonic_plate12.png](https://github.com/OPahunang/Mapping_Earthquakes/blob/main/resources/deliv1-tectonic_plate12.png)


•	The d3.json() callback is working and does the following: 
o	The tectonic plate data is passed to the geoJSON() layer
o	The geoJSON() layer adds color and width to the tectonic plate lines
o	The tectonic layer group variable is added to the map

![deliv1-tectonic_plate3.png](https://github.com/OPahunang/Mapping_Earthquakes/blob/main/resources/deliv1-tectonic_plate3.png)


•	The earthquake data and tectonic plate data displayed on the map when the page loads 

![deliv1-map.png](https://github.com/OPahunang/Mapping_Earthquakes/blob/main/resources/deliv1-map.png)



### Deliverable 2

•	The major earthquake data is added as a third layer group 
•	The major earthquake data is added to the overlay object 
•	The d3.json() callback is working and does the following: 
o	Sets the color and diameter of each earthquake.
o	The major earthquake data is passed to the geoJSON() layer.
o	The geoJSON() layer creates a circle for each major earthquake, and adds a popup for each circle to display the magnitude and location of the earthquake
o	The major earthquake layer group variable is added to the map

![deliv2-major_earthquake.png](https://github.com/OPahunang/Mapping_Earthquakes/blob/main/resources/deliv2-major_earthquake.png)


•	All the earthquake data and tectonic plate data are displayed on the map when the page loads and the datasets can be toggled on or off 

![deliv2-map.png](https://github.com/OPahunang/Mapping_Earthquakes/blob/main/resources/deliv2-map.png)



### Deliverable 3

•	Add an additional map

![deliv3-map.png](https://github.com/OPahunang/Mapping_Earthquakes/blob/main/resources/deliv3-map.png)

