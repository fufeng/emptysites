# Computer Code

> custom computer code that allows readers to repeat the results.

## About

There is one code file: ES.ipynb.

The notations in the code are consistent with those in the manuscript.

The order of the code is aligned with that of the manuscript (yet first the appendix and then the main text).

## Instructions

The code is organized into an ipython notebook. 

The software, module, and hardware list is given below.

* Software

> Python 3.11.8 and above

* Module

name | version | build | channel 
------------ | ------------- | ------------- | -------------
numpy | 1.26.4  | py311h91b6869_0 | 
pandas | 2.1.4  | py311hdb55bb0_0 | 
networkx | 3.1  | py311hecd8cb5_0 | 
sympy | 1.12 | py311hecd8cb5_0 | 
matplotlib | 3.8.0 | py311hecd8cb5_0 |
seaborn | 0.12.2 | py311hecd8cb5_0 | 
multiprocess | 0.70.16  | pypi_0 | 
mpl_toolkits 
warnings 

> If we have matplotlib installed, we would be able to import mpl_toolkits directly.

* OS

> Mac OS X, Windows, or Linux


We use Anaconda GUI to run our code (which includes all the packages required except multiprocess). Otherwise, we may run `pip install` with the name and version for every candidate item.


### Get Started

The figures are saved in the folder below.
```python
'./figures/'
```

The data are saved in the folder below.
```python
'./data/'
```

We can change the corresponding 
```python
_Figure_PATH_
```
and
```python
_Data_PATH_
```
if needed.

### How to Obtain the Expressions and Figures

More detailed explanations are given in the comments and markdown notes.
