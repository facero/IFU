# Integral field unit  3D visualization.

Integral field units (IFUs) combine imaging and spectroscopic capabilities to acquire spatially resolved 2-dimensional spectroscopy in a single astronomical exposure.

The dataset produced with an IFU is 3 dimensional object (RA, Dec, Energy) where a spectrum is available for each pixel of the image.
While a growing number of instrument in optical/IR are IFUs (e.g. [MUSE on VLT](https://www.eso.org/sci/facilities/develop/instruments/muse.html), [MIRI on James Webb Telescope](https://jwst-docs.stsci.edu/display/JPP/Introduction+to+IFU+Spectroscopy), CCD type detectors onboard X-ray telescope have provided have spectro-imaging capabilities ~since the ASCA satellite in the 90s.

X-ray CCDs can measure the position, energy and time of arrival of individual photons providing list of events that can be binned to produce data cubes (RA, Dec, Energy).
Due to the low photon statistics in the ASCA days or in the early phase of the last generation of telescopes XMM-Newton and Chandra with short exposures, the visualization of the data in 3D was not explored.
After 20 years in operation and deep Mega-second observations in the archive of bright extended sources such as Supernova Remnants (SNR) or clusters of galaxies, it is now possible to explore datasets in their true 3D nature.

This is an example of ~1 Ms of Chandra observation of the Cassiopeia A SNR. About 300 millions have been recorded in 1 Ms between 0.5 and 10 keV !
This extremly rich dataset provides unprecedented details about the spatial distribution and spectral properties of individual heavy elements producing during the supernova.

Below is a volume rendering of the 3D CasA data cube (RA, Dec, Energy) obtained with the Chandra X-ray satellite.
Three different viewing angles of the same cube are shown below (face-on, side, and edge-on).
The colors (blue, yellow, and red shades) indicates a higher density i.e. brightness of X-ray photons.
