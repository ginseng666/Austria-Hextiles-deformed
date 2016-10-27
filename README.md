# Austria-Hextiles-deformed

Several TopoJSON-files for Austria, including municipalities, counties and states as hex-tiles and deformed. For a demo see [http://drawingdata.net/colormaps](http://drawingdata.net/colormaps)

All deformations are based on the number of eligible voters 2016.

Each file contains the fields:
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
