# Python Data Science Handbook

This repository contains the entire [Python Data Science Handbook](http://shop.oreilly.com/product/0636920034919.do), in the form of (free!) Jupyter notebooks.

You can read the book in its entirety online at https://jakevdp.github.io/PythonDataScienceHandbook/

![cover image](notebooks/figures/PDSH-cover.png)

The book was written and tested with Python 3.5, though older Python versions (including Python 2.7) should work in nearly all cases.

The book introduces the core libraries essential for working with data in Python: particularly [IPython](http://ipython.org), [NumPy](http://numpy.org), [Pandas](http://pandas.pydata.org), [Matplotlib](http://matplotlib.org), and related packages.

## Contents

- [0.0 Preface](https://github.com/YonseiMVP/PythonDataScienceHandbook/blob/master/notebooks/00.00-Preface.ipynb)

### 1. IPython a.k.a Jupyter Notebook

- [1.0 Beyond Normal Python](https://github.com/YonseiMVP/PythonDataScienceHandbook/blob/master/notebooks/01.00-IPython-Beyond-Normal-Python.ipynb)

### 2. Numpy

- [2.0 Numpy](https://github.com/YonseiMVP/PythonDataScienceHandbook/blob/master/notebooks/02.00-Introduction-to-NumPy.ipynb)
- [2.1 Data Types](https://github.com/YonseiMVP/PythonDataScienceHandbook/blob/master/notebooks/02.01-Understanding-Data-Types.ipynb)
- [2.2 Numpy Arrays](https://github.com/YonseiMVP/PythonDataScienceHandbook/blob/master/notebooks/02.02-The-Basics-Of-NumPy-Arrays.ipynb)
- [2.3 Universal Functions](https://github.com/YonseiMVP/PythonDataScienceHandbook/blob/master/notebooks/02.03-Computation-on-arrays-ufuncs.ipynb)
- [2.4 Aggregations](https://github.com/YonseiMVP/PythonDataScienceHandbook/blob/master/notebooks/02.04-Computation-on-arrays-aggregates.ipynb)
- [2.5 Broadcasting](https://github.com/YonseiMVP/PythonDataScienceHandbook/blob/master/notebooks/02.05-Computation-on-arrays-broadcasting.ipynb)
- [2.6 Boolean Arrays and Masks](https://github.com/YonseiMVP/PythonDataScienceHandbook/blob/master/notebooks/02.06-Boolean-Arrays-and-Masks.ipynb)
- [2.7 Indexing](https://github.com/YonseiMVP/PythonDataScienceHandbook/blob/master/notebooks/02.07-Fancy-Indexing.ipynb)
- [2.8 Sorting](https://github.com/YonseiMVP/PythonDataScienceHandbook/blob/master/notebooks/02.08-Sorting.ipynb)
- [2.9 Structured Arrays](https://github.com/YonseiMVP/PythonDataScienceHandbook/blob/master/notebooks/02.09-Structured-Data-NumPy.ipynb)

### 3. Pandas

### 4. Matplotlib

## Required Packages

The code in the book was tested with Python 3.5, though most (but not all) will also work correctly with Python 2.7 and other older Python versions.

The packages I used to run the code in the book are listed in [requirements.txt](requirements.txt) (Note that some of these exact version numbers may not be available on your platform: you may have to tweak them for your own use).
To install the requirements using [conda](http://conda.pydata.org), run the following at the command-line:

```
$ conda install --file requirements.txt
```

To create a stand-alone environment named ``PDSH`` with Python 3.5 and all the required package versions, run the following:

```
$ conda create -n PDSH python=3.5 --file requirements.txt
```

You can read more about using conda environments in the [Managing Environments](http://conda.pydata.org/docs/using/envs.html) section of the conda documentation.


## License

### Code
The code in this repository, including all code samples in the notebooks listed above, is released under the [MIT license](LICENSE-CODE). Read more at the [Open Source Initiative](https://opensource.org/licenses/MIT).

### Text
The text content of the book is released under the [CC-BY-NC-ND license](LICENSE-TEXT). Read more at [Creative Commons](https://creativecommons.org/licenses/by-nc-nd/3.0/us/legalcode).
