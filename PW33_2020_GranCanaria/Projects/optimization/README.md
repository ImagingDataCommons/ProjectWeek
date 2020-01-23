Back to [Projects List](../../README.md#ProjectsList)

# Software for finding optimal weigths for extracting Spherical Harmonics components from a spherical distribution.

## Key Investigators

Hans Knutsson, Carl-Fredrik Westin

Linkoping University, Sweden  
Radiology, Brigham and Women’s Hospital, Boston, MA, US  
Harvard Medical School, Boston, MA, US

## Corresponding author:

Hans Knutsson (hans.knutsson@liu.se )

# Project Description

<!-- Add a short paragraph describing the project. -->

The goal of this project is to provide a tool for finding optimal weigths for extracting Spherical Harmonics components from a spherical distribution. The set of coordinades on the sphere can be given as input or chosen from one of a number of precomputed sets.

One good example where this approach is useful is restoring rotation invariance of diffusion MRI estimators in the presence of missing or corrupted measurements 


## Objective

<!-- Describe here WHAT you would like to achieve (what you will have as end result). -->

1. Introduce a tool for analysis of signal distributions on a sphere to the diffusion MRI community.
2. Provide tool for visualization of 3D point distributions.

## Approach and Plan

<!-- Describe here HOW you would like to achieve the objectives stated above. -->

<!-- 1. Discuss / demo the CMB platform
2. Integrate ITK into the CMB plaform
3. Integrate display of oriented image data in VTK
4. Basic thresholding -->

<!--## Progress and Next Steps-->

<!-- Update this section as you make progress, describing of what you have ACTUALLY DONE. If there are specific steps that you could not complete then you can describe them here, too. -->



## Illustrations

<!-- Add pictures and links to videos that demonstrate what has been accomplished.
![Description of picture](Example2.jpg)
![Some more images](Example2.jpg)
-->

https://www.dropbox.com/s/c3wrujj3mggao4y/Opt_SPH_fig1.jpg?dl=0

This figure shows the result of the weight optimization for the case of 120 uniformly distributed orientations with 12 missing measurements. The rows show results for spherical harmonic degrees 0, 2 and 4. Colors indicate filter weight values, blue is most positive and red is most negative. The missing measurement locations are shown in white. 

## Background 
I developed the upploaded code as tools in my research towards finding optimal sets of waveforms for analysis of microstructural tissue features using diffusion weighted MRI (dMRI). The code can be used for optimization and visualisation of a number of aspects in dMRI.

<!-- If you developed any software, include link to the source code repository. If possible, also add links to sample data, and to any relevant publications. -->#

## References

https://www.dropbox.com/s/ijnjnoeqw127zhn/ISMRM_poster_2019.pdf?dl=0

