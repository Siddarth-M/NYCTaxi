# Group 23 - Analysing NYC taxi data

This project uses public data set from the NYC TLC website to look for the pick-up and drop off times, trip lengths, average trip speed, surcharges associated with the trip and the number of people taking the taxi through the day to suggest the best time to travel by taxi in NYC. This way, people can plan their trip ahead of time by checking our model which will have predictions of the best time for every day of the year.

### Dependencies ###
Install dependencies

The following packages were used:

* pandas
* numpy
* shapely
* SQLAlchemy
* descartes
* matplotlib pyplot
* pyshp
* sklearn


### Folder Organization ###
 
 - VizualisationNotebooks : contains all Jupyter Notebooks + the Final_notebook.ipynb which mirrors all the visualizations provided in the presentation
 - src : contains python source codes that we used to figure the dataset out and experiment on

### Usage ###
All the data we used can be found in the following link: https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page

We have written code to directly download the csv files as you run the code using the python standard module [urllib.request](https://docs.python.org/3/library/urllib.request.html).
Feel free to download the trip_records.csv file from the NYC TLC webpage incase there is an error in accessing the url using the urllib module and store in the proper directory to access it.


### Visualizations ###
All the vizualisations use in the presentation can be found in the Final_Viz_team23.ipynb file, and the images we generated are stored alongside in the Presentation_Visualization folder under Visualization notebooks folder. The visualization done after time of presentation are added in the heat_map folder in the same folder.
