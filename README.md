## SQL and No SQL Database

### Skills:
SQL (Programming Language) using MySQL (RDBMS) and No-SQL (Programming Language) using MongoDB (NoSQL DBMS)

### Task:

### Part 1
Develop an appropriate relational database for a business data and performing queries to obtain some insights of the business-related analysis. The report should include the following:

#### 1. Select data
- Find any business data from the internet. Examine the data to ensure could possibly create queries to obtain some statistical metric from the data (i.e. the mean, median, average value). Size of data must be more that 10,000 rows (each row considered 1 record), may use more than 1 data set and may combine more than 1 source of data. State the source of data and data description. Data must be in csv format.

#### 2. Create a scenario for the data
- Create a possible scenario or background that can reflect the data obtain in (1). For example, if the data is on inventory, gives some background of the company/enterprise which include the business they are doing, the organisation structure of the company and etc. Explain what sort of data use in the business (i.e.  customer data like name, address etc; sales data, item sale, item in stock, supplier data etc).

#### 3. Identify some insight/metrics that can represent the performance of the business, for example:-
-	Average sale of item in certain month, year
- Which year have the highest sale
- Department/Item that have maximum sale
- Supplier performance
- The slow-moving item

#### 4. Identify possible relations
- Based on the scenario given in (2) identify entities (relation) and the relationship between relation. Identify the primary and foreign keys. The minimum number of relations in the database is five.	 

#### 5. SQL queries and index
- Perform queries to obtain the metric or data identified in (2). Include queries and the output from the queries in the report. The queries must involve multiple tables and use join, group statements and subqueries. Include index in certain data to improve the performance of the query.

### Part 2
The aim of this task is to develop a No-SQL document-based database using MongoDB Compass that allows to perform queries and indexing. Based on the SQL database that has been developed in SQL project, re-design tables in form of document and collection. Document design may be in the form of embedded or reference design (the reference form is using the object_id) in order to represent some relation in the tables (i.e. one-to many). The minimum number of collections in database is two. This is to allow perform of $lookup query. Report should have the following:

#### 1. How the table is being convert into document and why does it need to be appeared as in the single documents (embedded form) of reference documents?

#### 2. Perform similar queries that has been made in SQL. The queries must include aggregate queries, lookup query, index query. Save the queries and include them in the report. Export output (or partial of output) of query in csv, excel or json file.

#### 3. Having these two types of data model (relation and document-based), which one is more applicable to the case study. Discuss justification.

Note: 
Any modification made on the data or logic during the transformation from relation model to document model must be discussed in the report.
