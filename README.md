# Data Science

This project was developed for the Introductory Applied Machine Learning course at The University of Edinburgh.

It implements a series of Supervised and Unsupervised Learning tasks on the datasets with the goal of understanding the data and predicting/classifying new data points.

The datasets used are: 20 Newsgroups Dataset and Bristol Air Quality Dataset. The code is written in Python using Jupyter Notebooks.

## Prerequisites

The datasets used in Part A and B, found in the Data folder:
* **20 Newsgroups Dataset** - is a collection of approximately 20,000 news documents, partitioned evenly across 20 different newsgroups. The collection is a popular data set for experiments in text applications of machine learning techniques, such as text classification and text clustering.
* **Bristol Air Quality Dataset** - is a collection of the key traffic pollutants (e.g. NOx, NO2, NO...) from sites in Bristol that are part of the national network.

**mpctools** - a set of python tools for extending standard numpy, sklearn, pandas and matplotlib developed by Professor Michael Camilleri.

### Description of Files

* Assignment2_PartA.ipynb - Performs three main tasks on the 20 Newsgroups Dataset
  * Exploratory Analysis: summarises the key observations with regards to dimensionality, distribution, data ranges
  * Unsupervised Learning: performs and optimises **K-means Clustering** in order to learn new things about the data
  * Supervised Learning: performs **Logistic Regression Classification** on the data to predict which Newsgroup a new News Document belongs to

* Assignment2_PartB.ipynb - Performs three main tasks on the Bristol Air Quality Dataset
  * Exploratory Analysis: summarises the key observations with regards to dimensionality, distribution, data ranges and problematic features
  * Dimensionality Reduction: performs **Principle Component Analysis** in order to find the main drivers in the data 
  * Supervised Learning: predicts the NOx level for Site 17 (one of the sites) given the value at the other sites, using three different models: **Linear Regression**, **K-NN Regression** and **Decision Tree Regression**


## Built With

* [Jupyter Notebooks](https://jupyter.org/) - Web application for interactive data science and scientific computing
* [Python](https://www.python.org/) - Programming language

## Authors
**Valentine Dragan**
