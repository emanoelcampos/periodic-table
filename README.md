# Periodic Table

*Learning Documentation*

This project is a part of the "Build a Periodic Table Database" course from the Relational Database certification provided by [freeCodeCamp](https://www.freecodecamp.org/learn/relational-database/). The main goal of this project was to learn and understand the fundamentals of relational databases, SQL, and bash scripting.

## Database Creation

The first step of the project was to create a PostgreSQL database named `periodic_table.sql`. This database consists of tables that store information about each element of the periodic table. The information includes atomic number, symbol, name, type, and more. This step was crucial in understanding how to structure and create a relational database.

## Database Diagram

![periodic-table-diagram.svg](images%2Fperiodic-table-diagram.svg)

This diagram provides a visual representation of the database structure and the relationships between the tables. Analyzing this diagram helped in understanding how data is organized in a relational database and how different tables are interconnected.

## Bash Scripting

The next step was to create a bash script named `element.sh` that uses the argument data as input to retrieve information about an element from the database. The script can take the atomic number, symbol, or name of an element as input. If the element exists in the database, all its information is provided in the output. This step helped in learning how to interact with a database using a scripting language and how to handle different types of input data.

### element.sh

The element.sh script is structured as follows:

1. It first checks if the input argument is provided. If not, it exits the script with a message indicating that an input is required. 
2. It then checks if the input argument matches an atomic number, symbol, or name in the database. 
3. If a match is found, it retrieves all the information about the element from the database and displays it in the output. 
4. If no match is found, it displays a message indicating that the element does not exist in the database.

This script demonstrates the use of conditional statements, database queries, and error handling in bash scripting.

## Learning documentation
Through this project, I have gained a solid understanding of relational databases, SQL, and bash scripting. I have also learned the importance of documenting code and structuring data in an efficient manner.
