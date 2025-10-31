#### Survey coverages

Geographical areas delimiting surveys

Geometri:
- itemType: feature
- type: geometry-any
- crs:
  - http://www.opengis.net/def/crs/OGC/1.3/CRS84
  - http://www.opengis.net/def/crs/EPSG/0/4326
  - http://www.opengis.net/def/crs/EPSG/0/4258
  - http://www.opengis.net/def/crs/EPSG/0/25831
  - http://www.opengis.net/def/crs/EPSG/0/25832
  - http://www.opengis.net/def/crs/EPSG/0/25833
  - http://www.opengis.net/def/crs/EPSG/0/25834
  - http://www.opengis.net/def/crs/EPSG/0/25835
  - http://www.opengis.net/def/crs/EPSG/0/25836

Egenskaper

| **Navn:** | **geometry** |
| --- | --- |
| Definisjon: | Elementtype: feature |
| Type: | geometry-any |
| OGC-rolle: | primary-geometry |

| **Navn:** | **survey_id** |
| --- | --- |
| Definisjon: | Unique identification number. |
| Multiplisitet: | 0..1 |
| Type: | string |
| OGC-rolle: | id |

| **Navn:** | **data_owner** |
| --- | --- |
| Definisjon: | Company or institution that owns the data. |
| Multiplisitet: | 0..1 |
| Type: | string |

| **Navn:** | **year** |
| --- | --- |
| Definisjon: | Year the survey ended. |
| Multiplisitet: | 0..1 |
| Type: | integer |

| **Navn:** | **date_start** |
| --- | --- |
| Definisjon: | Date when survey started. |
| Multiplisitet: | 0..1 |
| Type: | date (string) |

| **Navn:** | **date_end** |
| --- | --- |
| Definisjon: | Date when survey ended. |
| Multiplisitet: | 0..1 |
| Type: | date (string) |

| **Navn:** | **depth_sensor** |
| --- | --- |
| Definisjon: | Depth sensor used. |
| Multiplisitet: | 0..1 |
| Type: | string |

| **Navn:** | **logged_backscatter** |
| --- | --- |
| Definisjon: | Backscatter is logged during survey. |
| Multiplisitet: | 0..1 |
| Type: | boolean |

| **Navn:** | **logged_water_column** |
| --- | --- |
| Definisjon: | Water column is logged during survey. |
| Multiplisitet: | 0..1 |
| Type: | boolean |

| **Navn:** | **survey_method** |
| --- | --- |
| Definisjon: | Method for collecting data. |
| Multiplisitet: | 0..1 |
| Type: | string |

| **Navn:** | **total_area** |
| --- | --- |
| Definisjon: | Total area of the survey in km2. |
| Multiplisitet: | 0..1 |
| Type: | number |

| **Navn:** | **normalised_area** |
| --- | --- |
| Definisjon: | Total area normalized to 100 meters depth. |
| Multiplisitet: | 0..1 |
| Type: | number |

| **Navn:** | **quality_specification** |
| --- | --- |
| Definisjon: | Technical specification used during survey. |
| Multiplisitet: | 0..1 |
| Type: | string |

| **Navn:** | **resolution** |
| --- | --- |
| Definisjon: | Resolution of terrain model. |
| Multiplisitet: | 0..1 |
| Type: | string |

| **Navn:** | **modeled** |
| --- | --- |
| Definisjon: | Terrain model created. |
| Multiplisitet: | 0..1 |
| Type: | boolean |

| **Navn:** | **financier** |
| --- | --- |
| Definisjon: | Company or institution financing the survey. |
| Multiplisitet: | 0..1 |
| Type: | string |
