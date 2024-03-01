# rift_propagation_at_thwaites
Code and Data required to reproduce the flowline damage modeling for Wild et al "Rift Propagation Signals the Last Act of the Thwaites Eastern Ice Shelf Despite Low Basal Melt Rates"

In the nbs directory you will find a notebook which walks through the components of the computation. To run it and save the data out, as is done throughout the notebook, create a 'results' and a 'figs' directory. The dependencies for the notebook are numpy, matplotlib, scipy, h5py (for reading the meltrate observations), and astropy (for performing an interpolated fill on missing velocity and strain rate observations).
