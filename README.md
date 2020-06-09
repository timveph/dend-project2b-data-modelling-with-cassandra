# dend-project2b-data modelling with cassandra
Using fictitious data from a startup called Sparkify, create an Apache Cassandra database, build a data model (based on analyst requirements) and an ETL pipeline to feed data into the database. 

## Project steps followed

### Modelling my database
1. Design tables based on analyst requirements
2. Write Apache Cassandra CREATE KEYSPACE and SET KEYSPACE statements
3. Develop my CREATE statement (making use of IF NOT EXISTS to test if table already exists)
     - Included DROP statements to reset my project and enable me to test various scenarios
4. Load data with INSERT statements

### Building the ETL pipeline
1. Iterate through each event file to create a new CSV file using Python
2. Using CREATE and INSERT statements, load records into the appropriate tables
3. Test by running predifined queries on my database to ensure the ETL process and data model are fit for purpose


 
