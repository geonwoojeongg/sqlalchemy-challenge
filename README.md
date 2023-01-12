# sqlalchemy-challenge

In this challenge, data such as date, temperature, and precipitation were analyzed using SQLAlchemy. SQLAlchemy was used to bring SQL data into Python, allowing easier access and analysis through Pandas as well as Matplotlib to graph them out. 

The retrieved data was formulated into a dataframe, with which a line graph showing the amount of precipitation was shown. An additional dataframe was made with temperature data to make a histogram to better show the frequency of each temperature.  

Using Flask, a web app with the following insightful api were made:
  1. a precipitation analysis of the last 12 months in the form of a JSON dictionary;
  2. a list of stations, where the various data were gathered;
  3. a temperature analysis of the last 12 months in the form of a jasonified list;
  4. a JSON list of the minimum temperature, the average temperature, and the maximum temperature for a specified start date; and
  5. a JSON list of the minimum temperature, the average temperature, and the maximum temperature for a specified start-end range.
