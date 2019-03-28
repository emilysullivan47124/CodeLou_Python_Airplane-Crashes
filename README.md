# CodeLou_Python_Airplane-Crashes
An analysis of historic airplane crashes 1903 to 2009

Code Louisville Python Data Science (January - March 2019)
Emily Sullivan emilysullivan47124@gmail.com
 
# Installing the Project git clone 
This project was coded in Python 3 on Jupyter Notebook accessed through Anaconda.
The following tools were used in this project: 
* Anaconda - https://www.anaconda.com/download 
* Jupyter Notebook - http://jupyter.org/install 
* SQLite3 - https://www.tutorialspoint.com/sqlite/sqlite_installation.htm 
* Pandas - https://pandas.pydata.org/ 
* NumPy - http://www.numpy.org/ 
* Matplotlib.pyplot - https://matplotlib.org/users/installing.html
* DateTime - https://docs.python.org/3/library/datetime.html
 
# Using the Notebook 
Open your terminal cd (change directory) to the cloned folder 
Run Jupyter Notebook by typing jupyter notebook at the terminal prompt 
Open the file Airplane_Crashes_Final.ipynb 
The repo contains csv files with data for airplane crashes that occur between 1908 and 2009 
From the Cell Menu choose Run All
 
# The Data 
I used the data to answer the following questions:
* Is there a difference in the number of crashes that happen with Small Aircraft (less than 20 passengers) versus Large Aircraft (20 or more passengers)?
* If there a difference in the day of the week that Small Aircraft crash versus Large Aircraft?
* Is there a difference in the number of crashes with survivors versus without survivors based on the day of the week?

The Jupyter notebook will perform the following:
* Create a sqlite database
* Create tables to load airplane crash data
* Import the data
* Analyze the data import itself
* Analyze specific questions about airplane crashes

