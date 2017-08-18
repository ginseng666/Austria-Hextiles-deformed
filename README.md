# Austria-Hextiles-deformed

Several TopoJSON-files for Austria, including municipalities, counties and states as hex-tiles and deformed - and now also electoral districts. For a demo see [http://drawingdata.net/colormaps](http://drawingdata.net/colormaps) and [http://vis.strategieanalysen.at/mandate](http://vis.strategieanalysen.at/mandate) for the electoral districts.

All deformations are based on the number of eligible voters 2016, the electoral districts on the data for the federal election 2017.

The electoral districts are a little different, as each hexagon represents one seat in parliament. It includes:
* name: The name of the electoral district
* mandate: The number of seats in each district
* wahlkreis: The code for the electoral district: "wk" + a number between 1 and 9 for the state + a-g for the district itself (so the city of Innsbruck for example has the code "wk7a")


All other files contain the following fields:
* iso: unique identifier, Gemeindekennziffer (5 digits for a municipality, 3 for a county, 1 for a state - to combine with voting results one might want to add trailing zeros to counties and states to get a total length of 5 digits)
* name: name of municipality/county/state


Municipalities/Gemeinden:
* gemeinden_normal: municipalities, normal (99% simplified)
* gemeinden_def: municipalities, deformed


Counties/Bezirke:
* bezirke_normal: counties, normal (99% simplified) 
* bezirke_moved: counties, normal, Vienna as extra element
* bezirke_hex: counties, normal, hex-tiles, Vienna as extra element
* bezirke_def: counties, deformed
* bezirke_hexdef: counties, deformed, as hex-tiles


States/Bundesländer:
* bundeslaender_normal: states, normal (99% simplified)
* bundeslaender_def: states, deformed
* bundeslaender_hex: states, normal, as hex-tiles
* bundeslaender_hexdef: states, deformed, as hex-tiles


CC BY 4.0, Flooh Perlot (https://creativecommons.org/licenses/by/4.0/); original file: CC BY 3.0 Geoland Kärnten 
