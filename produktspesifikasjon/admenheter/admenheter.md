---
title: Administrative enheter kommuner
updated: 2025-01-01
metadataId: 
---

# Produktspesifikasjon – Administrative enheter kommuner

Datasettet viser kommuneinndelinga i landet med de mest nøyaktige grensene som er registrert digitalt og som er samlet i ett datasett. Datasettet har referansedato 1.7.2025, og er oppdatert med overføring av et areal mellom Sel og Vågå ved Liaskarven - Rudihøe, i tillegg til ei retting av kommunegrensa mellom Stavanger og Sola ved Liapynten.
 
Flatene inneholder egenskaper som forteller om offisielle kommunenumre. De offisielle norske, samiske og kvenske navnene for kommunene er hentet fra SSR. I tillegg finnes informasjon om samiske forvaltningsområder.

Geodataene er fra nasjonal inndelingsbase, som er en del av matrikkelen. Ved overgang til ny forvaltningsløsning, ble det også gjort endringer i UML-modellen.

## Grunndata
- Metadata-ID: 
- Tema: Administrative grenser
- Status: 
- Metadata-URL: https://www.geonorge.no/geonetwork/srv/nor/csw?service=CSW&request=GetRecordById&version=2.0.2&outputSchema=http://www.isotc211.org/2005/gmd&elementSetName=full&id=041f1e6e-bdbc-4091-b48f-8a5990f3cc5b

## Formål
Framstille den offisielle kommuneinndelingen.

## Tilleggsinformasjon
Trenger du hjelp til å laste ned og ta i bruk Kartverkets data og tjenester? På kartverket.no finner du tips og veiledning.

## Bruk


## Kontakt
- Eigar: 
- Forvalter: 
- Kontaktpunkt:  

## Datakvalitet
Trenger du hjelp til å laste ned og ta i bruk Kartverkets data og tjenester? På kartverket.no finner du tips og veiledning.

## Datainnhold
#### Fylker

Fylker 2024

Geometri:
- itemType: feature
- type: geometry-any
- crs:
  - http://www.opengis.net/def/crs/OGC/1.3/CRS84
  - http://www.opengis.net/def/crs/EPSG/0/3857

Egenskaper

| **Navn:** | **geometry** |
| --- | --- |
| Definisjon: | Elementtype: feature |
| Type: | geometry-any |
| OGC-rolle: | primary-geometry |

| **Navn:** | **objid** |
| --- | --- |
| Definisjon: | objid |
| Multiplisitet: | 0..1 |
| Type: | integer |

| **Navn:** | **objtype** |
| --- | --- |
| Definisjon: | objtype |
| Multiplisitet: | 0..1 |
| Type: | string |

| **Navn:** | **lokalid** |
| --- | --- |
| Definisjon: | lokalid |
| Multiplisitet: | 0..1 |
| Type: | string |

| **Navn:** | **navnerom** |
| --- | --- |
| Definisjon: | navnerom |
| Multiplisitet: | 0..1 |
| Type: | string |

| **Navn:** | **versjonid** |
| --- | --- |
| Definisjon: | versjonid |
| Multiplisitet: | 0..1 |
| Type: | string |

| **Navn:** | **oppdateringsdato** |
| --- | --- |
| Definisjon: | oppdateringsdato |
| Multiplisitet: | 0..1 |
| Type: | date-time (string) |

| **Navn:** | **gyldigfra** |
| --- | --- |
| Definisjon: | gyldigfra |
| Multiplisitet: | 0..1 |
| Type: | date (string) |

| **Navn:** | **gyldigtil** |
| --- | --- |
| Definisjon: | gyldigtil |
| Multiplisitet: | 0..1 |
| Type: | date (string) |

| **Navn:** | **datafangstdato** |
| --- | --- |
| Definisjon: | datafangstdato |
| Multiplisitet: | 0..1 |
| Type: | date-time (string) |

| **Navn:** | **datauttaksdato** |
| --- | --- |
| Definisjon: | datauttaksdato |
| Multiplisitet: | 0..1 |
| Type: | date-time (string) |

| **Navn:** | **opphav** |
| --- | --- |
| Definisjon: | opphav |
| Multiplisitet: | 0..1 |
| Type: | string |

