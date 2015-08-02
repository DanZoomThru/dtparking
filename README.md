dtparking
=========

Map and Data set of parking lots in Downtown Cleveland, Ohio that are publicly accessible. 

View them at: http://skorasaurus.github.io/dtparking 

Uses [mapbox.js](https://www.mapbox.com/mapbox.js)

## To make your own:

- Obtain downtown parking lots for your downtown: 

Use the following overpass query: http://overpass-turbo.eu/s/4mn
Move the map to your preferred geographic area 
Hit Run 
Export as geojson and save as a geojson file and place it in the directory of your fork. 


Edit index.html with the file name of your geojson file. 


## Other notes

index.html is the only html code that you need to use. 

You can ignore the other html files in the folder. They are from older commits that I have published so I can refer to them in this [blog post](https://skorasaurus.wordpress.com/2014/08/24/how-i-styled-polygons-in-mapbox-js-from-an-external-geojson-file/). 


## License: 

The geographic data of parking lots is from OpenStreetMap so the license is [ODBL](http://www.openstreetmap.org/copyright). 

The Base map is designed by me and can be obtained as a style (named Pascal Pastel) at https://github.com/skorasaurus/pascalpastel.tm2 for use in MapBox Studio.

The html Code is under MIT License. 