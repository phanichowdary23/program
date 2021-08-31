# PYTHON PACKAGES
## PYTHON 
![Alt text](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRfDdOmVD3Ktc0FKrsLPZ5i6KXjqEpp9MnOCjgAoyrHBU6bkb1OOMe2AoBrOyHNzYVvwiM&usqp=CAU "a title")
## PYTHON PACKAGES 
## 1.PANDAS :
 The pandas package introduces a novel data structure, the DataFrame, optimized for tabular, multidimensional, and heterogeneous data. Once your data has been converted to this format, the package provides intuitive and practical means to clean and manipulate it. 

 Manipulations such as groupby, join, merge, concatenate data or filling, replacing and imputing null values can be executed in a single line. The developers of the package have the primary goal of producing the world’s most powerful data analysis and manipulation tool that exists in any language — a daunting task that they may actually achieve. 

For example: To create a DataFrame:

import pandas as pd

df_1 = pd.DataFrame({‘col1’: [1,2], ‘col2’: [3,4]})
 
 And to concatenate two dataframes together:

df_2 = pd.DataFrame({‘col3’: [5,6], ‘col4’: [7,8]})
df = pd.concat([df_1,df_2], axis = 1)

## 2.PIP :
 pip is the standard way of installing and managing packages in Python. Pip comes standard with every Python distribution, allowing you to accomplish installs, uninstalls, updates, etc from the command line. For example, to install a specific package with pip from PyPI, run:

pip install “SomePackage”
 

Or for a specific package version:

For example: pip install “SomePackage == 1.0”
 

pip allows for installation from multiple sources, and is not limited to installing packages maintained on the PyPI.

## 3.PENDULUM :
 If you have at least a little Python programming experience, you probably know that you can use the datetime module to manage dates and times within an application.

 While datetime is great for basic work along these lines, the Pendulum Python package makes it easier to do more complex coding involving dates and times. It’s more intuitive to work with, and it manages time zones automatically.

 Best of all, Pendulum is designed to be a drop-in replacement for datetime. That means you can use it with code you’ve already written based on datetime. With only a few exceptions, Pendulum will work just as well, without the need to modify the code, while providing extra features not present in plain-old datetime

example : import pendulum

now = pendulum.now("Europe/Paris")

### Changing timezone
now.in_timezone("America/Toronto")

### Default support for common datetime formats
now.to_iso8601_string()

### Shifting
now.add(days=2)

## 4.PYTHON IMAGING LIBRARY :
 If your Python application interacts with images in any way, the Python imaging library, also known as PIL or Pillow, is a Python must-have. It makes it easy to write code that opens, modifies, and saves images in a variety of formats.

 If you’re doing more advanced work with images (like image recognition, in which case OpenCV would be a good package to consider), Pillow won’t cut it on its own. But for basic image importing, manipulation, and exporting, Pillow is your go-to solution.

For example: from PIL import Image


img = Image.open(r"test.png")
img.show()

## 5.NUMPY : 
 We can do basic mathematical operations without any special Python packages. However, if you’re going to do any kind of complex math, the NumPy package will make your coding life much easier.

 NumPy provides tools to help build multi-dimensional arrays and perform calculations on the data stored in them. You can solve algebraic formulas, perform common statistical operations, and much more.

For example: to create two 2×2 complex matrices and print the sum: 

import numpy as np

a = np.array([[1+2i, 5+1j], [3, 4]])
b = np.array([[5, 8+6i], [7, 8+4j]])
print(a+b)

## 6.PYWIN32 : 
 For Windows Python programming in particular, Pywin32 is a must-have package. It provides access to many of the native Windows API functions, allowing you to do things like interact with the Windows registry, use the Windows clipboard, and much more.

 Pywin32 won’t do you much good if you’re building a cross-platform Python app, but Windows developers might find that they like it so much that they use it instead of native Windows tooling.

## 7.PyQt : 
 The preceding sentence notwithstanding, PyQT, another Python package for building GUIs, is also a strong contender. It provides bindings to (you guessed it) the Qt toolkit, which is also cross-platform. It’s intended for heavier-duty GUI programming than Tkinter. That means that PyQT may be overkill if you’re building an app that has a pretty simple interface — say, just a window with some buttons and text fields — but it is a good tool if you want to build a complex, multi-dimensional GUI.


## SOME USEFUL MODULES IN PYTHON  :  https://wiki.python.org/moin/UsefulModules

