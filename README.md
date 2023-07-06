# Data-analysis-and-Statistical-modeling
 Investigated various scenarios involving uncertainties in two-dimensional data. Explore cases of general, heterogeneous, and arbitrarily covariant uncertainties, as well as situations where there are outliers in the data, unknown uncertainties, and intrinsic scatter in the linear relationship being analyzed. 
## I used the JULIA language coded in jupyter notebook.
# Introduction
The process of fitting a model to data, specifically exemplified by fitting a straight line to points in a two-dimensional plane, involves numerous considerations. Standard weighted least-squares fitting is suitable only when there is a dimension with negligible uncertainties and another dimension where uncertainties follow known Gaussian distributions. However, these conditions are rarely met in practice. This study explores scenarios with general, heterogeneous, and arbitrarily covariant uncertainties in two dimensions. 
It also addresses challenges such as 
 -outliers
 -unknown uncertainties
 -expected intrinsic scatter in the linear relationship 
 Being fitted. 
 Having a **"generative model"** for the data, even if it is approximate, is crucial. It allows for a non-arbitrary fitting process by enabling direct calculation of **parameter likelihood** or **posterior probability distribution**. 
 ### Constructing a posterior probability distribution becomes essential, especially when dealing with "nuisance parameters" that need to be marginalized.
 ## TOPICs FOR PROBLEM SOLVING:
  -The standard weighted leastsquare fit linear/non-linear to data model
  -The objective function **“goodness of fit” **
  -Pruning outliers
  - Uncertainties in the best-fit parameters
  - Non-Gaussian uncertainties
  - Goodness of fit and unknown uncertainties
  - Arbitrary two-dimensional uncertainties
## References
- Hogg, D.W., Bovy, J. and Lang, D., 2010. Data analysis recipes: Fitting a model to data. arXiv preprint arXiv:1008.4686.



