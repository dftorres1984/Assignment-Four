# Assignment-Four
You can see my data [here](https://dftorres1984.github.io/Assignment-Four/)

#I first import the final merged file. 

#The first aggregation is suming the Total_Score column for the years from 2003 to 2020. I save the file in three formats--RDS, CSV and parquet. 

#The second aggregation I created a new column, Year_Range, where I divde the Year column into 2003-2011 (8 years) and 2012-2020 (8 years). I then sum the Polyachy and Total_Score columns and arrange. Finally, I also decide to subtract the Year_Range 2020-2012 from 2003-2011 for each to identify the change that has happened. I then merged the data sets into new dataset and saved it as RDS, CSV, and parquet. 

#3 I grouped by country and Year Range, two inputs, and different functions (Mean and Median). I saved the files as RDS, CSV, and parquet. 

#Additional 1--I grouped the data by Year and found the mean, max, min and median of each year. I saved it by the three types of data (RDS, CSV, and parquet). 

#Additional 2--I grouped the data by Country and found the mean, max, min and median for each country in the dataset. I saved it by RDS, CSV, and parquet. 
