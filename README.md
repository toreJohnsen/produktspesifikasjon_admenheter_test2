# Produktspesifikasjon administrative enheter kommune
Dette er et test prosjekt for generering av produktspesifikasjoner

Legg inn config.yml som under og kjør github action:
* Generer produktspesifikasjon
* Evt. legg inn egne kapittel 
* Publish produktspesifikasjon site
* se resultatet på https://kartverket.github.io/produktspesifikasjon_admenheter/

Eksempel config.yml
```yml config
metadataId: 041f1e6e-bdbc-4091-b48f-8a5990f3cc5b
ogc_feature_api: https://kos-pygeoapi.atkv3-dev.kartverket.cloud/collections
output_directory: produktspesifikasjon
product_slug: admenheter
```