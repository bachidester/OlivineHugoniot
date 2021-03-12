# OlivineHugoniot

These jupyter notebooks illustrate data fitting and error propogation for the pressure-density-temperature relation on the principal Hugoniot of olivine from Chidester et al. (submitted to GRL). 

"Example absorption correction and temperature calculation, Z Machine" uses a streaked visible spectrum output from SMASH. It corrects for the absorption of light in the olivine sample and calculates the shock temperature of olivine relative to an in situ quartz standard. 

"Olivine data analysis" uses Monte Carlo methods to fit Us-up and T-Us data on the principal olivine Hugoniot. The data used in these fits is provided in SuppDataforCalcs.csv.

"Impedance Match to Al Flyer" provides the routine for impedance matching to an Al (6061 T-06) flyer plate to determine the shock state of the sample. 

"Predictive Impedance Match Calculation" uses the Us-up fit of olivine from 'Olivine data analysis" with the known equations of state of aluminum and quartz to calculate the shock state of sample stacks for a given flyer velocity on the Z Machine.

The supplemental tables for this paper are also included.

SupplementalTable_1 - Shock data for olivine on the principal Hugoniot. Temperatures are provided for samples that included streaked visible spectroscopy (SVS) diagnostics. The Us and up values for samples with "Z Temperature Configuration" designation were calculated from the Hugoniot of olivine and the velocity of the aluminum flyer.

SupplementalTable_2 - Covariance matrix for the Us-up fit to data from Table S1.

SupplementalTable_3 - Known sample thickness compared with the theoretical sample thickness determined by integrating Us over the range of data in OMEGA EP experiments analyzed with different indices of refraction. There are two VISAR legs for each sample, so integrated thicknesses are given for both. In some experiments, the data was not collected over the entire range experiment, so integrated thicknesses could not be calculated (denoted with -).

SupplementalTable_4 - Percent reflectivity as a function of shock velocity for olivine.

SupplementalTable_5 - Temperature as a function of shock velocity for olivine.

SupplementalTable_6 - Covariance matrix for the Reflectivity-Us fit.

SupplementalTable_7 - Covariance matrix for the Temperature-Us fit.

SupplementalTable_8 - Comparison between different DFTMD configurations. Statistical uncertainties are given at the $1\sigma$ confidence interval.

