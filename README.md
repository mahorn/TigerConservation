# MAP675-Assignment2

# Summary
This web map will give a brief overview of conservation areas for the Royal Bengal Tiger in India. You will be able to see all protected & conserved areas, as recorded by [Protected Planet](https://www.protectedplanet.net/), in addition to current areas dedicated to tiger preservation, with high priority areas emphasized.


# Data Sources
StateBorder
* Obtained from [Diva GIS](http://www.diva-gis.org/gdata)
* Unnecessary attributes were removed.

TigerConservationAreas
* Obtained from [Global Forest Watch](http://data.globalforestwatch.org/datasets/04d892c083f54c638228931da081467b_3)
* Unnecessary attributes were removed. Data was cleaned to exclude any polygons not in India. Any overlapping areas with TigerConservationFocus were removed.
* Contains conservation areas for the Royal Bengal Tiger.

TigerConservationAreasFocus
* Obtained from [Global Forest Watch](http://data.globalforestwatch.org/datasets/f50efdadb0234ef392c4ecd8185c1f5f_4)
* Unnecessary attributes were removed. Data was cleaned to exclude any polygons not in India.
* The polygons in this layer are also conservation areas, but have been designated as a high priority focus for conservation efforts.

WildlifeProtectedAreas
* Obtained from [IUCN List of Protected and Conserved Areas](https://www.protectedplanet.net/country/IN) (aka UN Environment).
* Unnecessary attributes were removed.
