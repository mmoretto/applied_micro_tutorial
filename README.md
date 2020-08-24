# Python for Economists: a Structural Estimation Exercise
An applied-micro tutorial on Jupiter notebook showing how to perform a structural estimation using finite dependence and bootstrapping

In this tutorial, we present a simple structural estimation exercise using Python and Jupyter notebook.
  * In the first part of the tutorial, we provide a general discussion of the pros and cons of using Python compared to other popular programming languages
  * In the second part of the tutorial, we dig in in the simulation/estimation exercise:
    1. We generate data from a non-stationary dynamic discrete choice model, solving the model by backward induction.
    2. Using the value and policy functions, we simulate data, which we then use to estimate the underlying structural parameters, using both a more tranditional optimization routine and finite dependence (Arcidiacono and Miller, 2011).
    3. We use parametric and non-parameteric bootstrapping to estimate the standard errors of the estimated structural parameters.
