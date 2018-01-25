# NightVision [![License](https://img.shields.io/badge/License-BSD%202--Clause-orange.svg)](https://opensource.org/licenses/BSD-2-Clause)
This is a map style that uses a publically available [Tegola](https://github.com/terranodo/tegola) tileset of the world. It is currently still under development.

<img align="right" alt="TegolaNightVision" src="logo.png" />

## Viewing the map in the browser
- [Rendered with OpenLayers:](https://htmlpreview.github.io/?https://github.com/PetersonGIS/NightVision/blob/master/live-map.html)
Note that the tilt functionality is missing from this map, which displays the night-vision.json style.
- [Rendered with Mapbox:](http://www.gretchenpeterson.com/live-map-mapbox-night-vision.html) 
  This map displays the night-vision3d.json style. Test the tilt (pitch) functionality by holding ctrl while clicking and dragging. 

## Map Design

The NightVision basemap has a bright color scheme to contrast with dark backgrounds, and satellite backgrounds in particular. Use night-vision.json for OpenLayers implementations and night-vision3d.json for Mapbox implementations. To use these styles as springboards for your own styles it is currently recommended to use the version of Maputnik found [here](https://justenpalmer.github.io/editor) or to hand edit the json. It's expected that the background would be replaced with a satellite layer and the transparency of the two land layers, and any other polygons as desired, would be modified to allow the satellite layer to show through. 

Note that night-vision.json and night-vision3d.json use data extracted from OSM and Natural Earth Data and hosted using Tegola. See [tegola-osm](https://github.com/terranodo/tegola-osm) for a list of available layers in this vector tileset. You may want to explore using other open tilesets or hosting your own as this tileset is for demonstration purposes only.

[![night-vision3d.json map demo in a mapbox renderer](demo.gif)](http://www.gretchenpeterson.com/live-map-mapbox-night-vision.html)

