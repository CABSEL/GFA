# GFA
 

**G**lycosylation **F**lux **A**nalysis (GFA) is a constraint based modelling technique to analyze the fluxes through the glycosylation network based on a pseudo steady state assumption. While the glycosylation fluxes in the network are balanced at each time point, the GFA allows the fluxes to vary with time by way of two scaling factors: (1) an enzyme-specific factor that captures the temporal changes among glycosylation reactions catalyzed by the same enzyme, and (2) the cell specific productivity factor that accounts for the dynamic changes in the protein production rate.

For a detailed description of GFA please refer to [Hutter et al., *Metabolic Engineering*, **43**, (2017), p. 9-20](http://www.sciencedirect.com/science/article/pii/S1096717617300964).

We have recast the optimization in the GFA as a fixed point iteration. Therefore, no further toolbox is required for the optimization.
This software has been tested on MATLAB R2016a

### Last Update:
03.08.2015 

### License
Redistribution and use in source and binary forms, with or without modification, are permitted provided agreeing to the *Simplified BSD Style License* (see [more](http://opensource.org/licenses/bsd-license.php)).

### Download and installation
Please refer to Installation Guide for MATLAB

### Acknowledgements
This work has been supported by the ETH Zurich Research Grant.
