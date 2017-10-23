# GFA version 1.1

The MATLAB subroutines in GFA (v.1.1) have been successfully tested on MATLAB® 2016a. Please refer to the [GFA manuscript](http://www.sciencedirect.com/science/article/pii/S1096717617300964) for more detailed information about the algorithm. 
Any questions regarding GFA usage can be addressed to rudi.gunawan@chem.ethz.ch.

### Installation instruction:
Unzip the package GFA_1.1.zip to a preferred folder.
Set the current working directory to GFA in MATLAB.
The GFA package includes the following:

#### model.mat
Model definitions for the network given in the GFA manuscript.

#### t.mat
Vector containing the measurement times.

#### vmeas_PrcA.mat
Secretion fluxes measurements of process A.

#### vmeas_PrcB.mat
Secretion fluxes measurements of process B.

#### GFA_v1_1.m
Runs GFA for either process A or B as described in the [GFA manuscript](http://www.sciencedirect.com/science/article/pii/S1096717617300964). 

#### GFA_main.m
Calls the GFA fixed point optimization and evaluates the GFA outputs.

#### GFA_fixedpoint.m
Solves the GFA based on a fixed point iteration.

#### GFA_plots.m
Generates plots of all GFA results.
