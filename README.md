# AES408 Final Project
# NDVI & NDBI Analysis of Vegetation and Urban Change in Jefferson County, Alabama 
# Overview
## This project analyzes vegetation change and urban development in Jefferson County, Alabama from 1990 to 2025 using Landsat satellite imagery. The analysis uses two remote sensing indices:

### NDVI (Normalized Difference Vegetation Index) to measure vegetation health
### NDBI (Normalized Difference Built-up Index) to identify urban and developed areas

## By comparing multiple years of satellite data, this project examines how vegetation and urban development have changed over time.

# Objectives
## Analyze long-term vegetation trends using NDVI
## Identify expansion of built-up areas using NDBI
## Compare vegetation and urban growth patterns over time
## Provide insights relevant to urban planning and environmental management

# Study Area

## Jefferson County, Alabama (Birmingham metropolitan area), which has experienced significant population growth and urban development over the past several decades.

# Data Sources
## Jefferson County Boundary Shapefile: https://data-jeffco-al.opendata.arcgis.com/datasets/a470dbef36124cde85cf3ac606a5475f_4/explore
## Landsat Collection 2 Level-2 Imagery (USGS EarthExplorer): https://earthexplorer.usgs.gov/
## ChatGPT was also used to assist with coding support and explanation of geospatial processing steps. 

# Years used in analysis:
## 1990, 2000, 2010, 2015, 2025

# Methods

## The analysis was completed using Python and geospatial libraries.

# Key steps include:

## Loading Landsat surface reflectance data
## Clipping rasters to Jefferson County boundary
## Aligning datasets to a common spatial grid
## Masking clouds and shadows using the QA_PIXEL band
## Calculating NDVI and NDBI for each year
## Generating maps and change detection outputs
## Creating a time series trend graph of NDVI and NDBI

# Tools & Libraries:
## Python
## rasterio
## numpy
## matplotlib
## geopandas


# Outputs

## The project produces:

## NDVI maps for each year (1990–2025)
## NDBI maps for each year
## NDVI & NDBI trend graph
## NDVI and NDBI change maps (2025 – 1990)

### These outputs are saved as image files and used for analysis and visualization.

# Key Findings
## Urban development increased over time, especially around Birmingham
## Built-up areas expanded outward along major roads and suburban regions
## Vegetation remained relatively stable overall despite urban growth
## Changes in vegetation were more localized rather than widespread

# Relevance

## This analysis can be useful for:

## City planners – understanding patterns of urban expansion
## Environmental agencies – monitoring vegetation health
## Local decision-makers – supporting sustainable land use planning


# Author

## Kaitlyn Davis
## AES 408
