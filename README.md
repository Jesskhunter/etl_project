# etl_project
ETL Project

Team 4: Stephen Domke, Jess Hunter, Abhusan Karki & Shawntell Manning

<h2>Extract:</h2>

<li><h3>List Data source: Our World In Data</h3>
  <h4>Our World in Data relies on data from Johns Hopkins University</h4>
Global data on confirmed COVID-19 cases<br>
  <a href="https://ourworldindata.org/covid-cases?country=IND~USA~GBR~CAN~DEU~FRA">https://ourworldindata.org</a>
  <ul><li>us-worldwide-data.csv</li></ul>
</li>

<h2>Transform:</h2>

 <li>Created three tables from file: Based on Continent, Country, and ISO code</li>
<li>Used .unique() to obtain unique values for each</li>
<li>Used .reset_index() to create index then renamed to act as IDs</li>
<li>These IDs were used as primary keys.</li>
  
<h2>Load:</h2>

<li>Loaded data into PostgreSQL</li>

