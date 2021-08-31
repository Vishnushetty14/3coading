# Python Packages

## python package is a collection of modules. Modules that are related to each other are mainly put in the same package. When a module from an external package is required in a program, that package can be imported, and its modules can be put to use.
## Any Python file, whose name is the module’s name property without the .py extension, is a module.``

## Package Module Structure

![Alt text](https://data-flair.training/blogs/wp-content/uploads/sites/2/2018/02/Package-Module-Structure.png "a title")

## Simple Example of python Packages
 



![Alt text](https://www.python-course.eu/images/packages.webp "a title")





 We will demonstrate with a very simple example how to create a package with some Python modules. First of all, we need a directory. The name of this directory will be the name of the package, which we want to create. We will call our package "simple_package". This directory needs to contain a file with the name __init__.py. This file can be empty, or it can contain valid Python code.

## pandas
pandas is a Python package providing fast, flexible, and expressive data structures designed to make working with “relational” or “labeled” data both easy and intuitive. It aims to be the fundamental high-level building block for doing practical, real-world data analysis in Python.
 
## Ex:--
   ### import pandas as pd df = pd.DataFrame({'X':[78,85,96,80,86], 'Y':[84,94,89,83,86],'Z':[86,97,96,72,83]}); print(df)

## Numpy
NumPy is a library that helps us handle large and multidimensional arrays and matrices. It provides a large collection of powerful methods to do multiple operations.

It stands for ‘Numeric Python’. It is a cross-platform module and contains tools to iterate with C and C++. It can be thought of as a Python alternative to MATLAB. It is used in different applications including linear algebra, Fourier transforms, manipulating shapes, and generating random numbers.

 ### Ex;--
### import numpy as np importing the module numpy and creating a short form as np arr=np.array([1,2,3,4]) #creating a numpy array print(f"The array is {arr} and the type is {type(arr)}")


### To understand packages, you also need to know about modules. Any Python file is a module, its name being the file's base name/module's __name__ property without the .py extension. A package is a collection of Python modules, i.e., a package is a directory of Python modules containing an additional __init__.py file. The __init__.py distinguishes a package from a directory that just happens to contain a bunch of Python scripts. Packages can be nested to any depth, provided that the corresponding directories contain their own __init__.py file.




# More Complex Package

```
sound
|-- effects
|   |-- echo.py
|   |-- __init__.py
|   |-- reverse.py
|   `-- surround.py
|-- filters
|   |-- equalizer.py
|   |-- __init__.py
|   |-- karaoke.py
|   `-- vocoder.py
|-- formats
|   |-- aiffread.py
|   |-- aiffwrite.py
|   |-- auread.py
|   |-- auwrite.py
|   |-- __init__.py
|   |-- wavread.py
|   `-- wavwrite.py
`-- __init__.py    

 ```
 



