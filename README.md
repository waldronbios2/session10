<!-- badges: start -->
[![Actions Status](https://github.com/waldronbios2/session9/workflows/build/badge.svg)](https://github.com/waldronbios2/templatesession/actions)
<!-- badges: end -->

# Session 10: Repeated Measures and Longitudinal Analysis I

## Lecture

**Learning Objectives**

1. Define mixed effects models and population average models
2. Perform model diagnostics for random effects models
3. Interpret random intercepts and random slopes
4. Define and perform population average models
5. Define assumptions on correlation structure in hierarchical models
5. Choose between hierarchical modeling strategies

**Outline**

1. Review of fecal fat dataset
2. Summary of non-hierarchical approaches
2. Mixed effects models
3. Longitudinal data and the Georgia Birthweights dataset
4. Population average models and Generalized Estimating Equations (GEE)

* Vittinghoff sections 7.2, 7.3, 7.5

## Lab

**Learning objectives**

1. Gain an intuitive understanding of ICC through simulated data
2. Simulate correlated grouped data
3. Use a heatmap and spaghetti plot to visualize correlated grouped data
4. Fit random and mixed-effects models to correlated grouped data
5. Calculate ICC from a random or mixed-effects model
6. Fit a population average model, aka marginal model, using GEE

**Exercises**

1. Simulation of correlated grouped data
2. Create a heatmap of simulated data to visualize the group effect
3. Create a spaghetti plot of the simulated data to visualize the group effect
4. Fit a random effects model with no covariates and a random intercept. Does it recover the group and residual variances you simulated?
5. Estimate ICC from the model above. Is it what you expected from the group and residual variances you simulated?
6. Estimate ICC simply by calculating the correlation between fecfat1 and fecfat2. Is it similar to the estimate above?
7. Load and do basic cleaning of the Georgia Birthweights dataset.
8. Make a boxplot and spaghetti plot for the Georgia Birthweights dataset
9. Test the null hypotheses that baseline birth weights do not vary by mother
10. Test the null hypotheses that the mother’s age (at first birth) is unrelated to baseline mean birth weight
