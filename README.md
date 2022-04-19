
## dawid_skene_ensembling

This project is based on the implementation of the estimator for combining unreliable observations from Dawid and Skene (1979).

We want to **use the ensembling of pretrained models** to **generate reliable pseudo labels** or **managing annotation mistakes**. 

Given unreliable labels by multiple pretrain models,
determine pseudo labels (the most likely true class for each image), class marginals,
and individual error rates for each model, using Expectation Maximization.

### References:

* Dawid and Skene (1979). [Maximum Likelihood Estimation of Observer
Error-Rates Using the EM Algorithm](http://www.cs.mcgill.ca/~jeromew/comp766/samples/Output_aggregation.pdf). Journal of the Royal Statistical Society.
Series C (Applied Statistics), Vol. 28, No. 1, pp. 20-28. 

