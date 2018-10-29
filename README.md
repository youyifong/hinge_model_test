# hingemodeltest

This project contains the script and R code for the Monte Carlo studies and real data analysis in He, Huang, Fouda, Permar (2018). The hypothesis testing methods themselves are implemented in the R package chngpt (https://cran.r-project.org/web/packages/chngpt) version 2018.10-17 or later. The R package kyotil (https://cran.r-project.org/web/packages/kyotil) is also needed for MC studies.


---------------------------------------------------
Monte Carlo studies for speed comparison in Sec 4.1:

The superscript file can be executed in a slurm distributed computing environment. It calls the runscript file through the configuration files under the config directory. The runscript file then runs hinge_test_MC.R with proper arguments. The Monte Carlo results are saved in files organized into subdirectories. 

To analyze Monte Carlo results, source hinge_test_MC_analyses.R from an R prompt, which creates summary tables.

---------------------------------------------------
The mtct_hinge_test.R file replicates the data analysis example.


References:

He, Huang, Fouda, Permar (2018) A non-nested hypothesis testing problem for threshold regression models. Under review.
