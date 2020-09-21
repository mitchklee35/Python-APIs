# Python-APIs - Data Analysis and Visualization Course
# API to Python. ETL and Gmaps
# Function
The purpose of this exercise was to analyze the weather of each city and see how the weather changes as you get closer to the equator, as well as finding the best vacation spot with that data. First, I connected to openweathermap.org API and pulled all the cities locations and data into a data frame. I exported this data into a CSV file for later use and created scatter plots to see the relationship of weather and hemispheres. After finishing that analysis, I created a new file Jupyter Notebook to analyze possible vacation spots based on weather. Crossing this with a maps search of hotels or “lodging” I was able to create a list of the top hotels and overlay it onto a map. These hotels all met my weather criteria with certain conditions great for vacation. I generated a csv of all the locations. 
# Organization
The CSV file is within the output_data along with the images of what I was able to plot and chart. The map is generated on the Jupyter notebook. 
# How to Run
Open the jupyter notebook and run the functions starting with weather. Make sure your API key is working in “api_keys.py”. The file should create a CSV and you will be able to then run the VacationPy file. 
# Result
The result, showed correlations latitude and temperature which is obvious, but also slight negative correlations of windspeed. As well I was able to generate a list of great vacation spots that aren’t too hot or cold, and have low wind speeds 
