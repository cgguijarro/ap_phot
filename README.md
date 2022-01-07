# ap_phot
Script for aperture photmetry with realistic errors based on empty apertures measurements

In order to use the script it is very straighforward and self-explanatory, you just need to introduce (see the script for an example):

- Path to where the individual pointings and associated primary beams are located (what you download from the FTP)
- List of IDs (string)
- List of RA (float)
- List of Dec (float)
- List of RA, Dec coordinates (string) preceded by J2000 and in hh:mm:ss dd:mm:ss
- (if flux normalization weights applied) list of fluxes (float)
