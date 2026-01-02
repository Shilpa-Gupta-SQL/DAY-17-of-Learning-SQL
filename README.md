Stored Procedure Parameters – IN, OUT, INOUT
This repository captures my learning from Day 17, where I focused on understanding how parameters work in stored procedures and how arguments are passed while calling them.

What are Parameters in Stored Procedures?
Parameters allow stored procedures to accept input values, return output values, or do both. They make stored procedures dynamic, reusable, and suitable for real-world business logic.
Instead of hardcoding values inside SQL statements, parameters help pass values at runtime.

Types of Parameters Covered 

*IN Parameters
IN parameters are used to pass values into a stored procedure. These values are read-only inside the procedure and are commonly used for filtering and searching data.

*OUT Parameters
OUT parameters are used to return values from a stored procedure. They store results such as counts, totals, or calculated values into variables.

*INOUT Parameters
INOUT parameters work as both input and output. A value is passed into the procedure, modified inside it, and then returned back to the caller.

*Passing Arguments
This repository also covers how arguments are passed while calling stored procedures using the CALL statement and how output values are captured using variables.

Why This is Important
*Helps write reusable and dynamic stored procedures
*Essential for implementing business logic in databases
*Commonly asked topic in SQL and database interviews
*Improves understanding of data flow within procedures
