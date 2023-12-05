# Uber Data Analytics | End to end  Data Engineering Project

## Introduction

This is the project implemented by the idea of darshilparmar. The goal of this project is to perform data analytics on Uber data using various tools and technologies, including Python, Mage, Snowflake, and Looker Studio.

## Architecture 
<img src="architecture.jpg">

## Technology Used
- Programming Language - Python
- Mage
- Snowflake
- Looker Studio

Modern Data Pipeine Tool - https://www.mage.ai/

Contibute to this open source project - https://github.com/mage-ai/mage-ai


## Dataset Used
TLC Trip Record Data
Yellow and green taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. 

Here is the dataset used in the video - https://github.com/dlowji/uber_data_analytics/blob/master/uber_data.csv

More info about dataset can be found here:
1. Website - https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
2. Data Dictionary - https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf

## Data Model
<img src="data_model.jpeg">

## Config Snowflake connection
In order to export data from Mage to Snowflake, you need to configure these variables in io_config.yaml stored inside Mage hosted in your localhost:

-- Snowflake
  SNOWFLAKE_USER: your_user
  SNOWFLAKE_PASSWORD: your_password
  SNOWFLAKE_ACCOUNT: your_account_id.your_region
