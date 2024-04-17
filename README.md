# Data-analytics-week-2
# RELATIONAL DATABASES 
Are pieces of software that let you make an operational system out of ERD.Relational entities correspond to database tables and entity attributes respond to table columns.
To pull data from relational database table,you perform a query.You compose queries using a programming language called structured query language(sql)
foreign keys enforces referential integrity or how consistent the data is in related tables
RELATIONAL                            VS       NON-RELATIONAL DATABASES
*structured                                  *key value database
*tables are connected to each other          *columns stores databases
*ensures data consistency                    *graph databases
*security                                    *document store and flexible,scale ability and cost effect
*easy back up and recovery

# DATA USE CASES
Have two  major categories of data processing
# ONLINE TRACTIONAL PROCESSING(OLTP)
.OLTP systems handles the transactions we encounter everyday e.g flight reservation,ordering something online or executing a store trade.
.OTLP systems balance the ability to write and read data efficiently
.OLTP databases are in 3NF 
.Can use relational database technology

# ONLINE ANALYTICAL PROCESSING(OLAP)
.OLAP system focus on the ability of organizations to analyze data
.OLAP systems have a denormalized design
.Can use relational database technology

# WHAT IS DATABASES?
DATABASE refering to relational database can capture and record data(OLTP), data has ability to be live,real-time data,data stored in tables with rows and columns,data is highly detailed 
and flexible(how data is organized)

WHAT IS DATA WAREHOUSE?
Is also a database designed for analytical processinf (OLAP).Data is refreshed from source systems-stores current and historical,data is summarized and rigid schema.

Difference between databases and datawarehouse
Databases are used for transactions,data is fresh and detailed and it works slowly for querying large amounts of data and that slows down transactional process.
Data warehouse are used for analytics and reporting,refreshed and summarized data and its very fast.
WHAT IS DATA LAKE?
Its designed to capture raw data structured,unstructured and semi-structured.Made for large amounts of data.Used for ML and AI in current state and lastly can organize and put into databases
or data warehouse.Data lake is highly recommended



