
The entry point for this pipeline is the file 'main-pipeline.ipynb' which orchestrates all of the children notebooks

I chose notebooks for ease of use and set this up with an anaconda environment to install pyspark on my local machine.

For the database, I chose SQLite to avoid having to create a database with a server for loading the data with. 

In order to get the data to fulfil the requirements, I made some modifications to the csv files, these changes were:

1. Made wind_speed null on the first row of data_group_2
2. Made wind_direction null on the 2nd row of data_group_2
3. Made power_output null on 3rd row of data_group_3
4. Modified the value of 3 rows in data_group_1 to have readings higher/lower than our defined inputs