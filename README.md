# Zernike_Plotting
<p align="center">
<img src="https://img.shields.io/badge/MatLab%20Version-R2020b-blue"> <img src="https://img.shields.io/github/issues-raw/KatharinaSchmidt1/Zernike_Plotting">
<img src="https://img.shields.io/github/issues-closed-raw/KatharinaSchmidt1/Zernike_Plotting">
</p>  
<a MatLab Code to plot images (.eps or .png) of Zernike polynomials /a>

Examples: 
Image | Description
--- | ---
<img src="/Zernike4.png" width="50%" height="50%"> | Defocus
<img src="/Zernike7.png" width="50%" height="50%"> | Coma
<img src="/Zernike10.png" width="50%" height="50%"> | Trefoil

## Source of functions
The functions calcShape and calcPoly derive from:

      @inbook{Scott:17,author={Scott W. Teare}, 
      title        = {Optics using MatLab},
      chapter      = 10,
      pages        = {139-153},
      publisher    = {SPIE Press},
      year         = 2017,
      volume       = TT111,
      address      = {Bellingham, Washington, US}}
    
## How to use
1. Download all matlab files (.mlx) into the same folder
2. Start *main.mlx* and set the current folder to working directory or add it to PATH
3. Insert resolution of the derived images (Pixel)
4. Choose file format
5. Place a checkmark in the boxes of the Zernikes you want to plot
6. The plots appear in the live editor and in the current folder
