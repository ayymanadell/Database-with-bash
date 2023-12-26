**Basic DBMS with Bash Scripting**

**Overview:**

This project involves creating a Basic Database Management System (DBMS) using Bash scripting, complete with an interactive user interface. The primary functionalities include managing databases and tables, enforcing data consistency constraints, and providing a user-friendly experience.

**1. Dealing with Databases:**

- **Create Database:** Users can create multiple databases, and each database must have a unique name.

- **List Databases:** View a list of existing databases.

- **Connect to Databases:** Choose a database to connect to and perform operations within that database.

- **Drop Database:** Users can delete a selected database.

**2. Dealing with Tables and Data:**

- **Create Table:** Users can create tables where the first column serves as the primary key, ensuring no null or repeated values. Tables must have unique names within a database.
- **columns** in the same tables must have unique names

- **List Tables:** Display a list of tables within the connected database.

- **Drop Table:** Delete a specified table from the connected database.

- **Insert into Table:** Insert data into tables, with the database maintaining data types "ensure that primary key has unique and not null and the specified data type", and  "ensure the entered value in each column has the right data type to that column"

- **Select From Table:** Retrieve data from a table, users can retreive all the data, or specific columns or rows based on conditions (e.g., "WHERE AGE = 50").

- **Delete From Table:** Delete all data in a table, or delete rows by a condition (e.g., "WHERE AGE = 50"), or delete a column (set values to null), or drop a column from the table structure (entirely removing it). Primary keys and their data cannot be deleted.

- **Update Table:** Update a specific field in a table using the value of the primary key with maintaining the right data types to the new values . Primary keys themselves cannot be updated.

**To Run:**

1. Download the files to your machine.

2. Place all files in a directory.

3. Add the directory to the path using the following terminal command:
   export PATH=$PATH:<directory_path>
4. Run the 'main' script to initiate the program.

Enjoy the interactive experience! 😊
