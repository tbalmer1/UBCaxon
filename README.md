# UBCaxon
NEURON model of UBC axon conduction

This model began with a model of a mossy fiber axon from 2019_HCN Hallerman https://elifesciences.org/articles/42766 which can be found here: https://github.com/HallermannLab/2019_HCN or https://github.com/elifesciences-publications/2019_HCN

The purpose of this modeling is to explore axon conduction velocity, double humped spikes in boutons, and other features observed in UBC bouton recordings.

Each version of this model has .hoc files that ADD ion channels that will be used, BUILD the morphology, and DEFINE the densities of the added channels to the morphology.  run.hoc runs all of those files and the opens a session file that creates the graphs and windows.

Download the folder, run mkrndll in the folder to create the .c and .o files, then open 'run.hoc'
