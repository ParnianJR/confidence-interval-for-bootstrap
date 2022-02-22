# confidence-interval-for-bootstrap  
We will study the accuracy of bootstrap method for confidence intervals.For doing this, we will generate a sample from 16 random numbers generated from `N(μ, 4)`,
which `μ` is the last digit of my student number.  
We will calculate a 95% confidence interval using `Percentile Bootstrap method` and ` Bootstrap t interval method`,to see which of them gives us more accurate confidence interval.
The evaluation criteria is:  

                                 [ ̄x−1.96 σ√n, ̄x+ 1.96 σ√n]