| **Navn:** | **fylkesnummer** |
| --- | --- |
| Definisjon: | fylkesnummer |
| Multiplisitet: | 0..1 |
| Type: | string |
| OGC-rolle: | id |

| **Navn:** | **fylkesnavn** |
| --- | --- |
| Definisjon: | fylkesnavn |
| Multiplisitet: | 0..1 |
| Type: | string |

| **Navn:** | **samiskforvaltningsomrade** |
| --- | --- |
| Definisjon: | samiskforvaltningsomrade |
| Multiplisitet: | 0..1 |
| Type: | boolean |

#### Fylkesgrenser

Fylkesgrenser 2024

Geometri:
- itemType: feature
- type: geometry-any
- crs:
  - http://www.opengis.net/def/crs/OGC/1.3/CRS84
  - http://www.opengis.net/def/crs/EPSG/0/3857

Egenskaper

| **Navn:** | **geometry** |
| --- | --- |
| Definisjon: | Elementtype: feature |
| Type: | geometry-any |
| OGC-rolle: | primary-geometry |

| **Navn:** | **objid** |
| --- | --- |
| Definisjon: | objid |
| Multiplisitet: | 0..1 |
| Type: | integer |
| OGC-rolle: | id |

| **Navn:** | **objtype** |
| --- | --- |
| Definisjon: | objtype |
| Multiplisitet: | 0..1 |
| Type: | string |

| **Navn:** | **lokalid** |
| --- | --- |
| Definisjon: | lokalid |
| Multiplisitet: | 0..1 |
| Type: | string |

| **Navn:** | **navnerom** |
| --- | --- |
| Definisjon: | navnerom |
| Multiplisitet: | 0..1 |
| Type: | string |

| **Navn:** | **versjonid** |
| --- | --- |
| Definisjon: | versjonid |
| Multiplisitet: | 0..1 |
| Type: | string |

| **Navn:** | **oppdateringsdato** |
| --- | --- |
| Definisjon: | oppdateringsdato |
| Multiplisitet: | 0..1 |
| Type: | date-time (string) |

| **Navn:** | **gyldigfra** |
| --- | --- |
| Definisjon: | gyldigfra |
| Multiplisitet: | 0..1 |
| Type: | date (string) |

| **Navn:** | **gyldigtil** |
| --- | --- |
| Definisjon: | gyldigtil |
| Multiplisitet: | 0..1 |
| Type: | date (string) |

| **Navn:** | **datafangstdato** |
| --- | --- |
| Definisjon: | datafangstdato |
| Multiplisitet: | 0..1 |
| Type: | date-time (string) |

| **Navn:** | **malemetode** |
| --- | --- |
| Definisjon: | malemetode |
| Multiplisitet: | 0..1 |
| Type: | string |

| **Navn:** | **noyaktighet** |
| --- | --- |
| Definisjon: | noyaktighet |
| Multiplisitet: | 0..1 |
| Type: | integer |

| **Navn:** | **datauttaksdato** |
| --- | --- |
| Definisjon: | datauttaksdato |
| Multiplisitet: | 0..1 |
| Type: | date-time (string) |

| **Navn:** | **opphav** |
| --- | --- |
| Definisjon: | opphav |
| Multiplisitet: | 0..1 |
| Type: | string |

| **Navn:** | **avgrensningstype** |
| --- | --- |
| Definisjon: | avgrensningstype |
| Multiplisitet: | 0..1 |
| Type: | string |

#### Kommuner

Kommuner 2024

Geometri:
- itemType: feature
- type: geometry-any
- crs:
  - http://www.opengis.net/def/crs/OGC/1.3/CRS84
  - http://www.opengis.net/def/crs/EPSG/0/3857

Egenskaper

| **Navn:** | **geometry** |
| --- | --- |
| Definisjon: | Elementtype: feature |
| Type: | geometry-any |
| OGC-rolle: | primary-geometry |

| **Navn:** | **objid** |
| --- | --- |
| Definisjon: | objid |
| Multiplisitet: | 0..1 |
| Type: | integer |

| **Navn:** | **objtype** |
| --- | --- |
| Definisjon: | objtype |
| Multiplisitet: | 0..1 |
| Type: | string |

| **Navn:** | **lokalid** |
| --- | --- |
| Definisjon: | lokalid |
| Multiplisitet: | 0..1 |
| Type: | string |

