# ap_phot
Script for aperture photmetry with realistic errors based on empty apertures measurements

In order to use the script, you just need to introduce (see the script for an example):

- Path to .txt file that contains the following columns: ra, dec, aperture radius, inner annulus radius, outer annulus radius for background substraction
- Path to .txt file where each row is an input image path
- Name of output photometry file
- Pixel scale (arcsec/pix)
