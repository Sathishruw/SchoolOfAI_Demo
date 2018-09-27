Please change the data path in all the scripts to where you land the data!
R Users
R users can use RStudio or the R console to execute the R script.

Data
The primary data used is a airlines flight data with all flights from 1987 to 2013 heading to Chicago O'Hare airport. There is also a weather dataset we use to try to generate more features to improve our predictions on weather based delays.

flights.csv
weather.csv

Python Users
Python users can use a Jupyter/IPython notebook to launch the python notebook. Otherwise you can also run from a generic python console the python script.

Data
The primary data used is a airlines flight data with all flights from 1987 to 2013 heading to Chicago O'Hare airport. There is also a weather dataset we use to try to generate more features to improve our predictions on weather based delays.

flights.csv
weather.csv

Flow Users
Flow users can launch the flow notebook in Flow. Keep in mind you will need to start h2o first.

To start H2O please go to the h2o installation directory and run:

java -jar h2o.jar
Then navigate in a browser to and load the flow notebook by clicking on Flow > Open Flow and choosing the .flow file.

Data
The primary data used is a airlines flight data with all flights from 1987 to 2013 heading to Chicago O'Hare airport. For flow this dataset has been subsetted to only flights delayed by weather and post 2003. Subsequently there's a dataset that merged the first flights dataset with weather data. This was done beforehand because the user will not be able to conduct the joins and merges from Flow.

forFlow_flights.csv https://s3.amazonaws.com/data.h2o.ai/h2o-open-tour/2016-nyc/forFlow_flights.csv
forFlow_merged_data.csv https://s3.amazonaws.com/data.h2o.ai/h2o-open-tour/2016-nyc/weather.csv
# SchoolOfAI_Demo
