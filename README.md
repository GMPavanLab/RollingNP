# RollingNP

This repository contains the set of data shown in the paper "Towards chemotactic supramolecular nanoparticles: from autonomous surface motion following specific chemical gradients to multivalency-controlled disassembly".

All the input data needed to run the simulations and get the results are organized in 5 different folders:

 * `1-MinimlisticCGModel/`

	in this folder there are the Gromacs and PLUMED input files for reproducing the minimalistic coarse-grained model shown in the article.
        
 * `2-AAandFineCGModels/`

	the folder contains the atomistic (`monomerAA/`) and the coarse-grained Martini "wet" (`monomerGCWet/`) input files for modelling the Original monomer with one carboxyl group. The coarse-grained Martini "dry" (`monomerCGDry/`) model is reported for the Original monomer at the three different charged states. 

 * `3-UnbiasedMD/`

	this folder includes the Gromacs input files needed to reproduce the Unbiased simulations as shown in the article.

 * `4-MetaD/`

	this folder incorporates the Gromacs and PLUMED input files necessary to reproduce both the Infrequent CG Metadynamics simulations (`InfrequentMetaD/`) and the Multiple-walker CG Metadynamics simulations (`MultipleWalkerMetaD/`)

 * `5-InSilico/`

	in this folder all the files used to run the simulations about the exoliation experiments (`Original/`, `Type-1/`, `Type-2/`, `Type-3/`, `Type-4/`) are reported. Every subfolder contains all input files for the three different charged monomers (`Olig1-/`, `Olig2-/`, `Olig3-/`).
