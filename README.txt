===========================================================================
Multi-scale Stochastic Regional Texture Segmentation v_1.0 (2015-06-23)
===========================================================================

Written by 
Rafael Sachett Medeiros <rsmedeiros@inf.ufrgs.br>
Jacob Scharcanski		<jacobs@inf.ufrgs.br>
Alexander Wong			<a28wong@uwaterloo.ca>

===========================================================================
Content:

This algorithm was introduced in the paper:
Medeiros, R. S., J. Scharcanski, and A. Wong. "Image Segmentation via Multi-scale Stochastic 
Regional Texture Appearance Models." Computer Vision and Image Understanding (2016).

===========================================================================
INSTALLATION:

The matlab codes are a standalone implementation, and no instalation is needed.
To use the mex (C/C++) implementation of the Stochastic Region Merging you must have 
the GSL and BLAS libraries installed on your computer.

GSL: https://www.gnu.org/software/gsl/
BLAS: http://www.netlib.org/blas/

===========================================================================
USAGE:

Run the 'demo.m' for segmenting the images in the "./Images/test/" folder. 
Output will be a "*_reg" file (with the boundaries marked over the image) and a "*_seg" 
file (with the segmentation map), both saved in "./Images/output/".

See the file 'demo.m' for instructions on how to configure the software.


===========================================================================
FILES:

BiSS 		- Multi-scale decomposition library
demo.m		- Test script for running this software
Images		- Some test Images
README.txt 	- This file
SRMlib		- Stochastic Region Merging Library
STRlib		- Stochastic Texture Representation library

===========================================================================
REFERENCES:

If you use this software please refer to the works:

Medeiros, R. S., J. Scharcanski, and A. Wong. "Image Segmentation via Multi-scale Stochastic 
Regional Texture Appearance Models." Computer Vision and Image Understanding (2015).

Medeiros, R.S.; Scharcanski, J.; Wong, A., "Natural scene segmentation based on a stochastic 
texture region merging approach," ICASSP 2013.


