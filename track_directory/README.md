### Overview
A directory of horse racing tracks. PRs appreciated to fill in missing values, add additional columns (e.g. year opened) or to add more tracks, especially internationally

### Fields
* name: short track name
* abbreviation: abbreviation used by Daily Racing Form/Equibase (should be unique)
* locale: state/province
* country: country codes see: https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2
* track_name: longer track name
* is_active: 1 indicates still racing, 0 indicates closed permanently and missing value means I don't know
* latitude,longitude: geo coordinates

### Sources
* [Equibase](http://www.equibase.com/stats/)
* [The Racing Journal](http://www.theracingjournal.com/info/index.php)
* [Google Maps](https://maps.google.com")
* [DRF](http://www1.drf.com/entries/trackAbbreviations.html)
* American Racing Manual

### Thanks
* Google Sheets
* Various StackOverflow posts on regex
