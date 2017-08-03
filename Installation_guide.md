# GFA version 1.0

The MATLAB subroutines in GFA (v.1.0) have been successfully tested on MATLAB® 2016a. Please refer to the [GFA manuscript](http://www.sciencedirect.com/science/article/pii/S1096717617300964) for more detailed information about the algorithm. 
Any questions regarding GFA usage can be addressed to rudi.gunawan@chem.ethz.ch.

### Installation instruction:
Unzip the package GFA_1.0.zip (XX MB) to a preferred folder.
Set the current working directory to GFA in MATLAB.
The GFA package includes the following:

#### Input.xlsx
An Excel® file specifying the glycosylation network as well as the glycan measurements with the following Sheets:
‘Overview’: 	 Contains the overall model specifications
‘Stoichiometry’: Contains the glycosylation network stoichiometry formatted as in the given example
‘VCD’:		 The viable cell density measurements formatted as in the given example
‘Titer’:		 The protein production measurements formatted as in the given example
‘Fractions’:	 The glycan fractions formatted as in the given example.

#### GFA_v1.m
This is the main Matlab file of GFA. It runs GFA for a given dataset of a fed-batch experiment as specified in Input.xlsx. 

#### GFA_xlsxread.m
Extracts data from an EXCEL file and saves them in a form that can be used by GFA.

#### GFA_main.m
Calls the GFA fixed point optimization and evaluates the GFA outputs.

#### GFA_fixedpoint.m
Solves the GFA based on a fixed point iteration.

#### GFA_plots.m
Generates plots of all GFA results.
