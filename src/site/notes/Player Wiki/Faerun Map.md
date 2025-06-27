---
{"dg-publish":true,"permalink":"/player-wiki/faerun-map/","noteIcon":""}
---


Here is an interactable map.


```leaflet  
id: FaerunPlayer### Must be unique with no spaces  
image: [[Faerun Map.jpg]] ### Link to the map image file  
bounds: [[0,0], [6798, 9800]] ### Size of the map in px H_y, W_x  
height: 900px ### Size of the leaflet embed in px on your screen  
width: 90% ### Size of the leaflet embed in your note  
lat: 3350 ### To center the map, make this half of the map width.  
long: 4900 ### To center the map, make this half of the map height.  
minZoom: -3 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
maxZoom: 2 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
defaultZoom: -1.5 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out.  
unit: miles ### The value displayed when measuring so you know what type of unit is being measure.  
scale: 1.318681318681319 ### Only required if you are using the measurement tool. Real units/px (resolution) of your map  
recenter: false  
darkmode: false ### marker  
```





