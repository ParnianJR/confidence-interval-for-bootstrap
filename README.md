# confidence-interval-for-bootstrap  
We will study the accuracy of bootstrap method for confidence intervals.For doing this, we will generate a sample from 16 random numbers generated from `N($\mu$, 4),
which `$\mu$ is the last digit of my student number.  
We will calculate a 95% confidence interval using `Percentile Bootstrap method` and ` Bootstrap t interval method`,to see which of them gives us more accurate confidence interval.
The evaluation criteria is:  
\begin{center}
    \begin{equation} \label{eq:1}
    [\bar{x}-1.96\frac{\sigma}{\sqrt{n}},\bar{x}+1.96\frac{\sigma}{\sqrt{n}}]
    \end{equation}
\end{center}
