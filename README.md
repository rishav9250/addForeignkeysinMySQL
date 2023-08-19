# addForeignkeysinMySQL
add foreign keys in MySQL.





The foreign key is used to link one or more tables together. It matches the primary key field of another table to link the two tables. It allows us to create a parent-child relationship with the tables. We can add a foreign key to a table in two ways:

Using the CREATE TABLE Statement
Using the ALTER TABLE Statement
Following is the syntax to define a foreign key using CREATE TABLE OR ALTER TABLE statement:

[CONSTRAINT constraint_name]    
    FOREIGN KEY [foreign_key_name] (col_name, ...)    
    REFERENCES parent_tbl_name (col_name,...)   
