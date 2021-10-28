# Chicago Crime Analysis and Modeling
 
This repository stores an OLAP analytical project I did with the Chicago historical crime [dataset](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2).

The dataset is routinely updated and has all crime reports from 2001 to present. Due to the huge number of records in the dataset (7 million+ by the time I downloaded it), I used PySpark to perform the queries and addressed the OLAP questions.

## Objectives

This project is composed of four main parts:

1. Perform OLAP queries to extract key information from the dataset and address specific questions;
2. Create a geographical heatmap to visualize the distribution of crimes across the city;
3. Perform clustering using the spatial data, and give advice on how to select ideal locations for police stations and helicopter patrol centers;
4. Perform time series analysis and forecast the number of crimes in the future using historical crime data and temperature data;

## Results

The results of the analyses can be found in this [notebook](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/7069135374172990/4240259191993878/8540672038212706/latest.html) published on Databricks. **A report summary is given at the end of the notebook.** A local version of the notebook is provided in this repository as well.

*Note: If the geographical map is not showing in the published notebook, you can find a saved html file of the map in this repository.*