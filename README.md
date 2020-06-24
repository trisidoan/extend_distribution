# extend_distribution
This repository illustrates how to create a new package in python which can be install with pip install.

credit: AWS Machine learning foundation in Udacity 
Steps:
We first create folder that contains new created package (here is) which name extend_distribution which have a folder containing new package and a setup.py.

We may include test.py which is for testing with 
- numbers.txt and numbers_binomial.txt are data files used as part of the unit tests

A folder contains the distributions (package), named distributions will have 
 - Generaldistribution.py: main class that other classes are inherited from.
 - Two classes: Gaussiandistribution.py, Binomialdistribution.py and 
 - __init__.py


When you're ready to test out the code, we'll want to pip install the distributions package and then run the unit tests. In the terminal, assuming we are in the Extend_distribution directory (if not type `cd Extend_distribution`), type `pip install .` into the command line. Then run the unit tests by typing `python -m unittest test`. 


Note that if you change the code in the distributions folder after pip installing the package, Python will not know about the changes. You'll need to run `pip install --upgrade .` when you make changes to the package files.