| **Navn:** | **navnerom** |
| --- | --- |
| Definisjon: | navnerom |
| Multiplisitet: | 0..1 |
| Type: | string |

| **Navn:** | **versjonid** |
| --- | --- |
| Definisjon: | versjonid |
| Multiplisitet: | 0..1 |
| Type: | string |

| **Navn:** | **oppdateringsdato** |
| --- | --- |
| Definisjon: | oppdateringsdato |
| Multiplisitet: | 0..1 |
| Type: | date-time (string) |

| **Navn:** | **gyldigfra** |
| --- | --- |
| Definisjon: | gyldigfra |
| Multiplisitet: | 0..1 |
| Type: | date (string) |

| **Navn:** | **gyldigtil** |
| --- | --- |
| Definisjon: | gyldigtil |
| Multiplisitet: | 0..1 |
| Type: | date (string) |

| **Navn:** | **datafangstdato** |
| --- | --- |
| Definisjon: | datafangstdato |
| Multiplisitet: | 0..1 |
| Type: | date-time (string) |

| **Navn:** | **datauttaksdato** |
| --- | --- |
| Definisjon: | datauttaksdato |
| Multiplisitet: | 0..1 |
| Type: | date-time (string) |

| **Navn:** | **opphav** |
| --- | --- |
| Definisjon: | opphav |
| Multiplisitet: | 0..1 |
| Type: | string |

| **Navn:** | **kommunenummer** |
| --- | --- |
| Definisjon: | kommunenummer |
| Multiplisitet: | 0..1 |
| Type: | string |
| OGC-rolle: | id |

| **Navn:** | **kommunenavn** |
| --- | --- |
| Definisjon: | kommunenavn |
| Multiplisitet: | 0..1 |
| Type: | string |

| **Navn:** | **samiskforvaltningsomrade** |
| --- | --- |
| Definisjon: | samiskforvaltningsomrade |
| Multiplisitet: | 0..1 |
| Type: | boolean |

#### Kommunegrenser

Kommunegrenser 2024

Geometri:
- itemType: feature
- type: geometry-any
- crs:
  - http://www.opengis.net/def/crs/OGC/1.3/CRS84
  - http://www.opengis.net/def/crs/EPSG/0/3857

Egenskaper

| **Navn:** | **geometry** |
| --- | --- |
| Definisjon: | Elementtype: feature |
| Type: | geometry-any |
| OGC-rolle: | primary-geometry |

| **Navn:** | **objid** |
| --- | --- |
| Definisjon: | objid |
| Multiplisitet: | 0..1 |
| Type: | integer |
| OGC-rolle: | id |

| **Navn:** | **objtype** |
| --- | --- |
| Definisjon: | objtype |
| Multiplisitet: | 0..1 |
| Type: | string |

| **Navn:** | **lokalid** |
| --- | --- |
| Definisjon: | lokalid |
| Multiplisitet: | 0..1 |
| Type: | string |

| **Navn:** | **navnerom** |
| --- | --- |
| Definisjon: | navnerom |
| Multiplisitet: | 0..1 |
| Type: | string |

| **Navn:** | **versjonid** |
| --- | --- |
| Definisjon: | versjonid |
| Multiplisitet: | 0..1 |
| Type: | string |

| **Navn:** | **oppdateringsdato** |
| --- | --- |
| Definisjon: | oppdateringsdato |
| Multiplisitet: | 0..1 |
| Type: | date-time (string) |

| **Navn:** | **gyldigfra** |
| --- | --- |
| Definisjon: | gyldigfra |
| Multiplisitet: | 0..1 |
| Type: | date (string) |

| **Navn:** | **gyldigtil** |
| --- | --- |
| Definisjon: | gyldigtil |
| Multiplisitet: | 0..1 |
| Type: | date (string) |

| **Navn:** | **datafangstdato** |
| --- | --- |
| Definisjon: | datafangstdato |
| Multiplisitet: | 0..1 |
| Type: | date-time (string) |

| **Navn:** | **malemetode** |
| --- | --- |
| Definisjon: | malemetode |
| Multiplisitet: | 0..1 |
| Type: | string |

| **Navn:** | **noyaktighet** |
| --- | --- |
| Definisjon: | noyaktighet |
| Multiplisitet: | 0..1 |
| Type: | integer |

