---
{"dg-publish":true,"permalink":"/the-world-of-endul/"}
---

Welcome to The World of Endul
Click on a location on the map to get started!
[[Nefelrosse/Gorvatch/Gorvatch\|Gorvatch]]

```leaflet  
id: EndulWorldMap_NoLocations ### Must be unique with no spaces  
image: [[ENDUL-WORLD-MAP.png]] ### Link to the map image file. Do not add a ! in front of the image  
bounds: [[0,0], [8192, 16384]] ### Size of the map in px Height_y, Width_x. Ignore 0,0  
height: 1550px ### Size of the leaflet embed in px on your screen  
width: 3276px ### Size of the leaflet embed in your note  
lat: 4096 ### To center the map, make this half of the map height.  
long: 8192 ### To center the map, make this half of the map width.  
minZoom: -3.4 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
maxZoom: 1 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
defaultZoom: -2.425 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
zoomDelta: 0.05 ### Adjust how much the zoom changes when you zoom in or out.  
unit: km ### The value displayed when measuring so you know what type of unit is being measure.  
scale: 0.001 ### Real units/px (resolution) of your map  
recenter: false  
darkmode: false ### marker
```
