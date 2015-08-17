# horse-racing-data
Collection of data related to horse racing, mostly in CSV

Thanks to http://horseracingdatasets.com/ for making horse racing data more open and accessible

## track_directory.csv
### Overview
A directory of horse racing tracks. Cobbled together from a variety of sources and my own experience. Appreciate any help in filling in missing values and adding more international courses.

### Fields
* name: short track name
* abbreviation: abbreviation used by Daily Racing Form/Equibase (should be unique)
* locale: state/province
* country: country codes see: https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2
* track_name: longer track name
* is_active: 1 indicates still racing, 0 indicates closed permanently and missing value means I don't know
* latitude,longitude: geo coordinates
