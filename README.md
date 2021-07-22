# AAFragpy

Python implementation of secondary particle production model AAFrag (based on QGSJEt-II-04m). The code is modified after the original AAFrag code written on Fortran [1].

This package allows to quickly reconstruct the differential cross-sections of secondary gammas, leptons, and hadrons producing in a result of hadronic interaction between primary hadrons and different targets.

The package allows to calculate the spectrum of products knowing the spectra of primary particles and the composition of the target in the wide energy range from hundreds of MeV to EeVs.

Additional consideration of low-energy nuclear interactions is also possible using Kamae et al. 2006 [2] and Kafexhiu et al. 2014 [3] codes.

Examples of package usage are given in the Jupiter Notebook.

You can also get started quickly using `Binder <http://mybinder.org>`_ to run the tutorials in
your web browser within a remote server:

.. image:: http://mybinder.org/badge.svg
    :target: https://mybinder.org/v2/gh/astropy/astropy-tutorials/main?filepath=tutorials/notebooks

Comments are welcome!

If you are using AAFragpy, please cite it as:

TBA

References:


[1] M. Kachelrieß, I. V. Moskalenko, and S. Ostapchenko, “AAfrag: Interpolation routines for Monte Carlo results on secondary production in proton-proton, proton-nucleus and nucleus-nucleus interactions,” Comput. Phys. Commun., vol. 245, p. 106846, 2019. <https://doi.org/10.1016/j.cpc.2019.08.001>

[2] T. Kamae, N. Karlsson, T. Mizuno, T. Abe, and T. Koi, “Parameterization of γ, e+-, and Neutrino Spectra Produced by p-p Interaction in Astronomical Environments,” Astrophys. J., vol. 647, no. 1, pp. 692–708, Aug. 2006. <https://doi.org/10.1086/505189>

[3] E. Kafexhiu, F. Aharonian, A. M. Taylor, and G. S. Vila, “Parametrization of gamma-ray production cross-sections for pp interactions in a broad proton energy range from the kinematic threshold to PeV energies,” Phys. Rev. D - Part. Fields, Gravit. Cosmol., vol. 90, no. 12, pp. 1–19, Jun. 2014. <https://doi.org/10.1103/PhysRevD.90.123014>