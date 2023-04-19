# exploratorty-data-analysis

This code defines a class named 'dataproc', which contains some methods for processing traffic data. The class has three methods:

read_csv_format(): This method reads a CSV file from the given path and converts the 'datetime' column to datetime format. It returns the resulting dataframe.

pick_random(): This method selects a random number of detectors (specified by the 'n' variable in the class's init method) from the given CSV file and returns the resulting dataframe.

split_data(): This method takes a dataframe and splits it into two dataframes based on two given days (specified by the 'days' variable in the class's init method). It filters the data based on hour between 6am and 8pm and returns two dataframes.

The code also creates an instance of the 'dataproc' class with a path to a CSV file as an argument. It then calls the 'pick_random' method to select a random number of detectors and stores the resulting dataframe in the variable 'df'. It then calls the 'visualize' method to plot a histogram of the 'occupancy' column and a line graph of 'datetime' against 'occupancy'. Finally, it calls the 'split_data' method to split the 'df' dataframe into two dataframes based on the 'days' variable and stores the resulting dataframes in 'df1' and 'df2'.
