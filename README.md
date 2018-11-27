# SQLPageCalculator
Simple Python project to read the number of SQL Server logical reads and convert them to Gigabytes. 

How to use it?
- in SQL Server Management Studio, run the query you want to investigate like this:

SET STATISTICS IO, TIME ON

-- query goes here

SET STATISTICS IO, TIME OFF

Copy the results from the tab "Messages" (right by the "results" tab) and paste them to a text file.

Run this app to read the file, and convert all logical reads into a size in gigabytes. 
