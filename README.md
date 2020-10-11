# Statistical_Inference_Course_Project

In the first part of this project, we will investigate the exponential distribution in R and compare it with the Central Limit Theorem. The exponential distribution can be simulated in R with `rexp(n, lambda)` where `lambda` is the rate parameter. The mean of exponential distribution is `1/lambda` and the standard deviation is also `1/lambda`. We set `lambda = 0.2` for all of the simulations. We will investigate the distribution of averages of 40 exponentials by doing a thousand simulations. We illustrate via simulation and associated explanatory text the properties of the distribution of the mean of 40 exponentials.

In the second part of this project, we'll analyze the `ToothGrowth` dataset in the R `datasets` package as follows:

- Load the ToothGrowth data and perform some basic exploratory data analyses
- Provide a basic summary of the data
- Use confidence intervals and/or hypothesis tests to compare tooth growth by supp and dose
