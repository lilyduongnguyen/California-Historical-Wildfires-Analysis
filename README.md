# California Wildfires Analysis

![Image Description](https://static.scientificamerican.com/sciam/cache/file/0C8BD25C-3814-473A-A6EEE732A3726872_source.jpg)

## Table of Contents
- [Introduction](#introduction)
- [Data Sources](#data-sources)
- [Data](#data)
- [Analysis](#analysis)
- [Usage](#usage)
- [Results](#results)

## Introduction

This project aims to analyze the trends and characteristics of wildfires in California. It utilizes geospatial data and attribute tables to examine various aspects such as fire causes, burned areas, and temporal patterns.

## Data Sources

The project utilizes the following data sources:

1. California Fire Perimeters (all) GeoJSON: This GeoJSON file contains information about the perimeters of wildfires in California. You can access the file [here](https://gis.data.ca.gov/datasets/CALFIRE-Forestry::california-fire-perimeters-all-1/explore?location=37.363062%2C-118.992700%2C6.72&showTable=true).

2. California County Boundaries GeoJSON: This GeoJSON file provides the boundaries of counties in California. You can access the file [here](https://gis.data.ca.gov/datasets/8713ced9b78a4abb97dc130a691a8695_0/explore?location=37.083634%2C-119.002032%2C6.70&showTable=true).

## Data

The data used in this analysis includes three large files. You can access the data files through the following [Google Drive folder](https://drive.google.com/drive/folders/1Yk_NssjayTfKWJwFgg93CAkYmhfb714G?usp=sharing). The data files are as follows:

- **California_Fire_Perimeters_(all).geojson**: Contains information about wildfire perimeters in California, including attributes such as fire name, cause, agency, burned acres, and dates.
- **agency_code.xlsx**: Provides information about the agencies involved in fire management and suppression.
- **cause_code.xlsx**: Contains a list of fire causes and their corresponding codes.
- **collection_method.xlsx**: Provides information about the collection methods used to gather fire data.
- **type_of_fire.xlsx**: Contains information about different types of fires.

Please download these files from the provided Google Drive folder and ensure they are placed in the appropriate directory before running the code.

## Analysis

The analysis consists of the following steps:

1. Importing the required libraries and datasets.
2. Data cleaning and preprocessing to handle missing values and anomalies.
3. Exploratory data analysis to identify trends in wildfire occurrence and burned areas over the years.
4. Analyzing the causes of wildfires and their distribution throughout the months.
5. Spatial analysis to visualize the geographic distribution of wildfires in California using county boundaries and burned acreage data.

## Usage

To run the analysis and explore the findings, follow these steps:

1. Install the required libraries by running the following command:
```
%pip install geopandas pandas matplotlib seaborn contextily
```

2. Import the necessary libraries and files using the provided code in the "IMPORT LIBRARIES AND FILES" section.

3. Clean the data by executing the data cleaning code provided in the "DATA CLEANING" section. This includes handling missing values, data type conversions, and fixing anomalies.

4. Perform exploratory data analysis using the code snippets provided in the "EXPLORATORY DATA ANALYSIS" section. This includes visualizations of wildfire trends over the years, causes of wildfires, and spatial analysis of wildfire distribution.

## Results

The analysis provides insights into the following aspects:


- Trends in the occurrence and burned areas of wildfires in California over the years.
- Distribution of wildfires by their causes and monthly patterns.
- Spatial distribution of wildfires across different counties in California.

The visualizations and analysis findings help understand the dynamics of wildfires in California and can be valuable for policymakers, fire management agencies, and researchers working in the field of wildfire prevention and mitigation.

