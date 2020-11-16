# Tableau
U of MN Data Visualization &amp; Analytics: Tableau Homework #20 - Citi Bike Analytics

## Data Inspection & Cleaning
CSV files of raw data for the New York Citi Bike Program were extracted from https://s3.amazonaws.com/tripdata/index.html.

A Jupyter Notebook, CitiBikeData.ipynb, was created to inspect and clean the data. Using glob and 8 lines of code, multiple csv files of raw data were combined (see source in .ipynb file for reference) and saved into one file, combined_csv.csv.

A dataframe was created to determine the number of entries, number of columns, column names, data types, and identify if there were any null values. 

The following columns were renamed, trip duration, start time, stop time, bike id, user type, and customers/subscribers age range were contrained to ages 16-100.
    
Finally, the transformed data was saved as combined_bike_data.csv.


## Visualizations and Analysis
