# Bike_Stores_MSSql_Project5_Inserting_Records.

This project demonstrates my ability to insert records into previously created tables on MSSql.

Below is a summary of actions executed in the project.

The INSERT INTO inserts data into three tables of the BikeStores database: production.brands, production.categories, and production.products. The INSERT INTO statement is used to insert data into each table, with each row representing a brand, category, or product. The VALUES clause is used to specify the values to be inserted into each row.

It uses the SET IDENTITY_INSERT command to allow explicit values to be inserted into the identity column of each table.  Identity columns are columns in a table that are automatically populated with a unique value for each new row inserted into the table. By default, MSSQL does not allow explicit values to be inserted into identity columns. However, in some cases, it may be necessary to insert explicit values into identity columns, such as when migrating data from one database to another.
