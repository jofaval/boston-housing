# Boston Housing #

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jofaval/boston-housing/blob/master/notebook.ipynb)

## Table of contents

1. [📁 Data](#-data)
1. [📓 Description](#-description)
1. [✔️ Objective](#-objective)
1. [🧱 Tech stack](#-tech-stack)
1. [💹 Algorithms](#-algorithms)
1. [📊 Visualization](#-visualization)
1. [🤓 Conclusions](#-conclusions)
1. [©️ Credits](#-credits)

## 📁 Data
[↑ Back to the table](#table-of-contents)

The data is available at Kaggle using the following link:\
[https://www.kaggle.com/c/boston-housing](https://www.kaggle.com/c/boston-housing)

And it's official link:
[http://lib.stat.cmu.edu/datasets/boston](http://lib.stat.cmu.edu/datasets/boston)

## 📓 Description
[↑ Back to the table](#table-of-contents)

This is a quick resolution into a common dataset used for algorithms benchmarking. I've done extensive notebooks, and benchmarking, notebooks where I've explained my thought process and what I did understand about the dataset, this is NOT one of them. This is a quick gaze into a dataset resolution.

Sorry if you were looking for that, but, my [California Housing Pricing](https://github.com/jofaval/california-housing-pricing) project does go into further detail and is also a housing-related dataset.

## ✔️ Objective
[↑ Back to the table](#table-of-contents)

To develop an algorithm that gets as less Minimum Squared Error on the test data as possible. A simpe (not to say easy) objective makes it easier to focus on the project.

## 🧱 Tech stack
[↑ Back to the table](#table-of-contents)

Python, that's it! R is a programming language that, as for the moment being, I have no experience with, even though it's powerful and broadly used, but I'd dare to say that no more than Python.

And one of the strongest points, if not the most, about Python, are it's libraries, so... the libraries I've used are:

- Pandas, data manipulation with an ease of use and exploration data analysis.
- Numpy, a really strong linear algebra library, used in the project for it's statistics utilities, SciPy may be an alternative, but I have no experience at all with it.
- Matplotlib and Seaborn, both fantastic libraries for data visualization, and they complement each other.
- Scikit-Learn, the library used for Machine Learning and statistics models: Linear Regression, SVR, Lasso, Ridge, etc.
- Tensorflow and Keras, the industry standard for Deep Learning, the way to go, not really, it's just that for now I don't have that many experience with PyTorch

## 💹 Algorithms
[↑ Back to the table](#table-of-contents)

I've basically used, Linear Regression, XGBoost and RandomForest, they're both powerful algorithms.

- Linear Regression with Polynomial Features is the simplest of the three, but it fits the problem. Although it does not perform as well as the other two.
- Random Forest did perform the "best", except not really, it did not get the highest score on the test data, but it's still a damn good algorithm.
- XGBoost, the winner for this round, a powerful algorithm that's been taking the price lately, and for good reason.

## 📊 Visualization
[↑ Back to the table](#table-of-contents)

There's nearly any visualization, only some correlation and distribution plots, and, the actual main dish, the regression plot, it's borrowed from [Prasad Perera's](https://www.kaggle.com/prasadperera) [notebook](https://www.kaggle.com/code/prasadperera/the-boston-housing-dataset)

## 🤓 Conclusions
[↑ Back to the table](#table-of-contents)

Supervised or unsupervised, what truly makes a good algorithm is not the algorithm itself, but good, quality data. Obviously a good algorithm will give better score, and an adequate one will outmark an incredibly good algorithm.

But quality data is what makes up most of the data science projects. In this case I had to worry not about the data, since it was all cleaned and ready to work since the start.

## ©️ Credits
[↑ Back to the table](#table-of-contents)

All of the credits for the datasets goes to Kaggle, a company owned by Google. And, mostly, to the U.S Census Service who were the ones recolecting the data itself.
And credits to [Prasad Perera](https://www.kaggle.com/prasadperera). I learned new visualization tricks that deemed very useful.