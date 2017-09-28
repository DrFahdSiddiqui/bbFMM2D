# bbFMM2D-Matlab
Blackbox FMM in 2D using Matlab

This is the MATLAB/Octave translation of the C++ code of bbFMM2D. Tested with Matlab R2012 and R2016.

Define the kernel in @ExampleKernel1/ExampleKernel1.m file or create your own classes.
Use this kernel class in the FMM_Main.m file to compute the corresponding potential.
This code can used for multiple kernels simultaneously without having to rebuild the tree.

The code outputs the FMM tree object and the potential, resulting from the kernel-matrix to charge-vector multiplication.

The c++ version with documentation can be found at https://github.com/sivaramambikasaran/BBFMM2D
The paper for Chebyshev interpolation based black-box fast multipole method can be found at http://mc.stanford.edu/cgi-bin/images/f/fa/Darve_bbfmm_2009.pdf
