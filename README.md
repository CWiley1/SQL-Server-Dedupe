# SQL-Server-Dedupe
Quick and easy deduping in SQL server based on criteria of desired primary key columns.


## Instructions
1. If your table does not contain a unique id for each row, then execute the first SQL command which will add an additional field to your table. (Make sure to use your table's name is the place of TABLENAME and additionally change the columnname ID if you desire somthing different)
2. Once you do have a unique id for each row then execute the second SQL command filling in your tablename for keyword TABLENAME and your desired unique columns for column1, column2, column3 etc.
