# Uber-Data-Eng

This repo is a sample Data Engineering project with modern tech stack to analyse Taxi Data.

## Dataset used
The dataset used is publicly available from [here](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page).
The data include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts.

Data dictionary is found [here](https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf)

## Tech Stack
Programming Languages - Python, SQL
1. Google Cloud Storage - To store the source data as a flat csv file
2. Compute Instance - VM to run Mage and transformation code
3. Mage AI -  A modern data pipeline tool. Using this tool extract the flat file, do some transformations, convert the flat format to dimensional model (star schema) which is then loaded into Big Query
4. BigQuery - Serverless Data Warehouse in GCP
5. Looker Studio - Visualisation and Dashboard tool

## Architecture Diagram
<img src="architecture.jpg">

## Dimensional Data Model
<img src="Uber Data Model.jpeg">

