---
title: Master Address File (MAF)
created: '2020-11-10T16:58:55.078305'
modified: '2020-11-10T16:58:55.078312'
state: active
type: dataset
tags:
  - Address
  - Address Locations
  - Addresses
  - Cosgis
  - Maf
  - Seattle
  - Seattlecitygis
  - Transpo
  - Wa
  - Wm_transpo_mafdap
groups:
  - Local Government
csv_url: >-
  https://data-seattlecitygis.opendata.arcgis.com/datasets/36a74a49c2fd45f7918706b0f6e8be3e_1.csv?outSR=%7B%22latestWkid%22%3A2926%2C%22wkid%22%3A2926%7D
json_url: 'https://gisdata.seattle.gov/server/rest/services/COS/COS_Transpo/MapServer/1'
layout: post

---
Displays citywide address points using TRANSPO.MAFDAP_PV.  Differs from 
TRANSPO.DAP in that it contains address data.  Attributes include house 
number and modifier, directional, street name, and street type.  Does 
not display when zoomed out beyond 1:10,000.  Labels are based on the 
attribute MAF_HSENUMMOD and do not display when zoomed out beyond 
1:3,000. ATTRIBUTE INFORMATION: MAILUSECODE ? Identifies suitability of 
MAF address and associated MAFUNIT record(s) for use as a mailing 
address. This field serves as an indicator whether the address is being 
utilized in the City?s Utility Billing System. If so, it is more likely 
(but still not guaranteed) to be a valid mailing address. DCLUSTAT - 
Description of address establishment and validation status related to 
DCLU business                        process.  Valid values:  ?INITIAL 
VALUE?  ? SPU-added records are assigned this value upon creation.   
?DRAFT? ? only DPD-added records are assigned this value upon creation. 
  ?FIELD VERIFIED? ? only DPD can assign this value. Indicates that DPD 
at some point  conducted a site visit. This value is not reliably 
assigned and is not necessarily an indicator of a correct address.  
?CANCELED? ? only DPD can assign this value. The address was never 
utilized.  ?RETIRED? ? DPD or SPU can assign this value. The address may
 have been utilized for some period of time but was then replaced by a 
different address for the location or retired from use completely. 
DCLUSTATDT - Date of creation or modification of record. SOURCENAME - 
Descriptive character string identifying  agency, department or 
divisional record    source or usage. Valid values:  ?DPD_MAF? ? Added 
or modified by DPD  ?CGDB_MAFEDITS? ? Added or modified by SPU  
?INIT_MAF? ? The initial record value, likely harvested from King County
 Assessor data when the     MAF/DAP was first implemented.
