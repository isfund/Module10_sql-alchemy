# Module10_sql-alchemy
This project involves analyzing climate data from the Hawaiian Islands and creating a Flask API to serve the data. The analysis focuses on temperature and precipitation data, utilizing Python, SQLAlchemy, and Flask to create a simple and efficient web API.

The following was done for this project:
- Climate Data Analysis: Analyze temperature and precipitation data from various weather stations in Hawaii.
- Flask API: Provide easy access to the climate data through a RESTful API.

The Project Contains Files:
app.py: Flask application that handles the API routes.
hawaii.sqlite: Database containing climate data.
climate_starter.ipynb: Jupyter Notebook used for the initial data analysis.

For the app.py the API Endpoints are as follows:
1. Homepage (/)
2. Precipitation Data (/api/v1.0/precipitation)
3. Stations (/api/v1.0/stations)
4. Temperature Observations (/api/v1.0/tobs)
5. Temperature Statistics (/api/v1.0/<start> and /api/v1.0/<start>/<end>)


