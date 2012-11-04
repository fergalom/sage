sage
====

PHP scripts for interface to the Sage Line 50 database via ODBC

The Sage line 50 is a (very) closed Accounting System, but it does have an ODBC interface where tables can be read (but not written).

The scripts pull data out of Sage to updte a mysql database. there are varying complexities of scripts, start off with sage1.hp to understand how it woorks.

sage1.php:
explore Sage tables via ODBC, print out the list of tables, fields, and data.

sage2.php:
Dump all tables from sage ODBC and write them to a mysql database.

funcs.inc: Library of common functions.

config.inc: Configuration file

sage_t5_cust.php:
Read the customer table from sage and update a Take5 customer table in mysql.
 

