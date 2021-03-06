# installation

All packages associated with Thunder are simple Python packages that support Python 2.7 or 3.4. Most of them depend on the same set of standard scientific Python packages, including [`numpy`](https://github.com/numpy/numpy), [`scipy`](https://github.com/scipy/scipy), [`scikit-learn`](https://github.com/scikit-learn/scikit-learn) and [`scikit-image`](https://github.com/scikit-image/scikit-image). If you are just getting started with Python, we recommend installing the [Anaconda](https://www.continuum.io/downloads) distribution, which includes all of those packages. If you are coming from Matlab to Python, check out this great [cheatsheet](http://mathesaurus.sourceforge.net/matlab-numpy.html).

To install the core `thunder` package use the Python package manager `pip` by typing this in your terminal

```bash
pip install thunder-python
```

You can install any of the associated packages the same way, for example

```bash
pip install thunder-regression
pip install thunder-factorization
```

Here is the current list of packages

- [`thunder-regression`](https://github.com/thunder-project/thunder-regression) mass univariate regression algorithms
- [`thunder-factorization`](https://github.com/thunder-project/thunder-factorization) matrix factorization algorithms 
- [`thunder-registration`](https://github.com/thunder-project/thunder-registration) registration for image sequences

All components of Thunder are designed to support parallelization through the distributed computing engine [Spark](http://spark.apache.org/), but this is strictly optional; Thunder can be run in a local environment without Spark. See the section "use with spark" for information about how to run Thunder with a Spark cluster.

Thunder also works great inside the interactive [Jupyter](https://github.com/jupyter/notebook) notebook. All of the "tutorials" are written as jupyter notebooks, and you can launch any of them interactively in a web browser via [Binder](https://github.com/binder-project/binder) by clicking this [link]().