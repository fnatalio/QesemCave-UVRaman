# QesemCave-UVRaman

The csv file “data_set_interpolated_not_processed.csv” contains the raw Raman spectra of the geological flints used to train, tune and test the machine learning models and create the model used for temperature estimation. The spectra in this file are only interpolated to specific wave numbers but not smoothed, and without base removal and intensity normalization.

- The first row is the header.
- The first column is just an index.
- The second column is the heated temperature of the geological flint.
- The third column is the site that the geological flint was taken.
- The fourth column upto the last one are the Raman intensities where the header (102.0 – 1798.0) are the wave numbers for the corresponding intensities in cm-1.
