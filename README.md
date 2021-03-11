# etl_project
ETL Project

Team 4: Stephen Domke, Jess Hunter, Abhusan Karki & Shawntell Manning

<h2>Datasets used and sources:</h2>

<ol><li><h3>COVID-19 Dataset</h3>
Number of Confirmed, Death and Recovered cases every day across the globe:<br>
  <a href="https://www.kaggle.com/imdevskp/corona-virus-report">https://www.kaggle.com</a><br>
  <ul><li>country_wise_latest.csv - Latest country level no. of cases</li>
    <li>day_wise.csv - Day wise no. of cases (Doesn't have country level data)</li>
    <li>usa_county_wise.csv - Day to day county level no. of cases</li></ul></li>

<li><h3>European Centre for Disease Prevention and Control</h3>
Historical data (to 14 December 2020) on the daily number of new reported COVID-19 cases and deaths worldwide:<br>
<a href="https://www.ecdc.europa.eu/en/publications-data/download-todays-data-geographic-distribution-covid-19-cases-worldwide
         date_data.csv">https://www.ecdc.europa.eu</a>
  <ul><li>covid_19_clean_complete.csv</li>
    <li>daily_cumulative.csv</li>
    <li>date_data.csv</li>
    <li>full_grouped.csv</li>
    <li>worldometer_data.csv</li>
  </ul></li>

<li><h3>Our World In Data</h3>
  <h4>Our World in Data relies on data from Johns Hopkins University</h4>
Global data on confirmed COVID-19 cases<br>
  <a href="https://ourworldindata.org/covid-cases?country=IND~USA~GBR~CAN~DEU~FRA">https://ourworldindata.org</a>
  <ul><li>us-county-data.csv</li>
  <li>us-county-data.csv</li>
  <li>us-deaths-characteristics.csv</li>
  <li>us-hospital-data.csv</li>
  <li>us-states-data.csv</li>
  <li>us-worldwide-data.csv</li></ul>
</li></ol>

<h2>Types of wrangling/data cleansing:</h2>
<ol><li>Loaded all files</li>
  <li>Cleansed files: eliminated irrelevant data, renamed columns, dropped null values</li>
</ol>
