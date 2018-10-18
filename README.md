# Database Decoder
Returns basic details about any Postgresql database for which you may not have any schema infomation. It asks the user for the name of the database and login details, then lists the non-internal table names, along with their column names, data types, and internal lengths. Each table also shows the total number of rows, and has a sampling of 5 rows of data.
