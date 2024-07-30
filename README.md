# Background

The secondhand vehicle market is a dynamic and complex environment where prices fluctuate based on numerous factors. These include the vehicle's make, model, year, mileage, body, location, and current market demand. Traditional car appraisal often relies on human intervention and judgment, which tend to be subjective and time-consuming. The goal of this study is to streamline and enhance the accuracy of pricing second-hand vehicles through machine learning models while utilizing the webscraped data. 

# Datasets to Extract

## Websites

- Philkotse: https://philkotse.com/
- Autodeals: https://www.autodeal.com.ph/
- Automart: https://automart.ph/all

**Target Website:** Automart


## Top 10 Banks

BDO Unibank
Metropolitan Bank and Trust Company (Metrobank)
Bank of the Philippine Islands (BPI) 
Land Bank of the Philippines (Landbank) 
Security Bank Corporation
China Banking Corporation (Chinabank) 
Rizal Commercial Banking Corporation (RCBC) 
PSBank
Union Bank of the Philippines (UnionBank)
EastWest

**Target Bank:** PSBank

# Deliverables
**Start:** June 18, 2024
**Deadline:** June 24, 2024 (Monday), 6PM

# Task
**Extract and convert the most recent repossessed car pdf of the corresponding bank assigned to you into a data frame and save it as a parquet file. Expected variables:**
Make, Model, Year, Transmission, Body, Price, Location, Mileage, Fuel Type
Address missing data appropriately (imputation, fill, drop, interpolate, etc.)
pdf -> dataframe -> .parquet

## Webscrape the following variables:
Make, Model, Year, Transmission, Body, Price, Location, Mileage, Fuel Type (standard column names)
