# Geophysics-Papers-Reading-Roadmap

## Seismic Modeling Methods

### Finite-difference
1. Z. Alterman, F. Karal, Propagation of elastic waves in layered media by finite difference methods, Bull. Seismol. Soc. Am. 58 (1968) 367–398.

2. R. Alford, K. Kelly, D.M. Boore, Accuracy of finite-difference modeling of the acoustic wave equation, Geophysics 39 (1974) 834–842.

3. J. Virieux, SH-wave propagation in heterogeneous media: velocity-stress finite-difference method, Geophysics 49 (1984) 1933–1942.

### Pseudospectral methods
1. J. Gazdag, Modeling of the acoustic wave equation with transform methods, Geophysics 46 (1981) 854–859.

2. D.D. Kosloff, E. Baysal, Forward modeling by a Fourier method, Geophysics 47 (1982) 1402–1412.

3. D.D. Kosloff, M. Reshef, D. Loewenthal, Elastic wave calculations by the Fourier method, Bull. Seismol. Soc. Am. 74 (1984) 875–891.

4. B. Fornberg, The pseudospectral method: comparisons with finite differences for the elastic wave equation, Geophysics 52 (1987) 483–501.

### Finite-element methods
1. K.J. Marfurt, Accuracy of finite-difference and finite-element modeling of the scalar and elastic wave equations, Geophysics 49 (1984) 533–549

### Hybird methods
- Spectral-element method

D. Komatitsch, J.-P. Vilotte, The spectral element method: an efficient tool to simulate the seismic response of 2D and 3D geological structures, Bull.
Seismol. Soc. Am. 88 (1998) 368–392.
- Finite-volume method

E. Dormy, A. Tarantola, Numerical simulation of elastic wave propagation using a finite volume method, J. Geophys. Res., Solid Earth (1978–2012) 100
(1995) 2123–2133.


### Space dispersion
#### High-order FD Schemes
1. M.A. Dablain, The application of high-order differencing to the scalar wave equation, Geophysics 51 (1986) 54–66.

2. J.T. Etgen, High-order finite-difference reverse time migration with the 2-way non-reflecting wave equation, Stanford Exploration Project, Report-48 1986, pp. 133–146.

3. J.T. Etgen, Evaluating finite-difference operators applied to wave simulation, Stanford Exploration Project, Report-57, 1988, pp. 243–258.

4. Y. Liu, M.K. Sen, A new time–space domain high-order finite-difference method for the acoustic wave equation, J. Comput. Phys. 228 (2009) 8779–8806.

5. Y. Liu, M.K. Sen, Time-space domain dispersion-relation-based finite-difference method with arbitrary even-order accuracy for the 2D acoustic wave equation, J. Comput. Phys. 232 (2013) 327–345

#### Optimized FD operators
1. O. Holberg, Computational aspects of the choice of operator and sampling interval for numerical differentiation in large-scale simulation of wave phenomena, Geophys. Prospect. 35 (1987) 629–655.

2. J.T. Etgen, A tutorial on optimizing time domain finite-difference schemes: “Beyond Holberg”, Stanford Exploration Project, Report-129, 2007, pp. 33–43.

3. H. Zhou, G. Zhang, Prefactored optimized compact finite-difference schemes for second spatial derivatives, Geophysics 76 (2011) WB87–WB95.

4. C. Chu, P.L. Stoffa, Determination of finite-difference weights using scaled binomial windows, Geophysics 77 (2012) W17–W26.

5. J. Zhang, Z. Yao, Optimized explicit finite-difference schemes for spatial derivatives using maximum norm, J. Comput. Phys. 250 (2013) 511–526.

6. J. Zhang, Z. Yao, Optimized finite-difference operator for broadband seismic wave modeling, Geophysics 78 (2013) A13–A18.

7. Y. Liu, Globally optimal finite-difference schemes based on least squares, Geophysics 78 (2013) T113–T132.

8.  S. Tan, L. Huang, A staggered-grid finite-difference scheme optimized in the time-space domain for modeling scalar-wave propagation in geophysical problems, J. Comput. Phys. 276 (2014) 613–634.

9. Y. Wang, W. Liang, Z. Nashed, X. Li, G. Liang, C. Yang, Seismic modeling by optimizing regularized staggered-grid finite-difference operators using a time–space-domain dispersion-relationship-preserving method, Geophysics 79 (2014) T277–T285.

10. W. Sun, B. Zhou, L.Y. Fu, A staggered-grid convolutional differentiator for elastic wave modelling, J. Comput. Phys. 301 (2015) 59–76.

#### Flux-corrected transport technique
1. J.P. Boris, D.L. Book, Flux-corrected transport. I. SHASTA, a fluid transport algorithm that works, J. Comput. Phys. 11 (1973) 38–69.

2. T. Fei, K. Larner, Elimination of numerical dispersion in finite-difference modeling and migration by flux-corrected transport, Geophysics 60 (1995) 1830–1842.

