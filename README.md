# A/B Test: E-commerce data

This project aims to analyze data from an E-commerce dataset with a statistical approach. Through the project it is analyzed if a company should implement a new website
page, keep the old page, or perhaps run the experiment longer to make their decision.

## Datasets

There are 2 datasets that will be analyzed: ab_data and countries. The databases are in csv format, have more than 290k rows and were downloaded through Udacity's website. 

## Packages

The project requires the installation of the following packages: `Pandas`, `Numpy`, `Matplotlib`, `SciPy`, `Random` and the magic function `%Matplotlib inline`.

## Structure

The project has a brief introduction and has a statistical analysis with probability, A/B Test and Logistic Regression. By the end of the project, there is a conclusion about the analysis.

* Introduction
* Part I - Probability
* Part II - A/B Test
* Part III - Regression
* Conclusion

## Conclusion

After preforming A/B tests, regression approaches (through the logistic regression model and the interaction of countries and landing pages in the regression model), it is possible to conclude that the features analyzed in this project doesn't provide significant impact when predicting if an individual converts or not to the new webpage.

The results shows that the company should keep the old webpage (the analysis fails to reject the null hypothesis) but other parameters should be analyzed, like the timestamp data, so the company could verify insights if it should implement or not the new webpage.

## References

- [Markdown cells](https://jupyter-notebook.readthedocs.io/)
- Severall references of Ztest Function caught from [Stackoverflow](https://stackoverflow.com/)
