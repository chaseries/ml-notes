# Week 1 - Model Representation

## Reminders about what kinds of problems exist:

* ***Supervised*** a machine learning paradigm wherein we provide known data sets ("training sets") and try to "learn" solutions from them.

We start with a training set and we feed that to our learning algorithm. The job of the algorithm is to output a function *h* (the "hypothesis") that takes as input the size of a house that maps from some *x* to some *y*.

How do we represent *h*? We write it is *h<sub>ϴ</sub>* = *ϴ*<sub>0</sub> + *ϴ*<sub>1</sub>*x*. What thismeans is that we predict that we predict that *y* is going to be some linear function over the vector *x*. This in particular is *univariate linear regression*.

* ***Unsupervised*** a machine learning paradigm wherein we provide data to an algorithm and let the algorithm find patters in it without outside help.

## Notation used in this course

* ***m*** the number of training examples
* ***x*** s input variables ("features")
* ***y*** s output variables ("target" variables)
* ***(x, y)*** a single training example
* ***(x<sup>(i)</sup>, y<sup>(i)</sup>)*** the *i*th training example
