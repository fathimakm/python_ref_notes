# python_ref_notes
python_notes_for_reference


A __module__ is a Python file that contains additional functions, variables, classes, and any kind of runnable code.

A __library__ is a collection of modules that provide code users can access in their programs.


The Python Standard Library is an extensive collection of Python code that often comes packaged with Python. It includes a variety of modules, each with pre-built code centered around a particular type of task. 

 - re module, which provides functions used for searching for patterns in log files

 - csv module, which provides functions used when working with .csv files

- glob and os modules, which provide functions used when interacting with the command line

- time and datetime modules, which provide functions used when working with timestamps

- statistics module includes functions used when calculating statistics related to numeric data. 


 __mean()__ is a function in the statistics module that takes numeric data as input and calculates its mean (or average).
 __median()__ is a function in the statistics module that takes numeric data as input and calculates its median (or middle value).


 The **import** keyword searches for a module or library in a system and adds it to the local Python environment. 

import statistics
monthly_failed_attempts = [20, 17, 178, 33, 15, 21, 19, 29, 32, 15, 25, 19]
mean_failed_attempts = statistics.mean(monthly_failed_attempts)
print("mean:", mean_failed_attempts)
median_failed_attempts = statistics.median(monthly_failed_attempts)
print("median:", median_failed_attempts)

// Beautiful Soup (bs4) for parsing HTML files and NumPy (numpy) for arrays and mathematical computations. 

To install a library, such as numpy, 
`%pip install numpy`
 import it directly into Python using the import keyword
 `import numpy`



__A style guide__ is a manual that informs the writing, formatting, and design of documents. As it relates to programming, style guides are intended to help programmers follow similar conventions.
Play video starting at ::32 and follow transcript0:32
The __PEP 8 style guide__ is a resource that provides stylistic guidelines for programmers working in Python. PEP is short for Python Enhancement Proposals. PEP 8 provides programmers with suggestions related to syntax