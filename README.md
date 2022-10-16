# Crowdfunding-ETL

# Overview of the analysis:
We are using the extract, transform, and load (ETL) process to create data pipelines. 

The Crowdfunding analysis follows this steps: 
  (1) Extract Data. 
  (2) Transform and Clean Data. 
  (3) Create an ERD and Table Schema, and Load Data.
  (4) SQL Analysis
  
# Background:
Independent Funding wants to perform both an ETL process on this dataset and a data analysis by using SQL queries.
In this Challenge, we’ll use Python, Pandas, and Jupyter notebooks to do the extract and transform phases. Specifically, extract and transform the backers’ contact information from a CSV file to create a DataFrame that will be exported as a CSV file. Then do the load phase. The dataset to create an ERD and a table schema for creating a new table in the crowdfunding_db database. And, upload the CSV file that contains the backers’ information into this table. Finally, perform a data analysis on the crowdfunding_db database by using SQL queries.

# Extract Data/ Transform and Clean Data
Using your knowledge of Python, Pandas, and the extract and transform phases of ETL, we’ll extract the raw data and add it to a DataFrame for the transform phase.
In transform, the data via formatting, splitting, converting data types, and restructuring to create a DataFrame that can be loaded into a postgreSQL database as a CSV file.
![Screen Shot 2022-10-16 at 12 49 31 PM](https://user-images.githubusercontent.com/110873947/196052655-94e42ce8-5dd3-4d41-9e6e-dee737b2e298.png)

Backer data transformed into required format which is shown in below image.![Screen Shot 2022-10-16 at 12 51 25 PM](https://user-images.githubusercontent.com/110873947/196052720-e4684fa1-92fc-4224-a989-00187d388c4a.png)


# Create an ERD and Table Schema, and Load Data
Using the ERD that we created in this module, we’ll create a backers table that has primary and foreign keys based on the summary information about the backers.csv dataset. Then export the updated database schema as a PostgreSQL file and use it to create the backers table in the crowdfunding_db database. Finally, use pgAdmin to upload the backers.csv file into the backers table.
![crowdfunding_db_relationships](https://user-images.githubusercontent.com/110873947/196053081-f51105d7-4dfb-416d-b42c-9d2e8e7a4dd8.png)

![SQL data query bonus challenge 1](https://user-images.githubusercontent.com/110873947/196053220-59b630d7-805d-4538-bc85-c38243092930.png)

![SQL data query bonus challenge 2](https://user-images.githubusercontent.com/110873947/196053221-7779992c-9b8c-4a14-9b93-beafb55ceeca.png)

![SQL data query bonus challenge 3](https://user-images.githubusercontent.com/110873947/196053222-d91dddf9-8dc9-440e-b5e4-1c45765f6ea5.png)

![SQL data query bonus challenge 4](https://user-images.githubusercontent.com/110873947/196053223-6c8bcfed-6be0-4199-96fe-37200c890dd5.png)



