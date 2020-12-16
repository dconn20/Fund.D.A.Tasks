# Fundamentals of Data Analysis

# Tasks 2020

#### Lecturer: Ian McLoughlin

#### Student: Damien Connolly
#### Student Number: G00340321
***************************************************************************************************************************************************************
<br/>



#### Overview of tasks
*****************************************************************************************************************************************************************

1. Counts - Write a Python function called counts that takes a list as input and returns a dictionary of unique items in the list as keys and the number of times each item appears as values. So, the input ['A', 'A', 'B', 'C', 'A'] should have output {'A': 3, 'B': 1, 'C': 1} .

2. Dicerolls - Write a Python function called dicerolls that simulates rolling dice. Your function should take two parameters: the number of dice k and the number of times to roll the dice n. The function should simulate randomly rolling k dice n times, keeping track of each total face value. It should then return a dictionary with the number of times each possible total face value occurred. So, calling the function as diceroll(k=2, n=1000) should return a dictionary like: {2:19,3:50,4:82,5:112,6:135,7:174,8:133,9:114,10:75,11:70,12:36}

3. Numpy.random.binomial - Write some python code that simulates flipping a coin 100 times. Then run this code 1,000 times, keeping track of the number of heads in each of the 1,000 simulations. Select an appropriate plot to depict the resulting list of 1,000 numbers, showing that it roughly follows a bell-shaped curve. You should explain your work in a Markdown cell above the code.

4. Standard Deviation - Simpson’s paradox is a well-known statistical paradox where a trend evident in a number of groups reverses when the groups are combined into one big data set. Use numpy to create four data sets, each with an x array and a corresponding y array, to demonstrate Simpson’s paradox.

<br/>

#### Packages used in this project
************************************************************************************************************************************************************************
The following packages were used to run analysis for this project.

Python https://www.python.org/downloads/

Anaconda https://www.anaconda.com/distribution/ - is the easiest way to perfrom Python data science machine learning on Linux, Windows and Mac OS.

iPython https://ipython.org/ - it an interactive command-line terminal for Python.

Numpy http://www.numpy.org/ - is the fundamental package for scientific computing within Python.

Jupyter Notebook https://jupyter.org/ - is an open-source web application that allows the creation and sharing of documents that contains live code, equations, visualisations and narriative text

pandas https://pandas.pydata.org/

seaborn https://seaborn.pydata.org/

scipy.stats https://docs.scipy.org/doc/scipy/reference/stats.html

matplotlib.pylab https://matplotlib.org/

scikit-learn https://scikit-learn.org/stable/
