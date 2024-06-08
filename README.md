## lcls_example_notebooks
Example Jupyter notebooks for data analysis with LCLS tools

# smd
Example notebooks for the smalldata_tools setup

#smd/consumer
Example notebooks demonstrating the user of the smalldata hdf5 files

#smd/producer
Example notebooks demonstrating the concepts used in the smalldata production code

nb1_defaultDets.ipynb
This notebooks shows the few lines that will result in the standard (small) data for a given instrument to be saved without having to set anything up. It also shows how to add the timetool traces, should that be needed.

nb2_DetObject.ipynb
This notebooks demonstrates the addition of data for a larger area detector. Here, the data is reduced by executing azimuthal averaging.

nb3_DetObjectFunc_azimuthalBinning.ipynb
This notebook shows the configuration parameters for the azimuthal binning. It also shows the bins used as well as polarization and geometrical corrections.

nb4_DetObjectFunc_photonreconstruction.ipynb
This notebook shows how to look at data of a sparse detector and how to determine if photon reconstruction is a reasonable approach

nb5_DetObjectFunc_sparseSave.ipynb
This notebook shows the different options to save the reconstructed photonized data.

nb6_detector_treatment_epix100.ipynb
This notebook shows the effect of a number of different options to correct the data before applying dropletizing/photonizing.
