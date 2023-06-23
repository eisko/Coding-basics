# Python Basics for Data Science

Below are links and resources to get started in analyzing and visualizing data in python.

## 1. Learn unix/shell commands

- [free textbook on linux](http://linuxcommand.org/lc3_learning_the_shell.php)
- [datacamp free course](https://app.datacamp.com/learn/courses/introduction-to-shell-for-data-science)
- [look-up specific shell commands](https://explainshell.com/)

**To do:**

- [ ] Navigate file system through command line
- [ ] list files in a folder via command line
- [ ] find information on command line function
- [ ] make a new directory
- [ ] change working directory
- [ ] get path to working directory



## 2. Learn Conda Environments

Getting started with Conda: https://docs.conda.io/projects/conda/en/latest/user-guide/getting-started.html

Full User guide: https://docs.conda.io/projects/conda/en/latest/user-guide/index.html

Documentation: https://docs.conda.io/en/latest/

Search for packages here: https://anaconda.org/

**To do:**
- [ ] Install miniconda
- [ ] Access conda from terminal
- [ ] create environment and activate environment
- [ ] install the following packages into that environment:
    - [ ] [pandas](https://pandas.pydata.org/docs/) - package for managing dataframes (tables of data, e.g. csv file format)
    - [ ] [scikit-learn](https://scikit-learn.org/stable/) - package for machine learning and some data processing
    - [ ] [jupyter](https://jupyter.org/) - suite of packages that has a GUI for python notebooks (.ipynb)
    - [ ] [scikit-image](https://scikit-image.org/) - suite of tools for processing image files with python
    - [ ] [numpy](https://numpy.org/) - package for doing math in python, specifically handling matrices (i.e. arrays)
    - [ ] [matplotlib](https://matplotlib.org/) - package for plotting graphs in python
    - [ ] [seaborn](https://seaborn.pydata.org/) - package built on top of matplot
    - [ ] [Apybiomart](https://apybiomart.readthedocs.io/) - package for accessing gene name information

## 3. Learn Python coding
Do you know a what a variable is? Function? Different data types (e.g. string, int, float…)? For loops? if/else statements? Lists? <br/>
- If yes, great!, Proceed to the to-do list
- Else, if no, would recommend completing an online python tutorial
    - See google drive for intro to python/coding (_very_ basic): https://drive.google.com/drive/folders/1mV_EJJIG0BUqiYSxw7GMCfC4CDbL23wz?usp=sharing <br/>
Includes links to online lectures
    - Dense but very informative, all text: https://docs.python.org/3/tutorial/ <br/>
(don’t worry about completing all of it, just work through enough until you know the above terms) 
    - Can also look on [datacamp](https://www.datacamp.com/) or [codeacademy](https://www.codecademy.com/) for free and more interactive tutorials 
- _google is your best friend!_ Look at documentation pages for packages by google searching: 'package_name documentation' (e.g. 'pandas documentation')
- matplotlib website has great [tutorials](https://matplotlib.org/stable/tutorials/index.html) for learning the basics and many [examples](https://matplotlib.org/stable/gallery/index.html) for almost any type of graph
**To do:**
- [ ] Open jupyter notebook from terminal
- [ ] create jupyter notebook
- [ ] create text and code cells
- [ ] import packages
-- note: some conventions used:
```
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```
- [ ] load csv file as dataframe (hint: use `pandas` package)
-- [Pandas Cheat Sheet](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf)
- [ ] Plot histogram of random values (hint: use `matplotlib` or `seaborn`)
-- [Matplotlib Cheat sheet](https://matplotlib.org/cheatsheets/)
-- [Seaborn cheat sheet](http://datacamp-community-prod.s3.amazonaws.com/263130e2-2c92-4348-a356-9ed9b5034247 )
- [ ] Create scatterplot of y=x
- [ ] Load `.tiff` file as numpy array (if plan to work with images)

## Extra stuff
### Bioinformatics basics
See https://readiab.org/introduction.html for a great online, free, interactive textbook on the basics of bioinformatics <br/>
Goes over alignment algorithms and some basic functions/packages that could be used to manipulate DNA sequences in python
