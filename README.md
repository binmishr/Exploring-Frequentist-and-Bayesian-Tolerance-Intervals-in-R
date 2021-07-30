# Exploring-Frequentist-and-Bayesian-Tolerance-Intervals-in-R

Tolerance intervals are used to specify coverage of a population of data. In the frequentist framework, the width of the interval is dependent on the desired coverage proportion and the specified confidence level. They are widely used in the medical device industry because they can be compared directly vs. product specifications, allowing the engineer to make a judgment about what percentage of the parts would meet the spec taking into account sampling uncertainty.

In this post I wanted to dive a bit deeper into the frequentist version of tolerance intervals to verify that they provide the correct coverage in a straight-forward use case. Then I will explore a Bayesian version which uses the posterior draws from a fitted model to calculate the Bayesian analogue of a tolerance interval.

The codeset with images is attached in the .pdf file in this repository.
