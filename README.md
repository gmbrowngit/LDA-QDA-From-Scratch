We implement linear discriminant analysis and quadratic discriminant analysis on the MNIST digit data from scratch. These methods assume 
that the data classes are normally distributed with equal covariance (or different covariance for the quadratic case). Given the estimated
distributions, the model classifies a point my maximum posterior.

MNIST digits aren't such a bad candidate for such analysis, and indeed, the model has about 90% accuracy for handwritten digit recognition 
in cross validation.
