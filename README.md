# MSDS-692
US Census Data Insights - SQL, Data Exploration, and Interactive Dashboard
 
PROJECT OVERVIEW This repository contains an exploratory analysis of U.S. Census Data, focusing on unemployment rates, poverty levels, and educational attainment across different states from 2013 to 2022. The project creates a MySQL database, integrates SQL queries, Python-based data analysis (Pandas, Plotly, Dash), and visual dashboards to uncover trends in socioeconomic factors. I chose to pull at the "state" geography level and used the Python package Census to make the API call easier to manage. 

Data from the U.S. Census Bureau's 5 Year American Community Survey (ACS5) is pulled using the ACS5 API. The data retrieved includes key demographic, economic, and housing indicators for all U.S. states.

Key Variables
•	Demographics: Population, age distribution, gender breakdown

•	Income: Median household income, per capita income, poverty levels

•	Housing: Home ownership rates, median rent, housing costs

•	Employment: Labor force participation, unemployment rates

•	Education: Educational attainment levels

KEY Features
Data Collection: Extracted U.S. Census data, cleaned, and stored in a MySQL database. Alternately, you could use SQLite which is built into Python already. ( NOTE: You Must Obtain a Developer Key From https://www.census.gov/data/developers.html to make API requests )

Create Database using MySQL, SQL Queries: Developed SQL queries for analyzing unemployment, poverty, and education trends.

Data Visualization: Used Plotly and Dash to create an interactive dashboard.

Geographical Analysis: Compared states and territories to identify economic disparities.

Trend Analysis: Explored how key indicators evolved between 2020 and 2022, including post-pandemic recovery.

Technologies Used
- Python Census to make API request easier to implement
- SQL (MySQL - run through a python interface using MySQL Connector) for data storage and querying. SQLite may also be used.
- Python (Pandas, Plotly, Dash, Matplotlib ) for data analysis and visualization.
- Jupyter Notebook for interactive exploration.
- GitHub for version control and collaboration.

NEXT STEPS:
- Add more detailed geospatial visualizations.
- Integrate machine learning for predictive insights.
- Expand dataset to include additional socioeconomic factors.


