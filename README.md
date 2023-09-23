# MRIT1mapping_NOVIFAST
This package contains the following Matlab scripts/functions:

1) novifast_1D.m (Function)
    Description:
            This code is the 1D version of the original NOVIFAST implementation [1]. It is meant to estimate the T1 value from an SPGR signal. To estimate a complete T1 map from an SPGR T1-weighted image set, we do not recommend to apply novifast_1D in a voxel-wise manner. Instead, we advocate for using 'novifast_image', also included in this NOVIFAST package.
2) novifast_image.m (Function)
    Description:
            This code is a vectorized version of the original NOVIFAST implementation [1].  It works on the VFA T1-weighted image set, and provides the estimated T1 map (NLLS sense) directly. It is not a voxel-wise, for-loop, implementation of 1D NOVIFAST. This is the code we recommend using for fast VFA T1 mapping.

3) demo_novifast_image.m (script)
    Description:
            In this script, Novifast is run with real 3D SPGR MRI data. 

4) demo_novifast_SNR.m (script)
    Description:
            In this script, the behavior of NOVIFAST I as a function of SNR and number of iterations is presented. Experiments are performed with simulated SPGR MRI data.

5) Simulated and actual in-vivo VFA 3D (FSE sequence) data. Both are included in the folder “data”


If you find this code useful, please consider to cite the following paper:

[1] Ramos-Llordén, G., Vegas-Sánchez-Ferrero, G., Björk, M., Vanhevel, F., Parizel, P. M., San José Estépar, R., den Dekker, A. J., and Sijbers, J.
     NOVIFAST: a fast algorithm for accurate and precise VFA MRI T1 mapping.  IEEE Trans. Med. Imag., early access, doi:10.1109/TMI.2018.2833288




![NOVIFAST](https://github.com/gabrll/MRIT1mappingNOVIFAST/assets/49204215/472cf823-1e9e-4586-8b53-cce67d0f8da7)





© 2021 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pric
