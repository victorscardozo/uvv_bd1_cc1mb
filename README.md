
# Design and Development of Databases     



- # Summary

To make this project, I implemented a database for a network of UVV stores using PostgreSQL. The database includes tables such as products, stores, inventory, customers, orders, shipments, and others. The data insertion into the database has not been performed yet, but data will be provided to fill the tables.
(The whole project was made in Linux operating system)
 

 - # Logical Design

Construction of the logical design of the Stores Database using the SQL Power Architect application in Linux.
![](https://github.com/victorscardozo/psetrascunho5/blob/main/pset/Captura%20de%20tela%202023-05-28%20174432.png?raw=true])

 - # Conversion to Code
 The transformation of these tables into SQL code was performed using the SQL Power Architect application, and the resulting code could be implemented in POSTGRESQL. You can find the code >> [Here](https://github.com/victorscardozo/uvv_bd1_cc1mb/blob/main/pset/cc1mb_202305893_postgresql.sql) <<
- # Commands
Several commands were added for the creation of the user, database, and schema. Some commands were also included to adjust the search path and switch the current connection (postgres) to the user victor using a password.

 ![](https://github.com/victorscardozo/psetrascunho5/blob/main/pset/Captura%20de%20tela%202023-05-28%20224241.png?raw=true])
 - # Opening the File 
 ![](https://github.com/victorscardozo/psetrascunho5/blob/main/pset/Captura%20de%20tela%202023-05-28%20193135.png?raw=true])
 The above command, used in the Linux terminal, opens the file containing the code (named cc1mb_202305893_postgresql.sql), using the postgres user (wich is going to be swicthed to user "victor")

### *After that, the code was tested in the terminal and ran correctly, showing all the tables, inside the correct schema, with the correct user.

