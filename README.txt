This README.txt file was generated on 20220407 by IVAN CARDENAS, LAKSHMIPRIYA SABU and EMERALD AWUOR


-------------------
GENERAL INFORMATION
-------------------

Title of Dataset: Senegal Fisheries

Author Information (Ivan Cardenas-Leon,Lakshmipriya Sabu,Emerald Awuor, ITC, Hengelostraat 99, Enschede, NL  )

Date of data collection 2022-03 - Collected by Charis Chalkiadakis

Geographic location of data collection: Senegal, West Africa.

Information about funding sources or sponsorship that supported the collection of the data: Impact of International Fish trade flows in Africa, 2018-05.


--------------------------
SHARING/ACCESS INFORMATION
-------------------------- 

This work is licensed under a Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License (CC BY-NC-ND 4.0). See LICENSE file for details. Please contact Authors.

Recommended citation for the data: Cardenas-Leon, et al. (2022)


--------------------
DATA & FILE OVERVIEW
--------------------


DATA--|
	|Raster-----|
	|		|220330_UrbanAreasSenegal_v1.tif | Source:Global Human Settlement Layer (2019)
	|SHP--------|
			|210218_Landingsites_v1.shp | Source: PRCM (2021)
			|220330_RoadNetwork_v1.shp | Source: OSM (2022)
			|220330_Boundaries_v1.shp | Source: OSM (2022)
			|210218_SardinelaSpExtent_v1.shp | Source: OBIS (2022) | Derived from CSV file.
                  |Exclusive Economic Zones_v1.shp| Source :Flanders Marine Institute(2019)
                  |Protected Areas_v1.shp|UNEP-WCMC and IUCN(2022)
			|
	|Spredsheets|SardinelaSpatialExtent_v1.csv | Source: OBIS(2022) | Geo points were derived from this layer
			|Catch of biomass_v1.pdf|Source:DPM(2018)| The data values are derived from DPM report
			





--------------------------
METHODOLOGICAL INFORMATION
--------------------------

Description of methods used for collection/generation of data: 220330_UrbanAreasSenegal_v1.tif | Source:Global Human Settlement Layer (2019)| https://ghsl.jrc.ec.europa.eu/download.php
                                                             : 210218_Landingsites_v1.shp | Source: PRCM (2021)| https://prcmarine.org/
                                                             : 220330_RoadNetwork_v1.shp | Source: OSM (2022)| https://www.openstreetmap.org/export#map=7/14.477/-14.548
                                                             : 220330_Boundaries_v1.shp | Source: OSM (2022)| https://www.openstreetmap.org/export#map=7/14.477/-14.548
                                                             : 210218_SardinelaSpExtent_v1.shp | Source: OBIS (2022)| https://www.openstreetmap.org/export#map=7/14.477/-14.548
                                                             : Exclusove Economic Zones_v1.shp| Source :Flanders Marine Institute(2019)| https://www.vliz.be/en/data-search
                                                             : Protected Areas_v1.shp|UNEP-WCMC and IUCN(2022)| https://www.iucn.org/theme/protected-areas/our-work/quality-and-effectiveness/world-database-protected-areas-wdpa
                                                             : SardinelaSpatialExtent_v1.csv | Source: OBIS(2022)| https://www.gbif.org/network/2b7c7b4f-4d4f-40d3-94de-c28b6fa054a6/dataset
                                                             : Catch of biomass_v1.pdf|Source:DPM(2018)| http://hdl.handle.net/1834/15921

Methods for processing the data: Network Analysis was performed to calculate the Origin-Destination distances. The segments were later processed to calculate the DOT and CO2 Emissions.

Software- or Instrument-specific information needed to interpret the data, including software and hardware version numbers: ArcGIS PRO 2.7
