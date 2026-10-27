1. Project Overview

This project focuses on understanding rainfall variability, groundwater conditions, agricultural water demand and groundwater recharge in Jhunjhunu district, Rajasthan.

The study aims to establish a preliminary understanding of the region's hydro-climatic conditions using historical rainfall, groundwater-level, groundwater-resource and agricultural datasets.

The collected information will provide a foundation for subsequent hydrological assessment, spatial analysis and the identification of potential groundwater recharge and water-management strategies.

2. Study Area

The study focuses on Jhunjhunu district, Rajasthan, India.

The current dataset includes groundwater observations from five monitoring locations:

Birmi

Churela

Devroad

Dighal

Dulania1

The groundwater-resource assessment also provides district/block-level information.Therrre are total 31 stations but till now I worked on 5 station only.

Note: The five monitoring locations and district-level datasets do not yet constitute a complete urban municipal-scale spatial assessment.

3. Objectives

Analyse historical rainfall variability.

Examine groundwater-level fluctuations.

Assess groundwater recharge and extraction conditions.

Investigate agricultural crop-area patterns, which crops are considered and their implications for irrigation demand.

Establish a preliminary database for subsequent integrated water-management analysis.

Crop water Requirement Estimation.

Farmer Income Quantification and Drip irrigation working

4. Datasets Collected

Dataset 1: Groundwater Levels

Source: India-WRIS / Central Ground Water Board (CGWB)

Period: 2005–2023

Locations: Birmi, Churela, Devroad, Dighal and Dulania1

Format: Excel (.xlsx)

Purpose: Preliminary groundwater-level trend analysis.

Dataset 2: Rainfall Data

Source: IMDWeb (India Meteorological Department)

Period: 2005–2023

Temporal Resolution: Monthly

Format: CSV and PNG visualization

Purpose: Preliminary rainfall variability analysis.

Data quality note: The currently prepared CSV is an approximate digitisation of the rainfall visualization. It is not the original IMD numerical dataset and should not be treated as official measured rainfall values.

Dataset 3: Groundwater Resources

Source: Central Ground Water Board (CGWB)

Report: Dynamic Ground Water Resources of Rajasthan, 2025

Coverage: Rajasthan and Jhunjhunu assessment units

Format: PDF

Purpose: Understanding groundwater recharge, extraction and resource availability.

Dataset 4: Agricultural Crop Area

Source: Rajasthan Government agricultural statistics

Period: Available data for 2019–20 to 2022–23

Crops: Wheat, mustard, bajra, gram and other available crops

Format: Excel (.xlsx)

Purpose: Preliminary assessment of agricultural land use and irrigation demand.

The crop-area dataset is partially complete. Irrigated crop-area statistics and missing historical records are yet to be consolidated.

5. Software and Tools

QGIS – Geospatial analysis and mapping.

Python – Data processing, analysis and visualization.

Microsoft Excel – Dataset organisation and preliminary analysis.

6. Repository Structure

Jhunjhunu/
│
├── README.md
│
├── data/
│   ├── raw/
│   │   ├── groundwater_levels/
│   │   ├── rainfall/
│   │   ├── cgwb_groundwater_resources/
│   │   └── crop_area/
│   │
│   └── processed/
│
├── figures/
│
├── scripts/
│
├── sources/
│
└── reports/

7. Current Project Status

The project is currently at the preliminary data-acquisition and organisation stage.

Component

Current Status

Groundwater-level data

Initial collection completed

Rainfall data

Visualization obtained; numerical data consolidation ongoing

CGWB groundwater assessment

Report obtained

Crop-area data

Partially collected

Irrigated crop-area data

Pending

Data cleaning

Ongoing

QGIS spatial analysis

Pending

Hydrological modelling

Pending

8. Data Limitations

The rainfall CSV currently contains approximate image-derived values as from IMDWeb website it is not possible to download csv file in readable format thatswhy I made the Excel sheet from the image which I got from visualize the result.

Crop-area information is available only for selected years and crops.

Irrigated crop-area information is incomplete.

Available datasets have different spatial resolutions.
9. Planned Next Steps

Complete the collection and verification of historical rainfall data.

Clean and standardise groundwater-level records.

Complete crop-area and irrigated-area datasets.

Integrate spatial datasets using QGIS.

Conduct preliminary groundwater and rainfall trend analysis.

Identify relevant areas for further flood-management and groundwater-recharge assessment.

10. Data Sources

India-WRIS: https://indiawris.gov.in/

Central Ground Water Board: https://cgwb.gov.in/

IMDWeb: https://imdweb.lwcc.in/

Government of Rajasthan: Official agricultural statistics
