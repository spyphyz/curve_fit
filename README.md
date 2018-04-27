# curve_fit
These codes use Scipy to find a power law curve fit for a astrophysical-source spectrum 
(in this case an optical spectrum downloaded from SDSS)
and Astropy to fit a Gaussian to the emission lines. 

Currently you need to manually isolate a portion of the spectrum with the emission line you are interested in, 
and subtract the baseline power-law curve fit. 

It would be nice to figure out how to automate these processes. 
