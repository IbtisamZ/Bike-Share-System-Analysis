# Bike Share System Analysis


Over the past decade, bicycle-sharing systems have been growing in number and popularity in cities across the world. Bicycle-sharing systems allow users to rent bicycles on a very short-term basis for a price. 

In this project, I have used a dataset provided by Motivate (A bike share system provider for many major cities in the United States) to uncover bike share usage patterns. The main goal is to compare the system usage in three large cities: Chicago, New York City and Washington DC.

<h3>The Datasets</h3>
Randomly selected data for the first six months of 2017 are provided for all three cities. All three of the data files contain the same core six (6) columns:

<li>Start Time (e.g., 2017-01-01 00:07:57)</li>
<li>End Time (e.g., 2017-01-01 00:20:53)</li>
<li>Trip Duration (in seconds - e.g., 776)</li>
<li>Start Station (e.g., Broadway & Barry Ave)</li>
<li>End Station (e.g., Sedgwick St & North Ave)</li>
<li>User Type (Subscriber or Customer)</li>

<h5>The Chicago and New York City files also have the following two columns:</h5>

<li>Gender</li>
<li>Birth Year</li>

Data for the first 10 rides in the new_york_city.csv file

<h3>Statistics Computed</h3>
You will learn about bike share use in Chicago, New York City, and Washington by computing a variety of descriptive statistics. In this project, code is written to provide the following information:

<h5>#1 Popular times of travel (i.e., occurs most often in the start time)</h5>
<li>Most common month</li>
<li>Most common day of week</li>
<li>Most common hour of day</li>
<h5>#2 Popular stations and trip</h5>
<li>Most common start station</li>
<li>Most common end station</li>
<li>Most common trip from start to end (i.e., most frequent combination of start station and end station)</li>
<h5>#3 Trip duration</h5>
<li>Total travel time</li>
<li>Average travel time</li>
<h5>#4 User info</h5>
counts of each user type</li>
<li>Counts of each gender (only available for NYC and Chicago)</li>
<li>Earliest, most recent, most common year of birth (only available for NYC and Chicago)</li>
