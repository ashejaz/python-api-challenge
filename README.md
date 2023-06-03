# overview
In this challenge, the following python libraries were utilised in Jupyter Notebook to analyse weather data: pandas, numpy, scipy, matplotlib.pyplot, citypy, requests and hvplot.

For part 1 ("WeatherPy"), a random list of cities and their coordinates was generated using citypy and their weather data was retreived using the OpenWeatherMap API. This data was combined into a pandas DataFrame and exported as a .csv file. A series of scatter plots were generated and linear regression was performed to determine relationships between combinations of weather variables.

For part 2 ("VacationPy"), hvplot.pandas was utilised to create map visualisations based on humidity for each city in the output file from part 1. The Geoapify API was used to retreive the first hotel within 10,000 metres of a selection of the cities.

# files
All files are located in the "Weather_Py" folder.

The Jupyter notebook script for part 1 is titled "WeatherPy.ipynb".

The Jupyter notebook script for part 2 is titled "VacationPy.ipynb".

All output data is contained in the folder titled "output_data".

"cities.csv" contains the output data from part 1.

The scatter plots from part 1 are listed in order - "Fig1", "Fig2" etc.

# references
All data used in this challenge has been obtained using OpenWeatherMap API and Geoapify for the edX Data Analytics Bootcamp.