3. D. Yang, E. Liu, Z. Zhang, J. Teng, Finite-difference modelling in two-dimensional anisotropic media using a flux-corrected transport technique, Geophys. J. Int. 148 (2002) 320–328.

#### the nearly analytical discrete methods
1. D. Yang, J. Teng, Z. Zhang, E. Liu, A nearly analytic discrete method for acoustic and elastic wave equations in anisotropic media, Bull. Seismol. Soc. Am. 93 (2003) 882–890.

2. D. Yang, M. Lu, R. Wu, J. Peng, An optimal nearly analytic discrete method for 2D acoustic and elastic wave equations, Bull. Seismol. Soc. Am. 94 (2004) 1982–1991.

#### Stereo-modeling methods
P. Tong, D. Yang, B. Hua, M. Wang, A high-order stereo-modeling method for solving wave equations, Bull. Seismol. Soc. Am. 103 (2013) 811–833.

### Time-dispersion
#### High-order time FD schemes
1. J.B. Chen, High-order time discretizations in seismic modeling, Geophysics 72 (2007) SM115–SM122.

2. Y. Zhang, G. Zhang, D. Yingst, J. Sun, Explicit marching method for reverse time migration, in: 77th Annual International Meeting, SEG, Expanded Abstracts, Society of Exploration Geophysicists, 2007, pp. 2300–2304.

3. R. Soubaras, Y. Zhang, Two-step explicit marching method for reverse time migration, in: 78th Annual International Meeting, SEG, Expanded Abstracts, Society of Exploration Geophysicists, 2008.

4. Y. Zhang, G. Zhang, One-step extrapolation method for reverse time migration, Geophysics 74 (2009) A29–A33.

#### Rapid expansion method (REM)
1. H. Tal-Ezer, D. Kosloff, Z. Koren, An accurate scheme for seismic forward modelling, Geophys. Prospect. 35 (1987) 479–490.

2. D. Kosloff, A. Queiroz Filho, E. Tessmer, A. Behle, Numerical solution of the acoustic and elastic wave equations by a new rapid expansion method, Geophys. Prospect. 37 (1989) 383–394.

3. R.C. Pestana, P.L. Stoffa, Time evolution of the wave equation using rapid expansion method, Geophysics 75 (2010) T121–T131.

4. E. Tessmer, Using the rapid expansion method for accurate time-stepping in modeling and reverse-time migration, Geophysics 76 (2011) S177–S185.

#### Low rank methods
1. S. Fomel, L. Ying, X. Song, Seismic wave extrapolation using lowrank symbol approximation, in: 80th Annual International Meeting, SEG, Expanded Abstracts, Society of Exploration Geophysicists, 2010.

2. S. Fomel, L. Ying, X. Song, Seismic wave extrapolation using lowrank symbol approximation, Geophys. Prospect. 61 (2012) 526–536.

#### Fourier finite-difference methods
1. X. Song, S. Fomel, Fourier finite-difference wave propagation, Geophysics 76 (2011) T123–T129.

2. X. Song, K. Nihei, J. Stefani, Seismic modeling in acoustic variable-density media by Fourier finite differences, in: 82th Annual International Meeting, SEG, Expanded Abstracts, Society of Exploration Geophysicists, 2012.

3. X. Song, S. Fomel, L. Ying, Lowrank finite-differences and lowrank Fourier finite-differences for seismic wave extrapolation in the acoustic approximation, Geophys. J. Int. 193 (2013) 960–969.

#### Correction methods based on filter and interpolation
1. Y.E. Li, M. Wong, R. Clapp, Equivalent accuracy at a fraction of the cost: overcoming temporal dispersion, Stanford Exploration Project, Report-150, 2013.

2. C. Stork, Eliminating nearly all dispersion error from FD modeling and RTM with minimal cost increase, in: 75th Annual International Conference and Exhibition, EAGE, Extended Abstracts, Tu 11 07, 2013.

3. H. Liu, N. Dai, F. Niu, W. Wu, An explicit time evolution method for acoustic wave propagation, Geophysics 79 (2014) T117–T124.

#### Time dispersion transform
1. M. Wang, S. Xu, Finite-difference time dispersion transforms for wave propagation, Geophysics 80 (2015) WD19–WD25.

2. M. Wang, S. Xu, Time dispersion prediction and correction for wave propagation, in: 85th Annual International Meeting, SEG, Expanded Abstracts, Society of Exploration Geophysicists, 2015, pp. 3677–3681.

## Boundary condition
### Absorbing boundary conditions (ABC)
1. Clayton, R., and Engquist, B., 1977, Absorbing boundary conditions for acoustic and elastic wave equations: Bulletin of the Seismological Society of America, 67, 1529–1540.

2. Reynolds, A. C., 1978, Boundary conditions for the numerical solution of wave propagation problems: Geophysics, 43, 1099–1110. doi:10.1190/1.1440881

