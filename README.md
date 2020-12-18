# Fundamentals of Data Analysis

# Tasks 2020

#### Lecturer: Ian McLoughlin

#### Student: Damien Connolly
#### Student Number: G00340321
***************************************************************************************************************************************************************
<br/>



#### OVERVIEW OF TASKS
*****************************************************************************************************************************************************************

1. Counts - Write a Python function called counts that takes a list as input and returns a dictionary of unique items in the list as keys and the number of times each item appears as values. So, the input ['A', 'A', 'B', 'C', 'A'] should have output {'A': 3, 'B': 1, 'C': 1} .

2. Dicerolls - Write a Python function called dicerolls that simulates rolling dice. Your function should take two parameters: the number of dice k and the number of times to roll the dice n. The function should simulate randomly rolling k dice n times, keeping track of each total face value. It should then return a dictionary with the number of times each possible total face value occurred. So, calling the function as diceroll(k=2, n=1000) should return a dictionary like: {2:19,3:50,4:82,5:112,6:135,7:174,8:133,9:114,10:75,11:70,12:36}

3. Numpy.random.binomial - Write some python code that simulates flipping a coin 100 times. Then run this code 1,000 times, keeping track of the number of heads in each of the 1,000 simulations. Select an appropriate plot to depict the resulting list of 1,000 numbers, showing that it roughly follows a bell-shaped curve. You should explain your work in a Markdown cell above the code.

4. Simpson's Paradox - Simpson’s paradox is a well-known statistical paradox where a trend evident in a number of groups reverses when the groups are combined into one big data set. Use numpy to create four data sets, each with an x array and a corresponding y array, to demonstrate Simpson’s paradox.

<br/>

#### PACKAGES USED IN THIS PROJECT
************************************************************************************************************************************************************************
The following packages were used to run analysis for this project.

Anaconda https://www.anaconda.com/distribution/ - is the easiest way to perfrom Python data science machine learning on Linux, Windows and Mac OS.

Python https://www.python.org/downloads/ - An interpreted, high-level and general-purpose programming language

iPython https://ipython.org/ - it an interactive command-line terminal for Python.

Jupyter Notebook https://jupyter.org/ - is an open-source web application that allows the creation and sharing of documents that contains live code, equations, visualisations and narriative text

Numpy http://www.numpy.org/ - is the fundamental package for scientific computing within Python.

Pandas https://pandas.pydata.org/ - Python library used for for data manipulation and analysis

Matplotlib.pylab https://matplotlib.org/ - Python library used for creating static, animated, and interactive visualizations

Seaborn https://seaborn.pydata.org/ - Python data visualization library based on matplotlib

<br/>

#### INSTRUCTIONS
*************************************************************************************************************************************************************
Once you install Anaconda, the packages listed above will also be installed.

First go to https://github.com/dconn20/Fund.D.A.Tasks and download the repository

Navigate to the correct folder on your terminal that you saved the repository in

You can now run the notebook by typing jupyter notebook in the command prompt

A window or tab should open in your default web browser. If this does not happen the command prompt output will provide a URL which you can copy and paste into your web browser to access jupyter notebook

Double click the jupyter notebook file and the notebook should open in a new tab

When opened select run all cells

Please note that certain cells must be run before others, such as importing the libraries 
