# map675-assignment-02-jmfr236
Authored by: Jessica Freeman, November 2021<br>
GitHub Page URL: https://jmfr236.github.io/map675-assignment-02-jmfr236/

## About
This map shows historic buildings that are on the National Register of Historic Places in Kentucky (NRHP). See total number of historic buildings within each tourism region. 

## Sources
- Ky Tourism Regions: https://opengisdata.ky.gov/datasets/kygeonet::ky-tourism-regions
- NRHP Historic Buildings Point Locations and Spreadsheet Data: https://www.nps.gov/subjects/nationalregister/data-downloads.htm

## Data Processing
- ogrinfo - shapefile layer details
- ogr2ogr - projection transformation, converting shapefiles to GeoJSON
- Mapshaper - geojson layer info, simplify detail of tourism regions, filter NRHP data to Kentucky and show select fields
- QGIS - Join NRHP point locations with spreadsheet data, spatial join for total building count in each region
- Script - color selection


