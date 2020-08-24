# Python for Economists: a Structural Estimation Exercise

In this tutorial, we present a simple structural estimation exercise using Python and Jupyter notebook.
  * In the first part of the tutorial, we provide a general discussion of the pros and cons of using Python compared to other popular programming languages
  * In the second part of the tutorial, we dig in in the simulation/estimation exercise:
    1. We generate data from a non-stationary dynamic discrete choice model, solving the model by backward induction.
    2. Using the value and policy functions, we simulate data, which we then use to estimate the underlying structural parameters, using both a tranditional optimization routine and finite dependence (Arcidiacono and Miller, 2011). Finite dependence allows us to estimate the parameters by simply solving an OLS problem in the transformed parameter space. 
    3. We use parametric and non-parameteric bootstrapping to estimate the standard errors of the estimated structural parameters.
    
 The file main.ipynb contains the Jupyter notebook with the entire tutorial. Given that our estimation relies procedure on simulated data, this is the only file you will need in order to carry out the same analysis. 
 
 If you just want to take a look at the tutorial, please feel free to access the rendered version [here](https://mmoretto.github.io/).    

 
