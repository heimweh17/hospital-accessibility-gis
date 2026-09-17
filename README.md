# A Spatial Analysis of the Older Adult Population and Hospital Accessibility in Alachua County, Florida

This GIS project examines hospital accessibility across Alachua County, Florida, with a focus on adults age 65 and older. It combines block-level demographic data, hospital locations, distance-based accessibility measures, and spatial statistics to identify areas where older populations may face lower access to hospital services.

**Final deliverable:** [View the research poster (PDF)](Hospital_Accessibility_Alachua_County.pdf)

## Project Overview

Completed in Spring 2026 for GIS 3043: Foundations of Geographic Information at the University of Florida, the project developed an end-to-end spatial analysis workflow in ArcGIS Pro, from demographic and facility data preparation through accessibility modeling and spatial-statistical analysis.

## Data Sources

- U.S. Census Bureau TIGER/Line shapefiles for 2020 Census block boundaries
- U.S. Census Bureau 2020 Census Demographic and Housing Characteristics data
- FloridaHealthFinder hospital facility locations

## GIS Methods

- Geocoded hospital addresses and mapped facility locations
- Joined demographic attributes to Census block boundaries
- Mapped the population age 65 and older at the block level
- Used Euclidean Distance to model proximity to hospitals
- Reclassified areas into hospital-accessibility categories
- Summarized older-adult population by accessibility category
- Applied Global Moran's I to evaluate spatial autocorrelation
- Applied Hot Spot Analysis to identify statistically significant spatial clustering

## Key Findings

Most older adults in Alachua County were located in areas classified as having relatively high hospital accessibility. Lower-access older populations were more concentrated near county boundaries, while the Gainesville area generally showed higher accessibility.

Global Moran's I indicated that the spatial pattern was clustered rather than random, and Hot Spot Analysis highlighted clustering of lower-access older populations near the county edges.

## Skills Demonstrated

ArcGIS Pro · Geocoding · Census/TIGER data · Attribute joins · Raster distance analysis · Spatial classification · Global Moran's I · Hot Spot Analysis · Cartographic visualization

## Poster

The final poster presents the study area, workflow, hospital-accessibility analysis, block-level older-adult population patterns, spatial-statistical results, discussion, limitations, and future research directions.

[Open the final poster](Hospital_Accessibility_Alachua_County.pdf)
