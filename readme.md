# 1. Introduction

**Today, we're going to explore Washington House Price Data and will come up with a model to estimate the price of house given all the required features. We'll be doing some basic EDA followed by building multiple regression models from sckit-learn library and will evaluate their performance by comparing the predictions.**

# 2. Feature Engineering

**Now we'll add some new features to our house price data. When we actually look for a house, we keep all these features mentioned below in our mind:**

* **Age of house** - Age of house extracted by choosing 2020 as a reference year.
* **Is renovated(Categorical)** - 1 for renovated condition, 0 otherwise
* **Total Area of house**
* **Basement(Categorical)** - 1 if basement is available, 0 otherwise

# 3. Visualizing and Examining Data

**This is not a very big data and we do not have too many features. Thus, we have chance to plot most of them and reach some useful analytical results. Drawing charts and examining the data before applying a model is a very good practice because we may detect some possible outliers or decide to do normalization. This is not a must but get know the data is always good.**
