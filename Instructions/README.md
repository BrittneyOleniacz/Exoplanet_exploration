# Exoplanet Exploration

![exoplanets.jpg](Images/exoplanets.jpg)

## Background

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system. Machine learning models capable of classifying candidate exoplanets from the raw data set to help process this data.

- - -

## Methods

### Preprocessing the Data
* Preprocess the dataset prior to fitting the model.
* Perform feature selection and remove unnecessary features.
* `MinMaxScaler` to scale the numerical data.
* Separate the data into training and testing data.

### Tune Model Parameters
* Use `GridSearch` to tune model parameters.
* Tune and compare at least two different classifiers.

### Reporting
* Create a README that reports a comparison of each model's performance as well as a summary about your findings and any assumptions you can make based on your model (is your model good enough to predict new exoplanets? Why or why not? What would make your model be better at predicting new exoplanets?).

- - -

## Resources
* [Exoplanet Data Source](https://www.kaggle.com/nasa/kepler-exoplanet-search-results)
* [Scikit-Learn Tutorial Part 1](https://www.youtube.com/watch?v=4PXAztQtoTg)
* [Scikit-Learn Tutorial Part 2](https://www.youtube.com/watch?v=gK43gtGh49o&t=5858s)
* [Grid Search](https://scikit-learn.org/stable/modules/grid_search.html)

- - -

## Hints and Considerations

* Start by cleaning the data, removing unnecessary columns, and scaling the data.
* Not all variables are significant be sure to remove any insignificant variables.
* Make sure your `sklearn` package is up to date.
* Try a simple model first, and then tune the model using `GridSearch`.
* When hyper-parameter tuning, some models have parameters that depend on each other, and certain combinations will not create a valid model. Be sure to read through any warning messages and check the documentation

- - -

* Create a Jupyter Notebook for each model and host the notebooks on GitHub.
* Create a file for the best model and push to GitHub
* Include a README.md file that summarizes assumptions and findings.


