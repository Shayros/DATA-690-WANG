# Assignment 1: Reflection of the first class and Chapter 1 & 2 notes

**Author**: Shaimar R. González Morales
**Date**: 1/31/2021

**Reference**: McKinney, Wes. Python for Data Analysis: Data Wrangling with Pandas, NumPy, and I Pytho.2nd edition. O’Reilly Media, Inc. 2018.

## Reflection of DATA 690 first class 

I have used Jupyter notebooks, PyCharm, Spyder, Google Colab and Binder to write Python code. I am not good at it as I am just starting but for me Jupyer Notebook was the most user-friendly environment. I liked some aspect of Binder because it is not run locally but if internet is bad or if you don’t write the code fast enough the kernel can become frozen (I am not sure if that changed) and you could lose the code. 

I am interested in using deepnote and see how they manage this. After class and without saving the notebook, I noticed that deepnote saved the notebook for me, which provide an advantage over Binder. I am also looking forward to learning how to run code in the shell because I never tried to do that with Python and I think it can be a very valuable.

The class provided a good review on how to write good code and how to structure the code in a readable format not only for you both also for others, something that I often forgot when writing code.

I wonder if we will cover those interactive plots in class. 


## Chapter 1 Notes

### Interesting highlights

-Python originated in 1991. 

-It is slower than C++ and Java.

-It has a global interpreter lock which prevent multiple instructions to run at the same time.

### Python libraries

*Numpy*

Help make computations with array

*Pandas*

It helps analyzed data in table format (dataframe). It is useful for cleaning the data

*Matplotlib*

Library use to generate plots. 

*IPython and Jupyter*

IPython environment seems to be better to access the shell. The Jupyter notebook can use IPython as a kernel. You can create HTML and md files with just code.

*Scipy*

Is a package use for scientific computing from linear algebra, integration, matrices, stats, etc.

*Scikit-learn*

Is a package mainly used for machine learning, allowing to make classifications, regressions, clustering, dimensionality reduction, etc.

*Statsmodels*

It is a statistic analysis package that allows to do regression models, analysis of variance, time series analysis, non-parametric test and visualization of these methods.

*Integrated Development Environment (IDE)*

-If I understand correctly is the place you choose to run your Python code. This can be Jupyter Notebook, Spyder, PyCharm, etc., 

-It seems that there a lot of internet groups that focus just in Python and you can use it to get clarification of an analysis.

## Chapter 2 Notes


-Python runs by running one line of code at the time before moving to the next one.

-print() <- give you the output of the code or variable you are requesting

-python <-run the code in the file located in working directory (the file has to be .py)

-% run <-run code in a file that was called in your environment

-% run -I <- access to variables

-Jupyter notebooks is helpful when need multiple code lines to achieve the expected results. –

-Jupyter notebooks serves as a local environment meaning that the codes are running the local computer data?

-ipynb. Is the format for the Jupyter notebooks and can be edited by other users (I guess they meant in GitHub)

-Python Shell have tab completion which basically allows you to press the Tab key in your computer for you to choose/complete the function you want to use (ex. a <Tab>). Typing period (a.<Tab>) helps to complete methods.

-The Tab key can also help you find a file path.

-(?) serves to prove information about the object

-(Ctrl-C) pause cause Python to stop the run

-For copy and pasting in the Python shell you can use %paste or %cpaste (allows you to control how much is paste)

** IPython keyboard shortcuts**

![alt text](image.jpg)
 
**Magic commands**
-% commands are called magic commands

**Common magic commands** 

![alt text](image.jpg)

 
Indentation in Python is made with the use of tabs and spaces and the (:) usually indicates the beginning of the indentation.

The author recommends 4 spaces as the default

(;) are used to separate information in the line of code

# <- is used to provide comments that can help understand the function of the code or why is being run. Also, it helps you avoid deleting code that maybe you don’t have to use in the moment.

Module<- a file ending in .py

**Binary operators**
![alt text](image.jpg)
 
 

**Types**
-Numbers can be either float (when the number is (.) something ex. 4.5) or * int* (4)
-Strings (str) is when it uses quotation like (“little”) or (‘little)
-Boolian (bool) represent True or False
-None represent “null” values

**Slicing**
Ex [:9]

**Formatting arguments**

-{0:.2f} you want to have it as a float with two decimals like ex. 2.00 (observation it is not indicating that the number is 2)
-{1:s} second will be a str
-{2:d} third will be an int  

-This is because Python starts to count from number 0

**Control Flow**

if statements are used to evaluate if the statement is True you can say:

‘X=5’
‘If X==5:’
‘print(“is correct”)’

It will print the statement because it is true but if is not true and you want to continue evaluating the statement to evaluate what is actually is you can use if and if the statement is not true and you want to evaluate something additionally you can use elif and else after if.

**For loops**

-These are used to go over the values of a list or integer

-You can for example say:

-for  X in table: # meaning asking if is in the data then asking if the value of X is this then do this 

-you can use (break) to stop going through the data

**While loops**

Are used to evaluate the statements and loop until it is False or you added a break

**Range**

-Is basically whatever is included between what I indicate but without including the las value
Ex.

‘list(range(8))’
[0,1,2,3,4,5,6,7] # 8 is not included and list is used to have the output in a list format
