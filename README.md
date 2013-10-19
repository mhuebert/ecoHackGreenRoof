To view locally:

python -m SimpleHTTPServer

(then visit http://0.0.0.0:8000)



For geoJSON conversion:
http://ben.balter.com/2013/06/26/how-to-convert-shapefiles-to-geojson-for-use-on-github/
-- especially: $ ogr2ogr -f GeoJSON -t_srs crs:84 [name].geojson [name].shp

Leaflet.js with geoJSON:
http://leafletjs.com/examples/geojson.html