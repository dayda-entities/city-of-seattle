---
title: 'Catch Basin, Junction Box, Sand Box'
created: '2020-11-10T17:00:02.085181'
modified: '2020-11-10T17:00:02.085192'
state: active
type: dataset
tags:
  - Catch Basin
  - Drainage
  - Dso
  - Dww
  - Gis
  - Infrastructure
  - Junction Box
  - Land Base
  - Sandbox
  - Spu
  - Storm
  - Utility
groups:
  - Local Government
csv_url: >-
  https://data-seattlecitygis.opendata.arcgis.com/datasets/fb417b817bb34bc2ad241dd589591c28_0.csv?outSR=%7B%22latestWkid%22%3A2926%2C%22wkid%22%3A2926%7D
json_url: 'https://gisdata.seattle.gov/server/rest/services/SPU/SPU_DWW_DSO/MapServer/0'
layout: post

---
This layer displays all the sandboxes and junction boxes within the City of Seattle (and the former service area north of the City limits) regardless of ownership.  Selected Maximo data are included.  The data source is DWW.catch_basin_pt_pv with the following definition query, CB_LIFECYCLE_CODE IN( 'C' , 'UNK' , 'T' ,'TBC', 'U', 'PC') AND CB_FEATYPE_CODE IN ( 'SB' , 'JB', 'JBS').  The features are symbolized on the attribute CB_FEATYPE_CODE.  Labels are based on the attribute CB_ROLE_TYPE.  This layerfile does not display when zoomed out beyond 1:899.   Refreshed weekly.  Maintained by SPU GIS DWW Data Maintenance staff.
