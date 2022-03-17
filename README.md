# pyAirports
 Python airports project for Code Louisville in spring 2022.

Data source: https://www.kaggle.com/khaiid/most-crowded-airports

This project includes data for the most crowded airports around the world. The user selects a region of interest (from a list provided) and the program auto-generates a line graph showing total number of passengers for airports in that region by year. Project includes a dictionary and a list, as well as a While loop.

Before starting, you need to download/install the following add on in VS Code and the following Python packages:
- VS Code with Jupyter Notebook add on
- Pandas
- matplotlib.pyplot
- numpy
- matplotlib.ticker
- logging
- sys

For this project, you should utilize the Juypter Notebook add on to VS Code. Clone the repo to your computer. Navigate to the folder and open airport.ipynb with VS Code. The file import uses a public CSV saved in Google Sheets, a work around for users utilizing different operating systems (not having to adjust the import statement/file path).

Packages used:
* numPy
* Pandas
* matplotlib

Features used:
* Category 1: Create a dictionary or list, populate it with several values, retrieve at least one value, and use it in your program.

     * Used dictionary to assign "Region" to each observation
     * Used list to create values to check in while loop
      
* Category 2: Read data from an external file, such as text, JSON, CSV, etc, and use that data in your application.

     * Imported CSV file (permanent, public location on Google Sheets/Drive)
      
* Category 3: Visualize data in a graph, chart, or other visual representation of data.

     * Line graph showing total number of passengers for selected region by year.

* Category 4:

     * Implement a log that records errors, invalid inputs, or other important events and writes them to a text file.

* Additional features:
  
     * Use a Jupyter notebook to document your data analysis.
     * Use pandas, matplotlib, and/or numpy to perform a data analysis project. Ingest 2 or more pieces of data, analyze that data in some manner, and display a new result to a graph, chart, or other display.
