# ETL-Project
<hr>

### Contributors: Ian Housman, Abdullah Almasri, Hisham Elhassan

### Data Sets 

#### (1)  Car Sales CSV - https://www.kaggle.com/gagandeep16/car-sales

#### (2)  Data CSV - https://data.world/amercader/car-fuel-emissions-2000-2013

## Background 
<hr>

Our project was to extract two sources of data into a Python kernel, transform the sets of data to fit our liking, and load them into an online database. For our sets of data, we chose a CSV file from kaggle.com that showed the sales of many different car manufacturers, and another CSV file from data.world that looked at fuel emissions from each car manufacturer and model.

## Objective 
<hr>

Our objective for this project is to extract the data, transform the data, and load it into a database. In this case, the database is SQL. 

### Extraction 
<hr>

We downloaded the datasets as CSV files and loaded them into the jupyter notebook using the read_csv function in pandas. 

### Transform 
<hr> 

We transformed the dataframe by grouping the dataset by the manufacturer and the average. 

### Load 
<hr> 

Finally, we created table queries in sql, connect our sql to our jupyter notebook, and loaded our dataframes into the database. 


