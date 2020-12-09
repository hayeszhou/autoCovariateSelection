# autoCovariateSelection
**R Package to Implement Automated Covariate Selection for Two Exposure Cohorts Using High-Dimensional Propensity Score Algorithm**

*autoCovariateSelection* is an R package that contains functions to implement automated covariate selection using methods described in the high-dimensional propensity score (HDPS) algorithm put forward by Schneeweiss et.al. Covariate adjustment in real-world-observational-data (RWD) is important for estimating adjusted outcomes and this can be done by using methods such as, but not limited to, propensity score matching, propensity score weighting and regression analysis. While these methods strive to statistically adjust for confounding, the major challenge is in selecting the potential covariates that can bias the outcomes comparison estimates in observational RWD (Real-World-Data). This is where the utility of automated covariate selection comes in. 

The functions in this package help to implement the three steps of automated covariate selection. These three functions, in order of the steps required to execute automated covariate selection are:
1. get_candidate_covariates() 
2. get_recurrence_covariates()
3. get_prioritised_covariates(). 

In addition to these functions, a sample real-world-data from publicly available de-identified medical claims data is also available for running examples and also for further exploration. The original article where the algorithm is described by [Schneeweiss et.al. (2009)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3077219/)
