# PRISM_GEMC
PRISM:- Transiting Exoplanet and Starspot Model. GEMC:-  Optimisation Algorithm for PRISM
PRISM uses a pixellation approach to represent the star and planet on a two-dimensional array in Cartesian coordinates. Six parameters are used to model the transit: the ratio between the planetary and stellar radii, the sum of the fractional radii, 7 the linear and quadratic LD coefficients, the orbital inclination, and the time of mid-transit. Then, four parameters are used to model each starspot: the longitude and colatitude of the centre of the starspot on the stellar surface, the angular size of the starspot and the starspot’s contrast (the ratio between the intensity (I) of the starspot and the surrounding photosphere). For more details see (Tregloan-Reed J., Southworth J., Tappert C., 2013, MNRAS, 428, 3671, Tregloan-Reed J. et al., 2015, MNRAS, 450, 1760, Tregloan-Reed, J., Southworth, J., Mancini, L., et al. 2018, MNRAS, 474, 5485).
GEMC was created in conjunction to PRISM to improve the efficiency of finding a global solution in a complex multivariate parameter space compared to conventional MCMC algorithms (Tregloan-Reed et al. 2013, 2015). GEMC is a hybrid between an MCMC and a genetic algorithm and is based on the Differential Evolution Markov Chain (DE-MC) put forward by Ter Braak (Ter Braak C. J. F., 2006, Stat. Comput., 16, 239).

The codes are written in IDL (Interactive Data Language, For further details, see http://www.harrisgeospatial.com/Productsand
Technology/Software/IDL.aspx.) and were developed to model the transit, limb darkening (LD), and starspots on the stellar disc simultaneously.
