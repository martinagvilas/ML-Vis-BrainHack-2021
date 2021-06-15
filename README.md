# Introduction to Machine Learning and Data Visualization with Python

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/martinagvilas/ML-Vis-BrainHack-2021/HEAD?urlpath=lab)

:wave:  _Welcome!_
This short interactive tutorial will show you 
how to use the [scikit-learn](https://github.com/scikit-learn/scikit-learn) 
Python package to perform basic machine learning analysis. 
It will also cover how to visualize your results with 
the [matplotlib](https://matplotlib.org/) 
and [seaborn](https://seaborn.pydata.org/) Python packages. 

This tutorial was developed to be presented at the 2021 edition of the [OHBM BrainHack](https://ohbm.github.io/hackathon2021/) :brain:

## Structure of this tutorial
- The content of this tutorial is divided into the following notebooks:

| Notebook 	| Content 	| 
|----------	|---------	|
| [01. Preliminaries](.notebooks/01-introduction_ml.ipynb) | Introduction to the tutorial and dataset| 
| [02. Core concepts](.notebooks/02-estimators.ipynb) | Estimators, regression, classification and clustering in scikit-learn| 
| [03. Pipelines](.notebooks/03-pipelines.ipynb) | Transformers, preprocessing, feature selection, feature engineering, dimensionality reduction and pipelines in scikit-learn|
| [04. Overfitting](.notebooks/04-preventing_overfitting.ipynb) | The problem of overfitting, cross-validation, regularization and hyper-parameter tuning in scikit-learn| 
| [05. Visualization](.notebooks/05-visualization.ipynb) | Basic components of a matplotlib plot and basic plots with seaborn | 

- Each notebook provides small comprehension exercises, and a final integration exercise.

## Executing the notebooks
- To run these notebooks in Binder head here: 

    [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/martinagvilas/ML-Vis-BrainHack-2021/HEAD?urlpath=lab)

- To run these notebooks locally, follow these steps (you need to have installed git and python in your computer):
```
$ git clone https://github.com/martinagvilas/ML-Vis-BrainHack-2021.git
$ cd {path_to_cloned_folder}
$ pip install -r requirements.txt
```

## Learning goals
- [ ] Learn how to load and prepare your data for machine learning analysis with scikit-learn.
- [ ] Learn how to perform regression, classification and clustering 
analysis with scikit-learn.
- [ ] Learn the concepts of 
regularization, 
cross-validation, 
hyper-parameter tuning, 
and how to implement them using scikit-learn.
- [ ] Learn how to inspect and evaluate a machine learning model.
- [ ] Learn how to plot your results with matplotlib and seaborn.

## Pre-requisites
- For this tutorial, we assume you have:
    - Basic knowledge of Machine Learning concepts. 
    For example, you know the difference between supervised/unsupervised learning, or the difference between classification, regression and clustering models.
    - Basic experience with Python
- We also assume that you have seen the video 
["A tutorial on machine learning"](https://www.youtube.com/watch?v=pOAK6ynM11E&list=PLVso6Qs8PLCiciMyxyqxCzp38G5tEhdy6&index=6) 
by [Laura Suarez](https://twitter.com/LauraESuarez24).

## Code of conduct
This event follows the [OHBM BrainHack code of conduct](https://ohbm.github.io/hackathon2021/coc/). 
Please make sure to read it before participating in our session.

## Get in touch
If you run into any problems while executing this tutorial,
please open an [issue](https://github.com/martinagvilas/ML-Vis-BrainHack-2021/issues) describing the problem.

We also welcome any enhancements, ideas or discussions
on the structure or contents covered in the notebooks.
