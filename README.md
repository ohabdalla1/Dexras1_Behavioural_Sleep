# Dexras1_Behavioural_Sleep

This repository is to supplement the paper: "Mapping the brain response to sleep deprivation by meta-analysis of microarray data." 

The repository contains methods for the analysis of passive infrared sensing of Dexras1 knockout and C57 wild-type mice. The original method for passive infrared sensing can be found here: Brown LA, Hasan S, Foster RG and Peirson SN. COMPASS: Continuous Open Mouse Phenotyping of Activity and Sleep Status [version 2; referees: 4 approved]. Wellcome Open Res 2017, 1:2 (doi: 10.12688/wellcomeopenres.9892.2)

Analyses were conducted in R version 4.1.2. RStudio 2021.09.1 Build 372. Jupyter Lab Version 3.5.3.

 - The 20220530.csv file contains the raw, unfiltered data.
 - The Mouse_Information.csv file contains information on the mice used in this study, as well as information on when they were placed in the cabinets for recording
 - The Dexras1_Sleep.ipynb is a Jupyter notebook which contains analyses for behaviourally defined sleep found in the article, as well as additional analyses
 - The Dexras1_Activity.ipynb is a Jupyter notebook, which analyzes the same data for behaviourally defined activity, and which are not found in the paper
 - The "Plots" folder contains all figures produced for the paper, as well as figures from additional analyses in both notebooks.
