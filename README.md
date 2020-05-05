# Udacity Data Engineer ND Project1: Data Modeling with Postgres
The ojective of the process to demonstrate how a data engineer in startup could utilize the data (say, user activity), that is being collected and build an ETL pipeline for the analytics team to utilize the transformed data for further analysis. In this project, the data that is being used is the songs data and the user activities. The data is in JSON format. As a Data Engineer it is now our job to Transform the data into a table format and load it into a database (PostgresSQL), so that the analytics team could access the data, analyse it and to give the users a better experience - for example, a better recommendation of the songs based of the types and genre of the songs a user listens to.

This project is to bring in what was learnt in the classes about the process and practices of Data Modeling with PostgreSOL. The Database schema, that is being used in this project is the star schema, which simplifies the queries and also helps to denormalize the table which inturn gives faster read performance. The star schema also allows faster aggregations. This is required if we want to imporve the perfomance and data transformation capacity of our ETL pipeline.


## Getting Started
To get started with Data Modeling with PostgresSQL, the following steps need to be followed -
* To run the code locallly, download or clone the repo
* Make sure to run the python file create_tables.py to make sure that if any previous tables created are dropped and new tables are created to work with.
* The repo contains two IPython Notebooks etl.ipynb which could be run to steps takes in the process of Data Modeling and test.ipynb which could be run to test what has be done in the etl.ipynb (This is the prototyping part)
* The Python file etl.py contains everything that has been executed in the etl.ipynb. It could be run as the step in Data Modeling ETL process

### Prerequisites
To run the project locally you need the following dependencies -
* You need to have PostgreSQL installed
* You need to have Python 3 installed
* To run the IPython notebooks you need to have either ipython or jupyternotebook installed
    - ```python
        pip install ipython
      ```  
* You need to have the python package psycopg2
    - ```python
        pip install psycopg2
       ```