| **Navn:** | **datauttaksdato** |
| --- | --- |
| Definisjon: | datauttaksdato |
| Multiplisitet: | 0..1 |
| Type: | date-time (string) |

| **Navn:** | **opphav** |
| --- | --- |
| Definisjon: | opphav |
| Multiplisitet: | 0..1 |
| Type: | string |

| **Navn:** | **avgrensningstype** |
| --- | --- |
| Definisjon: | avgrensningstype |
| Multiplisitet: | 0..1 |
| Type: | string |

## UML
```plantuml
@startuml
title Administrative enheter kommuner - Objekttyper

skinparam class {
  AttributeIconSize 0
}

package "Objekttyper" {

  class Fylker <<featureType>> {
    + objid [0..1] : Integer
    + objtype [0..1] : CharacterString
    + lokalid [0..1] : CharacterString
    + navnerom [0..1] : CharacterString
    + versjonid [0..1] : CharacterString
    + oppdateringsdato [0..1] : DateTime
    + gyldigfra [0..1] : Date
    + gyldigtil [0..1] : Date
    + datafangstdato [0..1] : DateTime
    + datauttaksdato [0..1] : DateTime
    + opphav [0..1] : CharacterString
    + fylkesnummer [0..1] : CharacterString
    + fylkesnavn [0..1] : CharacterString
    + samiskforvaltningsomrade [0..1] : Boolean
  }

  class Fylkesgrenser <<featureType>> {
    + objid [0..1] : Integer
    + objtype [0..1] : CharacterString
    + lokalid [0..1] : CharacterString
    + navnerom [0..1] : CharacterString
    + versjonid [0..1] : CharacterString
    + oppdateringsdato [0..1] : DateTime
    + gyldigfra [0..1] : Date
    + gyldigtil [0..1] : Date
    + datafangstdato [0..1] : DateTime
    + malemetode [0..1] : CharacterString
    + noyaktighet [0..1] : Integer
    + datauttaksdato [0..1] : DateTime
    + opphav [0..1] : CharacterString
    + avgrensningstype [0..1] : CharacterString
  }

  class Kommuner <<featureType>> {
    + objid [0..1] : Integer
    + objtype [0..1] : CharacterString
    + lokalid [0..1] : CharacterString
    + navnerom [0..1] : CharacterString
    + versjonid [0..1] : CharacterString
    + oppdateringsdato [0..1] : DateTime
    + gyldigfra [0..1] : Date
    + gyldigtil [0..1] : Date
    + datafangstdato [0..1] : DateTime
    + datauttaksdato [0..1] : DateTime
    + opphav [0..1] : CharacterString
    + kommunenummer [0..1] : CharacterString
    + kommunenavn [0..1] : CharacterString
    + samiskforvaltningsomrade [0..1] : Boolean
  }

  class Kommunegrenser <<featureType>> {
    + objid [0..1] : Integer
    + objtype [0..1] : CharacterString
    + lokalid [0..1] : CharacterString
    + navnerom [0..1] : CharacterString
    + versjonid [0..1] : CharacterString
    + oppdateringsdato [0..1] : DateTime
    + gyldigfra [0..1] : Date
    + gyldigtil [0..1] : Date
    + datafangstdato [0..1] : DateTime
    + malemetode [0..1] : CharacterString
    + noyaktighet [0..1] : Integer
    + datauttaksdato [0..1] : DateTime
    + opphav [0..1] : CharacterString
    + avgrensningstype [0..1] : CharacterString
  }
}

@enduml
```

