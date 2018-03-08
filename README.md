# DeltaNeT
<img style = "float: right;" src = "https://github.com/CABSEL/DeltaNeTS/blob/master/image_deltanet.png" width="200" height="200" align="right"> 

DeltaNet is a network analysis tool for predicting genetic perturbations from gene expression data. Given a compendium of gene expression data, DeltaNet generates a perturbation score for each gene in every sample. For a given sample, the magnitude of a gene perturbation scores reflects the confidence that this gene is directly perturbed (for example, by drug or chemical compounds), while the sign reflects the nature of the perturbation (positive for gene induction, negative for gene repression).

Two versions of DeltaNet are available; DeltaNet-LAR which uses least angle regression and DeltaNet-LASSO which uses LASSO regression. The subroutines in the DeltaNet package (v.1.0) have been successfully tested on MATLAB® 2014b and 2015a platforms. The subroutines in the DeltaNetR package have been successfully tested on R versions 3.2.2 and 3.2.3. Please refer to our manuscript titled “Inferring gene targets of drugs and chemical compounds from gene expression profiles” for more detailed information about DeltaNet algorithm.


### Prerequisites:
DeltaNet: MATLAB® software (version R2014b or later) and [SpaSM package](http://www2.imm.dtu.dk/projects/spasm/) (last version on 24.10.2012) and [GLMNET package](http://web.stanford.edu/~hastie/glmnet_matlab/)

DeltaNet-R:  R software (versions 3.2.2 or 3.2.3 ) and R packages: "lars" for DeltaNet-lar, "glmnet", "cvTools" and "methods" for DeltaNet-lasso, and "doParallel" and "foreach" for parallel computing.

### Last Update
DeltaNet: 17.02.2016

DeltaNet-R: 27.06.2016
### License
Redistribution and use in source and binary forms, with or without modification, are permitted provided agreeing to the *Simplified BSD Style License* (see [more](http://opensource.org/licenses/bsd-license.php)).

[License](https://github.com/CABSEL/DeltaNeTS/blob/master/LICENSE) (RTF, 2 KB)


### Download and installation
DeltaNet (MATLAB version):
Download and unzip the [DeltaNet.zip](https://github.com/CABSEL/DeltaNet/blob/master/DeltaNet.zip) file.

The information on how to install and use DeltaNet can be found in the [README for MATLAB]().

DeltaNet-R (R version):
Download and unzip the DeltaNetR.zip (ZIP, 56 KB) file.

The information on how to install and use DeltaNet-R can be found in the [README for R]().

### Acknowledgements
This work has been supported by the ETH Zurich Research Grant. We would like to thank S.M. Minhaz Ud-Dean for providing useful suggestions and for supporting the computing environment and maintenance.
