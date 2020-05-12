# MKL
## Implementation of Multiple Kernel Learning (MKL) Model for Relating Structural (SC) and Functional Connectivity (FC) in the Brain based on resting state fMRI BOLD signals and diffusion weighted imaging and DTI

The code implemented here is based our new methods article based spectral graph theory (heat diffusion kernel) and application in fMRI at (www.nature.com/articles/s41598-018-21456-0). Please cite this article if you are using this code for your work. 

Surampudi, S.G., Naik, S., Surampudi, R.B. et al. Multiple Kernel Learning Model for Relating Structural and Functional Connectivity in the Brain. Sci Rep 8, 3265 (2018). https://doi.org/10.1038/s41598-018-21456-0

In order to use the MKL model on your data set, you need to ensure few things:

- The dataset should have both the structural and functional connectivity matrices. They are denoted by sCall and fCall respectively. Their size is [<#rois>, <#rois>, <#subjects>].
- to run the model use **run_MKL.m** file.
