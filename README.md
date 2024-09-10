SQLALCHEMY CHALLENGE
(1) Project Overview and Purpose:
This exercise will produce a climate analysis that aids in trip planning. Precipitation and location data will be used to evaluate potential vacation destinations, and an app will facilitate quick research of weather conditions
(2) Dataset Description and preprocessing: 
The following starter files were provided for this challenge:
•	The "hawaii.sqlite" file contains precipitation data and station location information.
•	The "hawaii_measurements.csv" file includes station identification, dates, and recorded precipitation (prcp) and temperature (tobs) values.
•	The "hawaii_stations.csv" file provides station identification, names, coordinates (latitude and longitude), and elevation data.
The tables from the 'hawaii.sqlite' file were mapped using the SQLAlchemy Object Relational Mapper. No cleaning was necessary for missing or incomplete data.
(3) Data Visualization Techniques:
The climate analysis produced two bar charts and a summary statistics table. The app displayed query responses in HTML format, viewable in a browser
a.	A precipitation analysis plot was created, showing the cumulative rainfall (in inches) over a 12-month period from August 2016 to August 2017, with the date on the x-axis.
    ![image](<Output/plot of the precipitation analysis.png>)

b.	A histogram displaying the frequency of temperature observations at Station USC00519281 over a 12-month period was created
    ![image](<Output/histogram of the frequency of observations at Station USC00519281 for the temperatures measured over a twelve (12) month period.png>)
    
c.	The user can utilize the 'app.py' file to query and generate responses for specific inquiries.

(4) Citation:
•	ChatGpt was used to determine fix datetime formatting error when 'Saving the query results as a Pandas DataFrame
•	Xpert Learning Assistant 




