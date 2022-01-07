# ap_phot
Script for aperture photmetry with realistic errors based on empty apertures measurements
It requires R installed, as it internally runs a couple of secondary scripts in this language

In order to use the script, you just need to run phot.py introducing (see the script for an example):

- Path to .txt file that contains the following columns: ra, dec, aperture radius, inner annulus radius, outer annulus radius for background substraction
- Path to .txt file where each row is an input image path
- Name of output photometry file
- Pixel scale (arcsec/pix)
- Note that there are two methods for background substraction
