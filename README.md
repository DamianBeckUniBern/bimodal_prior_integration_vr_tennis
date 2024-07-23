### bimodal_prior_integration_vr_tennis
##structure of the git repository. The repository contains all necessary data to do all analysis.
1. code folder with: 
- python script to clean the raw data and prepare the data for the statistical analysis.
- r-skript for each day (and merged day 2 and 3) to calculate the statistics.
2. data: here are the prepared datasets for each day for the statistical analysis.
3. plots: here are all plots saved for each participant in each condition on each day, and the summary plots of the aggregated plots of all participants.
4. raw_data: There are two folders with raw data for each day. For each day a folder for the participant numbers 0-15 and 16-31, but only data from 24 participants are collected (numbers: 1-12,15-19,22-28), the other participant numbers were only in reserve.
5. Simulation: For conceptual predictions, we have calculated a Bayesian simulation according to Bayesian decision theory. Steps of Bayesian modelling (see http://www.cns.nyu.edu/malab/bayesianbook.html).
6. The r scripts can be executed in the r-Studio project "statistical_analysis".