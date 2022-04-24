Project Data Warehouse

This project is about to read in data from S3 to staging data in redshifft and perform changes to have final table structure in place -> see sql_queries.py

create:tables.py -> needs to be run first to create the tables. File executes List of SQL commands defined in sql_queries.py

etl.py -> Nothing needs to be changed here too, as this is just to read out the data from S3 and bring it to staging form and then transform to final form.

In the graphic you can see the Redshift time required to process the S3 readin and transform to staging and final

