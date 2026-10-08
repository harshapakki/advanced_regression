# Advanced regression: house price prediction

Regularised regression on house sale data, built for the machine learning and AI
post graduate diploma at IIIT Bangalore.

## The problem

A property investor entering a new market wants to buy below market value and
resell higher. That needs two answers: which variables actually move the sale
price, and how much of the price those variables explain.

## What is here

- `Assignment3.ipynb` is the full analysis: cleaning, feature handling, model
  fitting and the written conclusions
- `Q&A-converted.pdf` is the submitted write up

## Approach

Ridge and lasso regression with a search for the optimal lambda, so the model
stays stable on a wide feature set instead of overfitting the training sample.
Lasso also does the variable selection, which answers the investor's first
question directly.

## Running it

```
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
jupyter notebook Assignment3.ipynb
```
