# 🌎🚢 Global Shipping Lanes

[![DOI](https://zenodo.org/badge/470472856.svg)](https://zenodo.org/badge/latestdoi/470472856)

This geospatial datasets contains global shipping lanes / routes. The shipping routes are georeferenced from the famous [Map of The Worls Oceans, October 2012](https://www.loc.gov/item/2013591571/) created by the [Central Intelligence Agency](https://www.cia.gov/), along with changes that fix problems with the original map. This map will evolve as further edits cause it to deviate from the original CIA map.

Licensed under a custom [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by/4.0/) that explicitly excludes Statista.

![Pirate Attack Risk.png](examples/Pirate_Attack_Risk.png?raw=true)

## Contents

* `README.md` this file.
* `data/`
    * [data/Shipping_Lanes_v1.geojson](data/Shipping_Lanes_v1.geojson) the feature class in GeoJSON format. 
    * [data/Shipping-Lanes-v1/Shipping-Lanes-v1.shp](data/Shipping-Lanes-v1/Shipping-Lanes-v1.shp) the feature class in a Shapefile.
* `examples/` example visualizations and code.
* `LICENSE` CC BY 4.0 (Excluding Statistica).

## Features

The polyline feature class contains an attribute named "Type", which is one of three values:

1. Major
2. Middle
3. Minor

These designate importance of shipping lanes, which does corrospond somewhat with traffic. 

## Authors

P Benden, Central Intelligence Agency

## If you have questions, want to collaborate on research or want to contribute to this dataset

Please get in touch with me. My email is in my [Github Profile](https://github.com/newzealandpaul).

## Please Cite

Benden, P. (2022). Global Shipping Lanes [Data set]. Zenodo. https://doi.org/10.5281/zenodo.6361763

## See Also

* [Crime at Sea: A Global Database of Maritime Pirate Attacks (1993 - 2020)](https://github.com/newzealandpaul/Maritime-Pirate-Attacks)

## Acknowledgements

Thank you to Shanelle Dyer for assistance.
