# Table of Contents

1. [Installation](#my-first-title)
2. [Usage](#my-second-title)
3. [Project Motivation](#my-second-title)
4. [File Descriptions](#my-second-title)
5. [Licensing, Authors, Acknowledgements](#my-second-title)

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install latest version of scikit-learn. After installing latest version using;

```bash
python -m pip install scikit-learn --user --upgrade pip 
```
The code should run with no issues using Python versions 3.*.

## Usage

```python
from sklearn.experimental import enable_iterative_imputer
from sklearn.impute import IterativeImputer
```

## Project Motivation
For this project, I was interestested in using Stack Overflow data from 2017 to better understand:

What are the trends on tech tools?
What is the average developer salary? 
What profession has more promising income as seniority increases? 
Salary Prediction (Linear Regression)

## File Descriptions
In this project, there are 3 different .ipynb files containing the questions I have detailed above and the salary estimation case. There are studies seeking answers to the questions in these files. In the estimation file, salary estimation was made using the features in the dataset and liear regression.


## Licensing, Authors, Acknowledgements
Thank you to StackOverFlow for providing this good dataset and Udacity for Data Science Nanodegree program based on real problem and use cases.