## Rå psdata
```json
{
  "identification": {
    "id": "041f1e6e-bdbc-4091-b48f-8a5990f3cc5b",
    "title": "Administrative enheter kommuner",
    "abstract": "Datasettet viser kommuneinndelinga i landet med de mest nøyaktige grensene som er registrert digitalt og som er samlet i ett datasett. Datasettet har referansedato 1.7.2025, og er oppdatert med overføring av et areal mellom Sel og Vågå ved Liaskarven - Rudihøe, i tillegg til ei retting av kommunegrensa mellom Stavanger og Sola ved Liapynten.\n \nFlatene inneholder egenskaper som forteller om offisielle kommunenumre. De offisielle norske, samiske og kvenske navnene for kommunene er hentet fra SSR. I tillegg finnes informasjon om samiske forvaltningsområder.\n\nGeodataene er fra nasjonal inndelingsbase, som er en del av matrikkelen. Ved overgang til ny forvaltningsløsning, ble det også gjort endringer i UML-modellen.",
    "purpose": "Framstille den offisielle kommuneinndelingen.",
    "language": "nor",
    "keywords": [
      "Kommune",
      "Administrativ inndeling",
      "Administrative grenser",
      "Kommunegrenser",
      "Fylkesgrenser",
      "Riksgrense",
      "ABAS",
      "Norge fastland",
      "Administrative enheter",
      "Det offentlige kartgrunnlaget",
      "Inspire",
      "geodataloven",
      "Norge digitalt",
      "beredskapsbase",
      "dataNorgeNo",
      "fellesDatakatalog",
      "Basis geodata",
      "Norge"
    ],
    "topicCategories": [
      "Administrative grenser"
    ],
    "dates": {
      "creation": "2006-07-01",
      "publication": "2006-07-01",
      "revision": "2025-07-04",
      "metadata": "2025-10-30"
    },
    "responsibleParties": [
      {
        "name": "Liv Mari Nesje",
        "organization": "Kartverket",
        "email": "post@kartverket.no",
        "role": "owner"
      },
      {
        "name": "Liv Mari Nesje",
        "organization": "Kartverket",
        "email": "post@kartverket.no",
        "role": "pointOfContact"
      },
      {
        "organization": "Kartverket",
        "email": "post@kartverket.no",
        "role": "publisher"
      }
    ],
    "supplementalInformation": "Trenger du hjelp til å laste ned og ta i bruk Kartverkets data og tjenester? På kartverket.no finner du tips og veiledning."
  },
  "scope": {
    "level": "dataset",
    "extent": {
      "temporal": {
        "interval": [
          [
            "2006-07-01",
            "2025-07-04"
          ]
        ]
      }
    },
    "legalConstraints": {
      "useLimitation": "Ingen begrensninger på bruk er oppgitt. Se forøvrig lisens.",
      "accessConstraints": "Åpne data",
      "useConstraints": "Lisens",
      "license": "Creative Commons BY 4.0 (CC BY 4.0)",
      "licenseUrl": "https://creativecommons.org/licenses/by/4.0/",
      "securityConstraints": "Ugradert"
    }
  },
  "dataContent": {
    "usage": "Forvaltningsmessig saksbehandling. Analyse og presentasjon i et GIS-system. Presentasjon av statistikk og analyser. Produksjon av kart og avledede produkter. Saksbehandling på lokalt og regionalt plan etter plan- og bygningsloven."
  },
  "referenceSystems": {
    "spatialReferenceSystems": [
      {
        "code": "EPSG:25832",
        "name": "EUREF89 UTM sone 32, 2d"
      },
      {
        "code": "EPSG:25833",
        "name": "EUREF89 UTM sone 33, 2d"
      },
      {
        "code": "EPSG:25835",
        "name": "EUREF89 UTM sone 35, 2d"
      },
      {
        "code": "EPSG:3035",
        "name": "EUREF89 / ETRS89-LAEA Europe"
      },
      {
        "code": "EPSG:4258",
        "name": "EUREF 89 Geografisk (ETRS 89) 2d"
      },
      {
        "code": "EPSG:25832",
        "name": "EUREF89 UTM sone 32, 2d"
      }
    ],
    "spatialRepresentationType": "Vektor"
  },
  "dataQuality": {
    "scope": {
      "level": "dataset"
    },
    "qualityElements": [
      {
        "name": "COMMISSION REGULATION (EU) No 1089/2010 of 23 November 2010 implementing Directive 2007/2/EC of the European Parliament and of the Council as regards interoperability of spatial data sets and services",
        "measure": "Dataene er i henhold til produktspesifikasjonen"
      },
      {
        "name": "SOSI produktspesifikasjon: Administrative enheter Norge",
        "measure": "Dataene er i henhold til produktspesifikasjonen"
      },
      {
        "name": "Sosi applikasjonsskjema",
        "measure": "SOSI-filer er i henhold til applikasjonsskjema"
      },
      {
        "name": "Sosi applikasjonsskjema",
        "measure": "GML-filer er i henhold til applikasjonsskjema"
      },
      {
        "name": "Prosentvis dekning i forhold til datasettets utstrekning",
        "measure": "Datasettets faktiske kartlagte areal i forhold til datasettets spesifiserte utstrekning",
        "result": "100"
      },
      {
        "name": "Prosentvis oppfyllelse av FAIR-prinsipper",
        "measure": "Angir fullstendighet i forhold til krav fra FAIR-prinsippene (The FAIR Guiding Principles for scientific data management and stewardship)",
        "result": "96"
      },
      {
        "name": "FAIR",
        "result": "Prosentvis oppfyllelse av FAIR-prinsipper: 96%"
      },
      {
        "name": "Coverage",
        "result": "Prosentvis dekning i forhold til datasettets utstrekning: 100%"
      }
    ],
    "lineage": {
      "statement": "Trenger du hjelp til å laste ned og ta i bruk Kartverkets data og tjenester? På kartverket.no finner du tips og veiledning."
    }
  },
  "maintenance": {
    "maintenanceFrequency": "Etter behov",
    "maintenanceNote": "Forvaltningsmessig saksbehandling. Analyse og presentasjon i et GIS-system. Presentasjon av statistikk og analyser. Produksjon av kart og avledede produkter. Saksbehandling på lokalt og regionalt plan etter plan- og bygningsloven.",
    "status": "Kontinuerlig oppdatert"
  },
  "delivery": {
    "distributions": [
      {
        "format": {
          "format": "GEONORGE:DOWNLOAD"
        },
        "access": {
          "href": "https://nedlasting.geonorge.no/api/capabilities/",
          "protocol": "GEONORGE:DOWNLOAD"
        }
      },
      {
        "title": "Geonorge nedlastning",
        "format": {
          "format": "Geonorge nedlastning"
        },
        "access": {
          "href": "https://nedlasting.geonorge.no/api/capabilities/",
          "protocol": "GEONORGE:DOWNLOAD"
        }
      },
      {
        "title": "Administrative enheter WMS",
        "format": {
          "format": "png"
        },
        "access": {
          "href": "https://wms.geonorge.no/skwms1/wms.adm_enheter2?service=wms&request=GetCapabilities",
          "protocol": "WMS-tjeneste",
          "license": "Åpne data"
        },
        "notes": "Tjeneste"
      }
    ]
  },
  "metadata": {
    "standard": "ISO19115",
    "standardVersion": "2003",
    "metadataDate": "2025-10-30",
    "language": "nor",
    "pointOfContact": {
      "organization": "Kartverket",
      "email": "post@kartverket.no",
      "role": "pointOfContact"
    },
    "identifiers": [
      {
        "authority": "geonorge",
        "code": "041f1e6e-bdbc-4091-b48f-8a5990f3cc5b"
      }
    ],
    "metadataUrl": "https://www.geonorge.no/geonetwork/srv/nor/csw?service=CSW&request=GetRecordById&version=2.0.2&outputSchema=http://www.isotc211.org/2005/gmd&elementSetName=full&id=041f1e6e-bdbc-4091-b48f-8a5990f3cc5b"
  },
  "links": [
    {
      "href": "https://www.geonorge.no/geonetwork/srv/nor/csw?service=CSW&request=GetRecordById&version=2.0.2&outputSchema=http://www.isotc211.org/2005/gmd&elementSetName=full&id=041f1e6e-bdbc-4091-b48f-8a5990f3cc5b",
      "rel": "describedby",
      "type": "application/xml",
      "title": "Metadata (ISO 19139)"
    },
    {
      "href": "https://nedlasting.geonorge.no/api/capabilities/",
      "rel": "enclosure",
      "type": "text/html",
      "title": "Nedlasting"
    },
    {
      "href": "#!?zoom=3&lon=306722&lat=7197864&wms=https://wms.geonorge.no/skwms1/wms.adm_enheter2",
      "rel": "service",
      "type": "text/html",
      "title": "Tjeneste"
    },
    {
      "href": "https://wms.geonorge.no/skwms1/wms.adm_enheter2?service=wms&request=GetCapabilities",
      "rel": "service",
      "type": "application/xml",
      "title": "Tjeneste-distribusjon"
    }
  ]
}
```
