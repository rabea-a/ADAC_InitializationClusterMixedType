# ADAC_InitializationClusterMixedType
Accompanying code to Aschenbruck et al. (????) "Initialization Strategies for Clustering Mixed-Type Data with the k-Prototypes Algorithm"

The file "simstudy_trial_design" contains the parameters utilized in the data generation process. The data parameters fac_prop, symm, nC, nV, and nO (for further details, please refer to the paper's section 4), as well as fac_lev and overlap, which remained unaltered in the present study, are defined in the columns. Additionally, the number of data sets generated repeatedly, designated as N=10, is indicated.

The object "simstudy_dat" contains the data that has been generated artificially for the purposes of the simulation study. The data set is comprised of a list of elements, with each element representing one of the 120 data situations pertaining to the parameters provided in the rows of simstudy_trial_design. Each element contains a list of 10 artificial data sets. Due to its considerable size, the file is available for download from an external server.
