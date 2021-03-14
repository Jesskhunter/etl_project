# etl_project
ETL Project

Team 4: Stephen Domke, Jess Hunter, Abhusan Karki & Shawntell Manning

List Data source: Our World In Data
Our World in Data relies on data from Johns Hopkins University
Global data on confirmed COVID-19 cases
https://ourworldindata.org
us-worldwide-data.csv



Extract:
Extracted data from csv file



Transform:
Created three tables from file: Based on Continent, Country, and ISO code
Used .dropna() to remove null values for each
Used .fillna() to replace null values for 0
Used .unique() to obtain unique values for each
Used .reset_index() to create index then renamed to act as IDs
These IDs were used as primary keys.
Once we created the tables, we used pd.merge() to join the tables with the original data to include the new ids.
Excess columns were removed as they were included in the new tables.
These IDs act as foreign keys in the main data, where they act as primary keys in the index tables.


Load:
Loaded data into PostgreSQL
