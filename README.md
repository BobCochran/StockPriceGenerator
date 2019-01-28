# StockPriceGenerator

This tool populates a MongoDB database with two collections containing fake stock price data. 

Example code is provided in Python.

## Dependencies

pymongo


Usage:

python stockgen.py -f stocklist.txt -d 10

-f is a text file that contains the list of stocks 
-d is the number of days of data you want to create

The StockGen tool used to generate sample data will generate the same data and store it in two different collections: StockDocPerSecond and StockDocPerMinute. This tool shows how different schema designs for the same data can affect data and index size in MongoDB collections.

You should use a current version of MongoDB. This tool was tested with MongoDB Enterprise version 4.0.5.

