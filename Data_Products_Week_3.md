---
title: "One of Best Cafes in Marikina"
author: "Julian Paolo S. Alejandro"
date: "August 6, 2019"
output:
  html_document:
    keep_md: yes
  pdf_document: default
---


## Plotting Map

The map below shows the exact location of Cafe Lidia.  


```r
library(leaflet)
```

```
## Warning: package 'leaflet' was built under R version 3.5.3
```

```r
m <- leaflet() %>%
  addTiles() %>%  # Add default OpenStreetMap map tiles
  addMarkers(lat=14.62, lng=121.09, popup="Cafe Lidia, one of Marikina's Best Cafe")
m  # Print the map
```

<!--html_preserve--><div id="htmlwidget-507b4d20c4e9bc174e36" style="width:672px;height:480px;" class="leaflet html-widget"></div>
<script type="application/json" data-for="htmlwidget-507b4d20c4e9bc174e36">{"x":{"options":{"crs":{"crsClass":"L.CRS.EPSG3857","code":null,"proj4def":null,"projectedBounds":null,"options":{}}},"calls":[{"method":"addTiles","args":["//{s}.tile.openstreetmap.org/{z}/{x}/{y}.png",null,null,{"minZoom":0,"maxZoom":18,"tileSize":256,"subdomains":"abc","errorTileUrl":"","tms":false,"noWrap":false,"zoomOffset":0,"zoomReverse":false,"opacity":1,"zIndex":1,"detectRetina":false,"attribution":"&copy; <a href=\"http://openstreetmap.org\">OpenStreetMap<\/a> contributors, <a href=\"http://creativecommons.org/licenses/by-sa/2.0/\">CC-BY-SA<\/a>"}]},{"method":"addMarkers","args":[14.62,121.09,null,null,null,{"interactive":true,"draggable":false,"keyboard":true,"title":"","alt":"","zIndexOffset":0,"opacity":1,"riseOnHover":false,"riseOffset":250},"Cafe Lidia, one of Marikina's Best Cafe",null,null,null,null,{"interactive":false,"permanent":false,"direction":"auto","opacity":1,"offset":[0,0],"textsize":"10px","textOnly":false,"className":"","sticky":true},null]}],"limits":{"lat":[14.62,14.62],"lng":[121.09,121.09]}},"evals":[],"jsHooks":[]}</script><!--/html_preserve-->
