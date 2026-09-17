# Spatial Analysis of Older Adult Population and Hospital Accessibility in Alachua County, Florida

This GIS project examines how hospital accessibility varies across Alachua County, Florida, with a focus on adults age 65 and older. The analysis combines block-level demographic data, hospital locations, distance-based accessibility measures, and spatial statistics to identify areas where older populations may face lower access to hospital services.

## Project Overview

The project was completed in Spring 2026 for GIS 3043: Foundations of Geographic Information at the University of Florida. The final deliverable was a research poster summarizing the workflow, maps, statistical results, findings, limitations, and future research directions.

[View the final poster (PDF)](Hospital_Accessibility_Alachua_County.pdf)

## Data Sources

- U.S. Census Bureau TIGER/Line shapefiles for 2020 Census block boundaries
- U.S. Census Bureau 2020 Census Demographic and Housing Characteristics data
- FloridaHealthFinder hospital location information

## Methods

The analysis was completed in ArcGIS Pro and included:

- Geocoding hospital addresses
- Joining demographic attributes to Census block boundaries
- Mapping the population age 65 and older
- Euclidean Distance analysis for hospital accessibility
- Reclassification of blocks into accessibility categories
- Summary statistics by accessibility category
- Global Moran's I to evaluate spatial autocorrelation
- Hot Spot Analysis to identify statistically significant spatial clustering

## Key Findings

Most older adults in Alachua County were located in areas classified as having high hospital accessibility. Lower-access older populations were concentrated more heavily near the county boundaries, while the Gainesville area generally showed higher accessibility.

The Global Moran's I result indicated spatial clustering rather than a random distribution, and the Hot Spot Analysis identified clustering of lower-access older populations near the county edges.

## Poster

The full poster includes the study-area map, analysis workflow, accessibility map, hot-spot map, block-level older-adult population map, statistical results, discussion, limitations, and future research.

[Open the final poster](Hospital_Accessibility_Alachua_County.pdf)
