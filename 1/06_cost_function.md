# Week 1 - Cost Function

A cost function will let us figure out how to fit the best possible straight line to data in linear regression.

Given some training set

```
Size in feet (x) | Price ($) in 1000s (y)
----------------------------------------
            2104 |                 460
            1416 |                 232
            1534 |                 315
             852 |                 178

```

And our hypothesis

*h<sub>ϴ</sub>* =  *ϴ*<sub>0</sub> + ϴ<sub>1</sub>*x*

We must chose values the parameters ϴ<sub>0</sub> and ϴ<sub>1</sub>. This is exactly the equation *y* = *mx* + *b* with the parameters swapped and subbed for thetas.

The idea is that we choose ϴ<sub>0</sub> and ϴ<sub>1</sub> so that *h<sub>ϴ</sub>*(*x*) is close to *y* for our training examples (*x*, *y*). Formally, in linear regression we want to solve a minimization problem *minimize ϴ*<sub>0</sub>*ϴ*<sub>1</sub>. That is, we want the difference between *h<sub>ϴ</sub>*(*x*) and *y* to be small. We might try the squared difference equation to evaluate this. Since I can't do LaTeX, this image will have to suffice:

![Squared error function](http://i.imgur.com/VlVHIdq.png "Squared error function")

This means "find me the values of *ϴ<sub>0</sub>* and *ϴ<sub>1</sub>* so that the 1/2*m* times the sum of squared errors between my predictions on the training set minus the actual values on the training set is minimized."

To rewrite this more cleanly, by convention we define a cost function:

*J*(*ϴ*<sub>0</sub>*ϴ*<sub>1</sub>) = 1/2*m*Σ(*h<sub>ϴ</sub>*(*x*<sup>(*i*)</sup>)-*y*<sup>(*i*)</sup>)<sup>2</sup>

So what we want to do is minimize *ϴ*<sub>0</sub>, *ϴ*<sub>1</sub> for *J*(*ϴ*<sub>0</sub>, *ϴ*</sub>1</sub>)




