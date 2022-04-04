# Assignment5
Data 1202 Data Analysis Tools Analytics
# INTRODUCTION
The top 1000 records were extracted from the 4000 records in the youtube_dataset, and the distribution of these channels were extracted and placed in a table.

1. First, the libraries pandas and numpy were imported into Jupyter Notebook as pd and np. Furthermore, the visualization packages matplotlib and seaborn were imported as plt and sns.
2. Next, pd.read_csv was used to load the youtube_dataset as a dataframe with an encoding of “cp1252” which allows for characters such as “€” which was part of the dataset. 
3. A function was then created to plot the distribution of the top 1000 channel types. Under this function, “dataframe.iloc” was used to slice the top 1000 rows and seaborn distribution plot (sns.displot) was used to plot the values.
4. The seaborn plot style was set to ‘white grid’ and the aspect ratio for the plot was chosen to be 3.
5. The function was called by inputting the first row and last row values by using “plot_channel_dist” which returned the figure for distribution of top 1000 channel types.
6. Second, the libraries pandas and numpy were imported into Jupyter Notebook as pd and np.
7. Next, pd.read_csv was used to load the youtube_dataset as a dataframe with an encoding of “cp1252” which allows for characters such as “€” which was part of the dataset. 
8. A subset of the dataframe was created using “dataframe.iloc” to fetch the first 1000 rows of the dataset. 
9. “.to_csv” was used to export the data frame to a csv file named “Top_1000.csv” with the encoding “cp1252” to allow for special characters (€).
10. After extraction from python, the “Top_1000.csv” file was imported as a table into a mysql schema named ‘data 1202’. 6. The table was retrieved using the SELECT statement.


# CONCLUSION
The distribution of the top 1000 channel types were found using a variety of functions in Python. This was then exported as a csv file which was then imported as a database file in SQL.

