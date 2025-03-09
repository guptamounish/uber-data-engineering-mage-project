# Uber Data Analytics | Modern Data Engineering GCP Project

## Introduction
This project leverages cutting-edge technologies such as mage.AI, BigQuery, Looker Studio, and Google Cloud Storage to develop a comprehensive data analytics platform tailored for Uber's operational data. By integrating these advanced tools, the project aims to enhance data processing efficiencies, enable deeper analytical insights, and support data-driven decision-making across Uber’s various service domains. This modern data engineering initiative on Google Cloud Platform represents a strategic effort to harness the full potential of big data in the transportation industry.


## Architecture
![Project Architecture](architecture.jpg)

## Technology Used
1. Programming Language - Python
2. Scripting Language - SQL
3. Google Cloud Platform
   - BigQuery
   - Cloud Storage
   - Looker Studio
   - Compute Instance
4. Mage.AI(Modern data pipeline tool)

**Modern Data Pipeline Tool:** https://www.mage.ai/

**Contribute to this project here:** https://github.com/mage-ai/mage-ai
## Data set used:
TLC Trip Record Data
Yellow and Green taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts.

Here is the dataset I used: https://github.com/guptamounish/uber-data-engineering-mage-project/blob/main/data/uber_data.csv

## More info about Datset
1. Original datasource : https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
2.Data Dictionary: https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf
                   https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_green.pdf

## Data Model
![Data_model_Image](data_model.jpeg)

## Scripts for Project
1. **Extract** [Extract Python File](mage-files/extract.py)
2. **Load** [Load Python File](mage-files/load.py)
3. **Transform** [Transform Python File](mage-files/transform.py)

