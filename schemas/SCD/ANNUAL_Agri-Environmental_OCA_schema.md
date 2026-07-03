---
layout: default  
title: Agri-Environmental Indicator – Soil Cover Days - Annual
parent: Annual Soil Cover Days
---

# Schema information
{: .no_toc }



**Name**: Agri-Environmental Indicator – Soil Cover Days - Annual  
**Description**: The Agri\-Environmental Indicator Soil Cover Days dataset provides a calculation of the number of days in a year that the soil of Canada agricultural lands is covered by a crop, crop residues on its surface, or snow. The dataset provide long term soil cover at the annual basis and at the Soil Landscape of Canada scale.  
**Classification**: RDF105  
**Schema package SAID**: EMgCc1-q_S-95YbUhZCzZJ1ebhAYetTupp8kVNudHC3s  

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| SOIL_LANDSCAPE_ID | Soil Landscape ID | Soil Landscape of Canada Polygon Identifier |
| YEAR | Year | The year of the data. |
| PROVINCE | Province | The provincial name that the data falls within. |
| PROV_PCT | Province Percent | The percentage weighting given the portion of the Soil Landscape of Canada polygon (identified by the SOIL_LANDSCAPE_ID) that falls in the identified province. If a Soil Landscape of Canada polygon is split by a provincial boundary, this value will |
| POLYGON_WEIGHT | Polygon Weight | The area of the portion of the spatial unit based on which the indicator is evaluated. It is used as the weighting factor when the indicator is scaled up to a larger spatial unit. For the soil cover indicator, it is equal to the total agricultural la |
| SCD_VAL | Soil Cover Days | The equivalent number of days in a year a soil is not exposed to air. |
| SCD_CLASS | Soil Cover Days Classification | Classes categorizing the soil cover status into 5 different levels according to Soil Cover Days. |
| SCD_CLASS_EN | Soil Cover Days Classification – English | Textual Description of the Class in English |
| SCD_CLASS_FR | Soil Cover Days Classification – French | Textual Description of the Class in French |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Agri-Environmental Indicator – Soil Cover Days - Annual | The Agri\-Environmental Indicator Soil Cover Days dataset provides a calculation of the number of days in a year that the soil of Canada agricultural lands is covered by a crop, crop residues on its surface, or snow. The dataset provide long term soil cover at the annual basis and at the Soil Landscape of Canada scale. |

## Selection lists

### English

#### SCD_CLASS entry codes

| Entry code | Label |
| --- | --- |
| 1 | Very Low (SCD_VAL <=250) |
| 2 | Low (250-274) |
| 3 | Moderate (275-299) |
| 4 | High (300-324) |
| 5 | Very High (SCD_VAL >= 325) |
| -1 | Not Assessed (area not evaluated) |

#### SCD_CLASS_EN entry codes

| Entry code | Label |
| --- | --- |
| 1 | Very Low (VAL <=250) |
| 2 | Low (250 < VAL <= 274) |
| 3 | Moderate (275 < VAL <= 299) |
| 4 | High (300 < VAL <= 325) |
| 5 | Very High (VAL > 325) |
| -1 | Not Assessed (area not evaluated) |

#### SCD_CLASS_FR entry codes

| Entry code | Label |
| --- | --- |
| 1 | Très faible (VAL <=250) |
| 2 | Faible (250 < VAL <= 274) |
| 3 | Moyen (275 < VAL <= 299) |
| 4 | Élevé (300 < VAL <= 325) |
| 5 | Très élevé (VAL > 325) |
| -1 | Elément non évalué (area not evaluated) |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| SOIL_LANDSCAPE_ID | false |  | Numeric |  |
| YEAR | false |  | Numeric |  |
| PROVINCE | false |  | Text |  |
| PROV_PCT | false |  | Numeric |  |
| POLYGON_WEIGHT | false |  | Numeric |  |
| SCD_VAL | false |  | Numeric |  |
| SCD_CLASS | false |  | Numeric |  |
| SCD_CLASS_EN | false |  | Text |  |
| SCD_CLASS_FR | false |  | Text |  |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| SOIL_LANDSCAPE_ID | Soil Landscape ID | Soil Landscape of Canada Polygon Identifier | Not a list |
| YEAR | Year | The year of the data. | Not a list |
| PROVINCE | Province | The provincial name that the data falls within. | Not a list |
| PROV_PCT | Province Percent | The percentage weighting given the portion of the Soil Landscape of Canada polygon (identified by the SOIL_LANDSCAPE_ID) that falls in the identified province. If a Soil Landscape of Canada polygon is split by a provincial boundary, this value will | Not a list |
| POLYGON_WEIGHT | Polygon Weight | The area of the portion of the spatial unit based on which the indicator is evaluated. It is used as the weighting factor when the indicator is scaled up to a larger spatial unit. For the soil cover indicator, it is equal to the total agricultural la | Not a list |
| SCD_VAL | Soil Cover Days | The equivalent number of days in a year a soil is not exposed to air. | Not a list |
| SCD_CLASS | Soil Cover Days Classification | Classes categorizing the soil cover status into 5 different levels according to Soil Cover Days. | Very Low (SCD_VAL <=250), Low (250-274), Moderate (275-299), High (300-324), Very High (SCD_VAL >= 325), Not Assessed (area not evaluated) |
| SCD_CLASS_EN | Soil Cover Days Classification – English | Textual Description of the Class in English | Very Low (VAL <=250), Low (250 < VAL <= 274), Moderate (275 < VAL <= 299), High (300 < VAL <= 325), Very High (VAL > 325), Not Assessed (area not evaluated) |
| SCD_CLASS_FR | Soil Cover Days Classification – French | Textual Description of the Class in French | Très faible (VAL <=250), Faible (250 < VAL <= 274), Moyen (275 < VAL <= 299), Élevé (300 < VAL <= 325), Très élevé (VAL > 325), Elément non évalué (area not evaluated) |

## Schema SAIDs

**Capture base**: EHIMfwKfGSvsVCrxjQzqo0JseYwknK0FBZ5Frtk03bmG

**Bundle**: EGI69n5SSzjo1fKXO01J9oS8VBr_GRFtpwaKtTJb4fGf

**Package**: EMgCc1-q_S-95YbUhZCzZJ1ebhAYetTupp8kVNudHC3s

| Layer | SAID | Type |
| --- | --- | --- |
| entry (eng) | EAhSjvAtc8wkVQIrwuaT7MRVXlx-s_f-UrQLkN2IUdex | spec/overlays/entry/1.1 |
| entry_code | ENl6ZeliAmud1qQ9Hu1JAOgFKOMEOZaqu3vUyA-l_n4I | spec/overlays/entry_code/1.1 |
| information (eng) | ENaAnitoMcF41cwU9H1eOUpzqfirkQEXwRC_o_34U3Rc | spec/overlays/information/1.1 |
| label (eng) | EK1vVE0tmYF4jMTzXcMptPcBX93V_JJTUSpU3fVvdxBY | spec/overlays/label/1.1 |
| meta (eng) | EKDtVQJknFJdi-TPZOeJwALN8Kvh9XDT_u-NrMrTiHnV | spec/overlays/meta/1.1 |
| ordering | ELnk3iG_bhJkoXE01C7-u5DGKAJhuDVSCjWvHxirXlHF | community/overlays/adc/ordering/1.0 |

**Date created**: 2026-06-16 15:46:01

