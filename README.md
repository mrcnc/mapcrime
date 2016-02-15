# mapcrime

## download data from data.nola.gov
```
wget -O Calls-for-Service-2016.csv https://data.nola.gov/api/views/wgrp-d3ma/rows.csv?accessType=DOWNLOAD
```

## convert csv to geojson
```
csv2geojson --lat MapY --lon MapX --crs ESRI:102682 Calls-for-Service-2016.csv > calls-for-service-2016.json
```
