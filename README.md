# Python Data Science Handbook

This repository contains the entire [Python Data Science Handbook](http://shop.oreilly.com/product/0636920034919.do), in the form of (free!) Jupyter notebooks.

You can read the book in its entirety online at https://jakevdp.github.io/PythonDataScienceHandbook/

![cover image](notebooks/figures/PDSH-cover.png)

The book was written and tested with Python 3.5, though older Python versions (including Python 2.7) should work in nearly all cases.

The book introduces the core libraries essential for working with data in Python: particularly [IPython](http://ipython.org), [NumPy](http://numpy.org), [Pandas](http://pandas.pydata.org), [Matplotlib](http://matplotlib.org), [Scikit-Learn](http://scikit-learn.org), and related packages.
Familiarity with Python as a language is assumed; if you need a quick introduction to the language itself, see the free companion project,
[A Whirlwind Tour of Python](https://github.com/jakevdp/WhirlwindTourOfPython): it's a fast-paced introduction to the Python language aimed at researchers and scientists.

See [Index.ipynb](http://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/Index.ipynb) for an index of the notebooks available to accompany the text.

## Contents

- [0.0 Preface](https://github.com/YonseiMVP/PythonDataScienceHandbook/blob/master/notebooks/00.00-Preface.ipynb)

### 1. IPython a.k.a Jupyter Notebook

- [1.0 Beyond Normal Python](https://github.com/YonseiMVP/PythonDataScienceHandbook/blob/master/notebooks/01.00-IPython-Beyond-Normal-Python.ipynb)
- [1.1 Help and Documentation](https://github.com/YonseiMVP/PythonDataScienceHandbook/blob/master/notebooks/01.01-Help-And-Documentation.ipynb)
- [1.2 Shell Keyboard Shortcuts](https://github.com/YonseiMVP/PythonDataScienceHandbook/blob/master/notebooks/01.02-Shell-Keyboard-Shortcuts.ipynb)
- [1.3 Magic Commands](https://github.com/YonseiMVP/PythonDataScienceHandbook/blob/master/notebooks/01.03-Magic-Commands.ipynb)
- [1.4 In-Out History](https://github.com/YonseiMVP/PythonDataScienceHandbook/blob/master/notebooks/01.04-Input-Output-History.ipynb)
- [1.5 Shell Commands](https://github.com/YonseiMVP/PythonDataScienceHandbook/blob/master/notebooks/01.05-IPython-And-Shell-Commands.ipynb)
- [1.6 Errors and Debugging](https://github.com/YonseiMVP/PythonDataScienceHandbook/blob/master/notebooks/01.06-Errors-and-Debugging.ipynb)
- [1.7 Timing and Profiling](https://github.com/YonseiMVP/PythonDataScienceHandbook/blob/master/notebooks/01.07-Timing-and-Profiling.ipynb)

### 2. Numpy


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
