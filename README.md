# Quora Duplicate Questions

This project is my attempt to solve the Quora Duplicate Questions machine learning challenge on [Kaggle].

## Requirements
The program uses [Python2.7]. The following additional packages must be installed for it to run correctly:
* [Numpy]
* [SciPy]
* [Pandas]
* [scikit-learn]
* [matplotlib]
* [Seaborn]
* [Xgboost]

Additionally the training and testing datasets must be downloaded from Kaggle [here] and placed in the same folder as the main notebook.

[Kaggle]: <https://www.kaggle.com/c/quora-question-pairs>
[Python2.7]: <https://www.python.org/download/releases/2.7/>
[Numpy]: <http://www.numpy.org/>
[SciPy]: <https://www.scipy.org/>
[Pandas]: <http://pandas.pydata.org/>
[scikit-learn]: <http://scikit-learn.org/>
[matplotlib]: <https://matplotlib.org/>
[Seaborn]: <https://seaborn.pydata.org/>
[Xgboost]: <https://xgboost.readthedocs.io/en/latest/>
[here]: <https://www.kaggle.com/c/quora-question-pairs/data>

## Usage
If all dependencies are installed correctly the notebook should run correctly without further modification.
It is possible to change which machine learning algorithm is used with a modification to just one line of code. Just set the `algorithm_choice` parameter according to the following settings:
* 0 = Linear Regression
* 1 = SVR  (not recommended - too slow)
* 2 = Decision Tree
* 3 = Random Forest
* 4 = XGBoost

