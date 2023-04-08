---
jupytext:
  cell_metadata_filter: -all
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.11.5
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---


# Summary of machine learning fundamentals


## Machine Learning Landscape : Discriminative Models

Most of supervised machine learning can be looked at using the following framework: 
You have a set of training points $(x_i, y_i)$, and you want to find a function f that "fits the data well", 
that is, $yi \approx f(x_i)$ for most $i$.

You will start by doing the following:

- Define the form of $f$. For instance, we can define $f = wx + b$, for some constants $w$ and $b$. 
Note that this is a set of functions — for different values of $w$ and $b$, 
you will get different functions $f$, and you want to find an $f$
from this set that does the “best”.
- As you might have noticed, we have been talking about this notion of “best”, 
which is ill-defined up to this point. So, we need to make this more concrete. 
The goal here, as stated above, is to have $y_i \approx f(x_i)$
for most $i$.

The above two steps essentially define the **function class** and the **loss function** respectively.

Depending on how you choose your function class and the loss function, 
you get different supervised learning models or even unsupervised learning models:

- Linear function class with squared-error loss function — Linear regression
- Linear function class with logistic loss function — Logistic regression
- Linear function class with hinge loss — SVM
- Function class containing a network of neurons with cross-entropy loss — Neural networks

and so on.

## How to conceive a "new" Machine Learning algorithm : Discriminative Models


- [How about perpendicular distance instead of vertical distance for Linear Regression?](https://math.stackexchange.com/questions/1530298/variant-of-linear-regression-using-perpendicular-distance-instead-of-vertical)

- [How about Logistic Regression with Kernel Trick?](https://www.quora.com/How-can-one-use-kernels-utilizing-the-kernel-trick-in-logistic-regression)

- [How about a Neural Network with Kernel Trick]

- [How about a Neural Network not by Layers but inter-connected]

- [How about horizontal or vertical lines - then we have Decision Tree]

- [How about counting numbers - then we have KNN]

- [How about counting numbers with Kernel trick](https://stats.stackexchange.com/questions/44166/kernelised-k-nearest-neighbour)



## Machine Learning Landscape : Generative Models 


## LDA 


## Unsupervised learning

## Semi-supervised learning


<div hidden>
    https://www.baeldung.com/cs/svm-vs-neural-network
</div>