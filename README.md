# Y2-FOM
Facets of Mathematics course notes and relevant scripts.


## Thursday 19th September (Lecture 1/2)

Lots of complicated theory on the lectures notes, including set theory and a lot of linear algebra. Not sure if it's neccesary to make notes on it, as we are implementing more so than proving or deriving, so will wait and see.

When dicussing RSS, we talk about minimising the RSS so that our regression fit is closest to true. By this we mean that Beta Hat is closer to true Beta, where Beta Hat(s) are the coefficients of the equation of the regression line. We know that we have a minimum because we have that the (Hessian) matrix is positive, definite. 
* * This is better explained here in layman's: If the quadratic form is positive for all values of x and y, then our. stationary point must be a minimum, and we say that the (Hessian) matrix is positive, definite. If the quadratic form is negative for all values of x and y, then our stationary. point must be a maximum, and we say that the matrix is negative ... So we have a minimum which we will find in order to create our regression equation coefficients (Beta Hats).

* A large R^2 statistic that is close to 1 indicates that a large proportion of the variability in the respone is explained by the regression model. (i.e. accurate)

* A small (or close to 0) R^2 indicates that the regression does not explain much of the variability. (i.e. inaccurate)

Currently I don't follow what the "design matrix" means, although I understand it can be used to solve for Beta.

Should follow the theory again, perhaps watch a video to better understand.