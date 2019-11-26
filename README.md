# Atomic-Line-Info
Returns a tuple consisting of central wavelength, oscillator strength, gamma, and atomic weight for an ion of interest. The information is obtained from the website: https://www.pa.uky.edu/~peter/newpage/, which is hosted by the Department of Physics & Astronomy, University of Kentucky, and maintained by Peter van Hoof, Royal Observatory of Belgium. The current development of the atomic line list is described in [van Hoof, P.A.M., 2018, Galaxies, 6, 63](https://www.mdpi.com/2075-4434/6/2/63). Please cite this paper when you use any data from this list.


    Inputs:
    ion = Ion of interest, e.g. 'OVI'
    cenwave = Approximate wavelength of the transition. Looks for lines within +/-1 angstrom of this wavelength
    
    Usage example:
    ALL('OVI',1031.5)
    
    Returns:
    (1031.93, 0.133, 416000000.0, 15.999)

