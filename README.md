# MAP675-Assignment2


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
