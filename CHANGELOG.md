# Changelog

## Alpha 3
**Breaking Changes**
* modified Services.Geoprocessing constructor to account for changes in esri leaflet core at [Release Candidate 5](https://github.com/Esri/esri-leaflet/blob/master/CHANGELOG.md#release-candidate-5)
* added a generic setParam() method to replace previous setters

**Changes**
* in addition to L.GeoJSON geometries, L.LatLng, L.LatLngBounds, and L.Marker are now considered valid GP inputs

## Alpha 2

**Breaking Changes**
* reorganized logic of GP to inherit from services (to introduce better support for secure resources)

**Changes**
* added ability to set custom paths (which will allow for use with Network Analyst services and SOEs)
* refactored code to follow pattern established by [esri-leaflet-geocoder](https://github.com/Esri/esri-leaflet-geocoder)
* introduced ability to check properties of GP services that don't support CORS
