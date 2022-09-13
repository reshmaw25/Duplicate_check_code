# Duplicate_check_code

This file is for checking the duplicates in the table. It reads from a view , takes into the schema names provided , reads all the redshift tables in that schema which has a primary key defined in the structure. Then it runs a query on the table list provided and checks for duplicate rows based on the primakry key. If there are duplicates , it will send in the schemaname , tablename and the counts of the duplicates into a slack channel mentioned here
