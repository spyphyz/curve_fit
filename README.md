# curve_fit
These workbook uses Scipy (1.0.0) to find a power law curve fit for a astrophysical-source spectral continuum
(in this case an optical spectrum downloaded from SDSS)
and Astropy (3.0.2) to fit a Gaussian to the emission lines. 

Currently you need to manually isolate a portion of the spectrum with the emission line you are interested in, 
and subtract the baseline continuum power-law curve fit. 

Also trying out sherpa, powerlaw, and pyspeckit.

It would be nice to figure out how to automate these processes - ?scikit-learn
