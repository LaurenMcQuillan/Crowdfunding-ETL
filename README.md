# Crowdfunding ETL

## Summary

The crowdfunding platform Independent Funding wants to move all their data from one large Excel file with multiple sheets into a PostgreSQL database so their analytics team will be able to create reports and query in the database. Before this could be done, the ETL (extract transform load) process had to be performed. I extracted and transformed the data from the large Excel file provided by Independent Funding and turned it into four csv files. I created a database in PostgreSQL with four tables, one table for each of the four individual csv files. After the database was created, I loaded the four csv files into their corresponding tables. Once the files were loaded, I performed SQL analyses to create a list of contacts of live campaigns to inform them of how much of the goal remains, and another list of all backers of live campaigns to inform them of how much of the goal remains of the campaigns that they have pledged to.