3. Liao, Z, Huang, K, Yang, B, and Yuan, Y, 1984, A transmitting boundary for transient wave analyses: Scientia Sinica (Series A), 27, 1063–1076.

4. Higdon, R. L., 1986, Absorbing boundary conditions for difference approximations to the multidimensional wave equation: Mathematics
of Computation, 47, 437–459.

5. Higdon, R. L., 1991, Absorbing boundary conditions for elastic waves: Geophysics, 56, 231–241. doi:10.1190/1.1443035

### Absorbing boundary layers 
1. Cerjan, C., Kosloff, D., Kosloff, R., and Reshef, M., 1985, A nonreflecting boundary condition for discrete acoustic and elastic wave equations: Geophysics, 50, 705–708. doi:10.1190/1.1441945

2. Kosloff, R., and Kosloff, D., 1986, Absorbing boundaries for wave propagation problems: Journal of Computational Physics, 63,
363–376. doi:10.1016/0021-9991(86)90199-3

3. Compani-Tabrizi, B., 1986, k-t scattering formulation of the absorptive acoustic wave equation: Wraparound and edge-effect elimination: Geophysics, 51, 2185–2192. doi:10.1190/1.1442071

4. Sochacki, J., Kubichek, R., George, J., Fletcher, W., and Smithson, S., 1987, Absorbing boundary conditions and surface waves: Geophysics, 52, 60–71. doi:10.1190/1.1442241

5. Bérenger, J. P., 1994, A perfectly matched layer for the absorption of electromagnetic waves: Journal of Computational Physics, 114,
185–200. doi:10.1006/jcph.1994.1159

6. Komatitsch, D., and Martin, R., 2007, An unsplit convolutional perfectly matched layer improved at grazing incidence for the seismic wave equation: Geophysics, 72, SM155–SM167. doi:10.1190/1.2757586

7. Liu, Y., and Sen, M. K., 2010, A hybrid scheme for absorbing edge reflections in numerical modeling of wave propagation: Geophysics, 75, A1–A6. doi:10.1190/1.3295447

8. Liu, Y., and Sen, M. K., 2012, A hybrid absorbing boundary condition for elastic staggered-grid modeling: Geophysical Prospecting, 60, 1114–1132. doi:10.1111/j.1365-2478.2011.01051.x

## Upsampling
1. Moczo, P. (1989). Finite-difference technique for SH-wave in 2-D media using irregular grids-application to the seismic response problem. Geophys. J. Int., 99(2), 321-329. https://doi.org/10.1111/j.1365-246X.1989.tb01691.x

2. Jastram, C., and Behle, A. (1992). Acoustic modelling on a grid of vertically varying spacing. Geophys. Prospect., 40(2), 157-169.
https://doi.org/10.1111/j.1365-2478.1992.tb00369.x

3. Falk, J., Tessmer, E., and Gajewski, D. (1998). Efficient finite-difference modelling of seismic waves using locally adjustable time steps. Geophys. Prospect., 46(6), 603-616. https://doi.org/10.1046/j.1365-2478.1998.00110.x

4. Tessmer, E. (2000). Seismic finite-difference modeling with spatially varying time steps. Geophysics, 65(4), 1290-1293. https://doi.org/10.1190/1.1444820

5. Oliveira, S. A. M. (2003). A fourth-order finite-difference method for the acoustic wave equation on irregular grids. Geophysics, 68(2), 672-676. https://doi.org/10.1190/1.1567237

6. Zhao, H. B., and Wang, X. M. (2008). An optimized staggered variable-grid finitedifference scheme and its application in cross-well acoustic survey. Chinese Sci. Bull., 53(6), 825-835. https://doi.org/10.1007/s11434-008-0042-x

7. Song, G. J., Yang, D. H., Chen, Y. L., and Ma, X. (2010). Non-uniform grid algorithm based on the WNAD method and elastic wave-field simulations. Chinese J. Geophys. (in Chinese), 53(8), 1985-1992. https://doi.org/10.3969/j.issn.0001-5733.2010.08.025

8. Chu, C. L., and Stoffa, P. L. (2012). Nonuniform grid implicit spatial finite difference method for acoustic wave modeling in tilted transversely isotropic media. J. Appl. Geophys., 76, 44-49. https://doi.org/10.1016/j.jappgeo.2011.09.027

9. Zhang, Z. G., Zhang, W., Li, H., and Chen, X. F. (2013). Stable discontinuous grid implementation for collocated-grid finite-difference seismic wave modeling. Geophys. J. Int., 192(3), 1179-1188. https://doi.org/10.1093/gji/ggs069

10. Zhang, J. H., and Yao, Z. X. (2017). Exact local refinement using Fourier interpolation for nonuniform-grid modeling. Earth Planet.
Phys., 1, 58-62. http://doi.org/10.26464/epp2017008

## 
