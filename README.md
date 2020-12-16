# Open source codes employing isogeometric analysis (IGA)
A curated list of some open source frameworks, libraries and softwares employing isogeometric analysis. This list is by no means complete. So if you would like me to add something, please send me a link to sthavishthabr@gmail.com or perform a pull request. 

---------------------------

* [G+Smo](https://github.com/gismo/gismo/wiki) [[1](#gismo)] - an object-oriented, cross-platform, template C++ library which supports dimension-independent NURBS, adaptive splines etc. Developed at the Johannes Kepler University and RICAM Institute of the Austrian Academy of sciences. 
* [GeoPDEs](geopdes.sourceforge.net) [[2](#geopdes_1), [3](#geopdes_2)] - a numerical framework written in Octave (compatible with MATLAB). Also inclusion of multipatch domains, adaptive methods with hierarchial B-splines, divergence and curl conforming spline spaces. Developed at the University of Pavia, Italy.
* [igafem](https://sourceforge.net/projects/cmcodes/files/) - a three-dimensional framework written in MATLAB using Galerkin method and collocation. Also supports global h-refinement using knot insertion, p-, k-refinement and other features. Developed at the [Delft University of Technology](https://www.tudelft.nl/en/), Netherlands.  
* [Igatools](https://code.google.com/archive/p/igatools/) [[4](#igatools)] - written in C++11 and uses object oriented and generic programming techniques. Supports isogeometric elements of h-div and h-curl type, dimension independent code. 
* [IGA-dealii](https://github.com/mathLab/IGA-dealii) [[5](#igadealii)] - supports classes for performing isogeometric analysis using the deal.ii library. Developed at the International School for Advanced Studies, SISSA. 
* [ISOGAT](http://www-m2.ma.tum.de/bin/view/Allgemeines/EXCITING) - a tutorial code written in MATLAB for solving elliptic diffusion-type problems including Poisson's equation on single patch geometries. Primarily intended for small-scale/tutorial-related problems. Developed at the Faculty of Mathematics at [TU Munich](https://www.tum.de/en/).
* [mechanoChemIGA](https://github.com/mechanoChem/mechanoChemIGA) [[6](#mechanochemiga)] - a high performance parallel code built on top of PetIGA and PETSc libraries. Supports PDEs describing solid mechanics and chemistry (including the Cahn-hiliard phase field model). Developed at the [Computational Physics Group](http://www.umich.edu/~compphys/index.html), [University of Michigan](https://umich.edu/).
* [PetIGA](https://bitbucket.org/dalcinl/petiga/src/master/) [[7](#petiga)] - a high performance parallelized numerical framework written in C, which adds the NURBS based discretization capabilities on top of PETSc. Developed by the Center for Numerical Porous Media, Division of Computer, Electrical, and Mathematical Sciences & Engineering ([CEMSE](https://cemse.kaust.edu.sa/)) at [King Abdullah University of Science and Technology](https://www.kaust.edu.sa/en). The same set of researchers have developed [PetIGA-MF](https://doi.org/10.1016/j.jocs.2016.09.010) written on top of PetIGA but this is not open-source.
* [Pigasus](https://github.com/ratnania/pigasus) [[8](#pigasus)] - a FORTRAN library interfaced with Python which includes a visualization module as well. Supports B-splines and NURBS. Developed at CEA, France. 
* [tiGAr](https://github.com/david-kamensky/tIGAr) [[9](#tigar)] - a high performance Python library for isogeometric analysis using IGA. Developed at the Department of Mechanical and Aerospace Engineering, [University of California at San Diego](https://ucsd.edu/).

---------------
## References

1. <a name="gismo"></a> [Official website of G+Smo](https://gismo.github.io/)

1. <a name="geopdes_1"></a> de Falco, C., Reali, A., Vasquez, R., _GeoPDEs: A research tool for Isogeometric Analysis of PDEs_, Advances in Engineering Software, Vol. 42 (12), pp. 1020-1034, 2011. [Link](https://doi.org/10.1016/j.advengsoft.2011.06.010)

1. <a name="geopdes_2"></a> Vasquez, R., _A new design for the implementation of isogeometric analysis in Octave and Matlab: GeoPDEs 3.0_, Computers & Mathematics with Applications, Vol. 72 (3), pp. 523-554, 2016. [Link](https://doi.org/10.1016/j.camwa.2016.05.010)

1. <a name="igatools"></a> Pauletti, M. Sebastian, et al. , _Igatools: An isogeometric analysis library_, SIAM Journal on Scientific Computing, Vol. 37 (4), pp. C465-496, 2016. [Link](https://doi.org/10.1137/140955252)

1. <a name="igadealii"></a> [Official website of IGA-dealii](https://zenodo.org/record/59834#.X9ozTMJS_VM)

1. <a name="mechanochemiga"></a> Rudraraju, S., Van der Ven, A., Garikipati, K., _Phenomenological treatment of chemo-mechanical spinodal decomposition_, Computational Materials, Vol. 2, 2016. [Link](10.1038/npjcompumats.2016.12)

1. <a name="petiga"></a> Dalcin, L., Collier, N., Vignal, P., Côrtes, A.M.A, Calo, V.M., _PetIGA: A framework for high-performance isogeometric analysis_, Computer Methods in Applied Mechanics and Engineering, Vol. 308, pp. 151-181, 2016. [Link](https://doi.org/10.1016/j.cma.2016.05.011)

1. <a name="pigasus"></a> Ratnani, A., _Pigasus : Python for IsoGeometric AnalysiS and Unified Simulations_, Computer Methods in Applied Mechanics and Engineering, Vol. 308, pp. 151-181, 2016. [Link](https://hal.inria.fr/hal-00769225)

1. <a name="tigar"></a> Kamensky, D., Bazilevs, Y., _tIGAr: Automating isogeometric analysis with FEniCS_, Computer Methods in Applied Mechanics and Engineering, Vol. 344, pp. 477-498, 2019. [Link](https://doi.org/10.1016/j.cma.2018.10.002)