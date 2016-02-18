# mapcrime

This repo is a complement to the [maptime
talk](https://docs.google.com/presentation/d/11Q_RO2Sxs9QBuc42f8R09QY_qwa1bErM0iaEYaGxB_I/edit?usp=sharing)

## download data from data.nola.gov
```
wget -O Calls-for-Service-2016.csv https://data.nola.gov/api/views/wgrp-d3ma/rows.csv?accessType=DOWNLOAD
```

## convert csv to geojson
```
csv2geojson --lat MapY --lon MapX Calls-for-Service-2016.csv > calls-for-service-2016.json
```
