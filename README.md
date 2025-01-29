# Zimbabwe-Revised-Agroecological-Zones
Newly revised Agroecological Zones for Zimbabwe
# Zimbabwe Revised Agro-Ecological Zones (AEZs) Report

## Overview
This repository contains the report on the revised Agro-Ecological Zones (AEZs) of Zimbabwe. The report details the updated zoning classifications based on climate variability, land use changes, and improved mapping techniques. The document is available in multiple formats, including HTML, PDF, and Word.

## Contents
- **Report Files:**
  - `Zim-AEZs.html` (HTML version)
  - `Zim-AEZs.pdf` (PDF version with table of contents, figure captions, and numbered sections)
  - `Zim-AEZs.docx` (Word document with table of contents)
- **Code Files:**
  - `generate_AEZ_map.R` (R script to generate the AEZ map)
- **Shapefile Data:**
  - `Zim_regions.shp` (Shapefile containing AEZ boundaries)
  - Supporting spatial data files required for GIS processing

## Key Highlights of the Report
- **Introduction:** Importance of AEZs in guiding agricultural practices, natural resource management, and policy planning.
- **Revised AEZs:** Updated classification into six primary zones: Region I, IIa, IIb, III, IV, Va, and Vb.
- **Key Changes:**
  - Increased detail with subdivision of Region V into Va and Vb.
  - Emphasis on climate adaptation strategies.
  - Use of modern GIS-based mapping techniques.
- **Implications:** How the updated AEZs contribute to climate-smart agriculture, sustainable land use, and improved food security.
- **Conclusion:** The importance of ongoing research and monitoring to enhance AEZ effectiveness.
- **References:** Supporting research and official publications.

## Generating the AEZ Map
The `generate_AEZ_map.R` script processes the shapefile and visualizes the revised AEZs using R packages such as `sf` and `ggplot2`.

### Requirements
- R (latest version recommended)
- R packages:
  - `sf`
  - `ggplot2`

### Running the Script
Ensure the `Zim_regions.shp` file is available in the specified directory, then execute the script in R:
```r
source("generate_AEZ_map.R")
```

This will generate a high-resolution map and save it as `Revised_AEZs.pdf`.



