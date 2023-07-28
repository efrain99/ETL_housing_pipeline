# Housing ETL pipeline

## Purpose:
Cleans the raw housing data into the database format. Once the pipeline runs on a csv file
the resultant files are placed in the staging directory to be loaded into the database. The
csv files are extracted from https://www.realtor.com/research/data/.

## The Data
The data are broken down into various geographical levels, the highest level being national down
to zip code. Each row is distinguished using two metrics, date (month and year) and location.