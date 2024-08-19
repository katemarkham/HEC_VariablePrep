Author: Katherine Markham.

Publication_Date: 20240819.

Title: HEC_VariablePrep

Online_Linkage: Link to published manuscript forthcoming.

Abstract:  This Google Earth Engine (GEE) script 1) calculates distance from certain land cover types, as well as  distance from buildings, roads, and rivers, and building density. Rivers, roads, and buildings are from Open Street Map (OSM). 2) This script uses Landsat 8, elevation from JAXA, CHIRPS' precipitationand calculates NDVI, SAVI, & NDMI from Landsat 8 imagery.  3) It then extracts those values recorded at each point over the specified dates. Those values are exported as a table to a folder in Google Drive. Refer to published manuscript for more information on methods.

Dependencies:
 To run this script requires: 1) table of points projected into ESPG: 4326, 2) assets of agricultural land and 2) forest by year, 3) assets of buildings, roads, and rivers from OSM or other source.  4) Dates of conflict specified. All other data is extracted from EE datasets. 

Supplemental_Information: Other scripts related to this HEC project include machine learning algorithms in R and Python.

Progress: Complete.

Point_of_Contact: Katherine Markham.

Native_Environment: Run using Google Earth Engine API.

Completeness_Report: Users must provide own conflict data.
