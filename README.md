# Independent TESS Transit Analysis of TOI-1470

## PROJECT OVERVIEW

I am analyzing archival NASA TESS observations of the TOI-1470 planetary system using Python and the Lightkurve astronomy package.

My goal is to independently recover and characterize transit signals in the TESS data, then compare my results with published measurements of the multi-planetary system.

I am using this project to develop practical experience with astronomical data analysis and scientific Python, while gaining a better understanding of how transiting exoplanets can be detected and characterized from photometric observations.

## Research Questions

1. Can periodic transit-like signals be independently recovered from the available TESS observations of TOI-1470?
2. Can the orbital periods and basic transit properties be recovered without using published planetary parameters as inputs to the analysis?
3. How closely do the independently recovered parameters agree with published results?
4. Can TESS Target Pixel Files provide additional information about the source of the detected signals and potential contamination from nearby stars?

## Methods

I will use a combination of:

- NASA TESS observations obtained through MAST
- TESS SPOC light-curve products
- Target Pixel Files (TPFs)
- Python
- Lightkurve
- Astropy
- NumPy
- Matplotlib
- Box Least Squares (BLS) period searches

The analysis will include data selection, light-curve inspection and cleaning, detrending, transit searches, phase-folding, transit characterization, and pixel-level examination.

## Data

TESS observations will be obtained from the Mikulski Archive for Space Telescopes (MAST).

Raw  TESS data files will not be stored in this repository. The specific TESS sectors and data products used in the analysis will be documented so that the analysis can be reproduced.

## Project Status

Target selected and MAST data analysis in progress