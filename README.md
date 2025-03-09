# Lab3
## GGR472 Lab3
### **This is an interactive webmap of my flight destinations in 2024.**

The webpage presents the viewer with a globe centered on the Western Hemisphere, a scale in the bottom left corner of the screen; a geocoder, return button, and a legend on the right from the globe; a continent filter in the top left. 

The map presents flight destinations with airplane-shaped point feature, the colour of which represents the price of the flight, which is reflected in the legend. Users can zoom in and out of the map, click on the cities to read about the flight cost and a memory from that trip, search up any location in the relevant countries, and filter the visual output through the choice of a continent of interest.

The map was created using a manually compiled dataset of flight destinations which I created using Geojson.io (initially for Lab1), and which I then uploaded on Mapbox and converted it into a vector tileset.

The repository consists of an html, a css, and a js files. The website uses **_Mapbox GL JS, Mapbox Geocoder Plugin, and Bootstrap CSS_**, all of which are noted in the html file. The website has such interactivity as a **_Scale Control, Navigation Control, Mapbox Geocoder, Popup_**.

I was also going to implement the mapbox-gl-globe-minimap but I encountered issues that I was unable to troubleshoot and figure out. I think that my code still has some issues which I encountered in the developer mode but I do not think that they affect the current functionality of the website. Nevertheless, I hope to address them soon and figure out the minimap add-on as well.

## Here is the link to the map: https://polina-gorn.github.io/Lab3/ 
