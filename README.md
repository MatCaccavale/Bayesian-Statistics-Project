# Bayesian-Statistics-Project
The goal of the project is using models and techniques from Bayesian Statistics to compare different groups of patients in terms of the mean function and the time warping parameters obtained from their curves, which needed to be aligned in time (refer to the Report.pdf file for all the deatils). 

## Content of the repository
Import_data.R : the script contains functions to read data and to prepare the dataset for the analysis.
Auxiliary_Functions.R : the script contains several functions which performs repetitive tasks (e.g. computation of quantities for the full conditional, evaluation of some functions). In particular you can find the functions implementing the different versions of the Metropolis-Hastings step.
Metropolis_within_Gibbs.R : in this script the MCMC simulation is performed using a Metropolis-within-Gibbs algorithm. Different choice for the model of the coefficients phi of the warping function can be made inside the script. Depending on the choice of the model for the coefficients, different Metropolis Hasting algorithms are implemented to update their values.
Results_and_Plots.R : in this script the results produced in 3) are analyzed and the plots of the significant quantities are made.
