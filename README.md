## Youtube Video Dashboard

### Video Demo: "https://www.youtube.com/watch?v=cSZhbMPCAwE"

## Description:
- Frameworks:
  - Requests
    - Performed Data Extraction through making API calls
    - JSON extracted response
  - Pandas
    - Store extracted data in dataframes
    - Minor Data Cleaning and Reformatting
  - AWS Database
    - PostgreSQL
    - Oncloud DB for storage of extracted data
  - Psycopg2
    - Wrapper for PostgreSQL for establishing connection between Jupyter to Cloud DB
    - Cursor for execution of SQL queries, to create table and for real time updates of data
  - DBeaver
    - Connection to Oncloud Database
    - Used for verifying data formats and data presence in table
  - Power BI
    - Established ODBC connection to import cloud database data to Power BI
    - Final reformatting of Data
    - Created new measures and columns to implement relative indicators like grossing rates of videos
    - Utilized tools and features for data visualization, including but not limited to, charts, tables and tooltips
    - Created visuals to display essential information, with time period slicers; Data displayed based on selected time period
  

