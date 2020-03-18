# Open COVID-19 Analysis
This repository contains Jupyter notebooks with examples of how to load and
analyze the data from the [open-covid-19](https://github/open-covid-19/data)
dataset. You can use Google Colab if you want to run your analysis without
having to install anything in your computer, simply go to this URL: 
https://colab.research.google.com/github/open-covid-19/analysis.

See below for a list and description of each of the notebooks in this repo.

### [Exponential Modeling](exponential_modeling.ipynb)
This notebook explores modeling the spread of COVID-19 confirmed cases as an
exponential function. While this is not a good model for long or even
medium-term predictions, it is able to fit initial outbreaks quite well. For a
more sophisticated and accurate model, see the
[logistic modeling](logistic_modeling.ipynb) notebook.

### [Logistic Modeling](logistic_modeling.ipynb)
This notebook explores modeling the spread of COVID-19 confirmed cases as a
logistic function. It compares the accuracy of two sigmoid models:
[simple logistic function](https://en.wikipedia.org/wiki/Logistic_function)
and [Gompertz function](https://en.wikipedia.org/wiki/Gompertz_function), and
finds the Gompertz function to be a fairly accurate short-term predictor of
future confirmed cases.
