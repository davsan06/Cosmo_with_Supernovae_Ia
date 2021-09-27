# Cosmo_with_Supernovae_Ia
In this repository you can find Python notebooks to compute LCDM paramaters using supernovae Ia data.

There are two different ways of doing the analysis:

  * Sampling just over on cosmological parameter, which is chosen to be $\Omega_\Lambda$ the quantity related with the abundance of dark energy in the universe.
  * Sampling over two different cosmological parameters: $\Omega_\Lambda$ and $w_{DE}$. The later is the barotropic constant from the dark energy equation of state which relates the pressure and the density of the fluid. In the Standard Model of Cosmology this value is fix $w_{DE} = -1$ as we think it has cosmological constant properties. In this analysis we free this parameter to check if there's something else...

The output of the notebook contains:

 * Best-fit value and associated errors for the params
 * Figures: Hubble parameter evolution with redshift for several universes, radial comoving distance evolution with redshift for different universes, distance modulus evolution with redshift and supernovae data, reduced $\chi^2$ minimization in 1 and 2-D.
