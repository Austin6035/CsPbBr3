# CsPbBr3
This is input files for training a complete DP of CsPbBr3 using DP-GEN and subsequent NEMD calculations of thermal conductivity.
## init
This folder contains the input files that build the initial dataset of the four structures. This part is completed using the init part of DP-GEN, and the corresponding param.json and structure files are under the four small folders.
## run
This folder contains the input files that explore and continuously complete the dataset. This part is completed using the run part of DP-GEN, under the folder is the corresponding param.json and INCAR for calculating the energy and force of the label structure.
## NEMD
The NEMD folder contains the input file for calculating the thermal conductivity of CsPbBr3 with different cell expansion lengths.The expansion of 10,15,20,25 and 40 in the x direction was carried out.
