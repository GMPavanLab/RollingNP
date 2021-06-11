# RollingNP

This repository contains the data used in the paper "Towards chemotactic supramolecular nanoparticles: from autonomous surface motion following specific chemical gradients to multivalency-controlled disassembly".

This repository contains all the input data needed to run the simulations and get the results presented in the paper. Data are organized in 5 different folders:

 * `1-MinimlisticCGModel/`

	in this folder there are the Gromacs and PLUMED input files for reproducing the minimalistic coarse-grained model showed in the article.
        
 * `2-AAandFineCGModels/`

	contains the atomistic (`monomerAA/`) and the coarse-grain Martini "wet" (`monomerGCWet/`) input files for the Original monomer with one carboxyl group while the coarse-grain Martini dry (`monomerCGDry/`) model is reported for the Original monomer at the three different charged states. 

 * `3-UnbiasedMD/`

	include the Gromacs input files necessary to reproduce the Unbiased simulations as showed in the article.

 * `4-MetaD/`

	incorporate the Gromacs and PLUMED input files necessary to reproduce both the Infrequent CG Metadynamics simulations (`InfrequentMetaD/`) and the Multiple-walker CG Metadynamics simulations (`MultipleWalkerMetaD/`)

 * `5-InSilico/`

	in this folder are reported all the files used to run all the simulations for the exoliation experiments (`Original/`, `Type-1/`, `Type-2/`, `Type-3/`, `Type-4/`). Every subfolder contain three folders for the three different charged monomers (`Olig1-/`, `Olig2-/`, `Olig3-/`).
