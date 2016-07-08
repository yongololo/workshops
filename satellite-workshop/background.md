# Analyzing the Earth using Earth Observation data

![untitled2](https://cloud.githubusercontent.com/assets/126868/16667445/24493b76-44aa-11e6-9c7f-96278c2f829d.gif)<br>
_Combinations of spectral analysis over the [Mumbai landfill fire](https://www.mapbox.com/blog/mumbai-landfill-fire/) from Sentinel data_

[Earth Observation satellites](https://en.wikipedia.org/wiki/Earth_observation_satellite) regularly collect environment and surface data of the Earth.

## Data
* NASA Landsat-8/ESA Sentinel-2 Satellite search https://remotepixel.ca/projects/satellitesearch.html ([About](https://remotepixel.ca/blog/satellitesearch_20160610.html))
* [India] ISRO Oceansat-2/Resourcesat-1  http://bhuvan.nrsc.gov.in/data/download/index.php
* https://en.wikipedia.org/wiki/List_of_Earth_observation_satellites

## Bands
The data is collected in multiple bands, each capturing the reflected radiation of a certain wavelength from the Earth. Use [QGIS](http://www.qgis.org/en/site/) alongwith this [tutorial](https://github.com/mapbox/workshops/tree/gh-pages/satellite-workshop) to process the bands for analysis.

### Landsat and Sentinel
![](http://landsat.gsfc.nasa.gov/wp-content/uploads/2015/06/Landsat.v.Sentinel-2.png)
- [Landsat Bands](http://landsat.usgs.gov/best_spectral_bands_to_use.php)
- [Sentinel-2 Bands](https://earth.esa.int/web/sentinel/user-guides/sentinel-2-msi/resolutions/spatial) | [Specification](https://sentinel.esa.int/documents/247904/685211/Sentinel-2+Products+Specification+Document+%28PSD%29/0f7bedeb-9fbb-4b60-91aa-809162de456c)

**[Landsat 8 band combinations](https://blogs.esri.com/esri/arcgis/2013/07/24/band-combinations-for-landsat-8/)** 
- Natural Color 4 3 2
- False Color (urban) 7 6 4
- Color Infrared (vegetation) 5 4 3
- Agriculture 6 5 2
- Atmospheric Penetration 7 6 5
- Healthy Vegetation 5 6 2
- Land/Water 5 6 4
- Natural With Atmospheric Removal 7 5 3
- Shortwave Infrared 7 5 4
- Vegetation Analysis 6 5 4

## Processing and Analysis
Use one of these resources to start analyzing the bands from your data source:
- https://github.com/mapbox/workshops/tree/gh-pages/satellite-workshop
- https://www.mapbox.com/blog/putting-landsat-8-bands-to-work/
- http://landsat.gsfc.nasa.gov/?page_id=2372
- http://www.harrisgeospatial.com/Home/NewsUpdates/TabId/170/ArtMID/735/ArticleID/14305/The-Many-Band-Combinations-of-Landsat-8.aspx
- http://gisgeography.com/landsat-program-satellite-imagery-bands/