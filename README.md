# Applied Statistical Inference Coursework

To view just download the html and view in a browser, knit to pdf wont work and I don't plan on finding the error.

Done in completion for Dr. Karim Anaya-Izquierdo's graduate applied statistical inference coursework (if I recall correctly 40% of it). All code is in R, I wish github picked up that 
.rmd files contain R code, alas. 

We had two weeks to do this, and I recall it being two of the most painful weeks of my masters (just before christmas too, brutal). Some techniques included are: 

- Unconstrained optimisation via quasi-Newton algorithms (e.g. BFGS)
- Maximum likelihood estimation
- Symbolic differentiation in R
- Estimation of Fisher information matrix with Hessian
- Use of estimated Hessian to construct confidence intervals for true parameter
- Gamma, lognormal, normal, logistic, loglogistic, Weibull distribution analysis
  - Unconstrained optimisation to find MLE and Fisher info matrix approximation to find confidence interval
- Reparameterisation of models to expand state space to $\mathbb{R}^n$, allowing for unconstrained optimsation.
- Computation of network information criterions (see [seminal paper](https://bsi-ni.brain.riken.jp/database/file/144/147.pdf)) for model selection
- Confidence intervals for misspecified models with Kullback-Leibler estimate
- Computation of Kullback-Leibler via integration in R.
