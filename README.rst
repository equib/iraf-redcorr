=======
redcorr
=======

IRAF STSDAS Reddening Correction Functions
==========================================

IRAF functions for reddening and extinctions from the `Space Telescope Science Data Analysis System (STSDAS) <https://web.archive.org/web/20141110064251/http://www.stsci.edu/institute/software_hardware/stsdas>`_ package distributed by the Space Telescope Science Institute (STScI) :

* ebmvlfunc.x: Evaluation of Howarth's LMC extinction curve

* ebmvxfunc.x: Extended reddening law extinction function

    - GAL1: First galactic reddening law (Seaton's)

    - GAL2: Second galactic reddening law (Savage and Mathis's)
    
    - GAL3: Third galactic reddening law (Cardelli, Clayton & Mathis)
    
    - SMC: Reddening law for Small Magellanic Cloud
    
    - LMC: Reddening law for the Large Magellanic Cloud
    
    - XGAL: Extragalactic reddening function
    
* redlaw.x: Interstellar extinction function (ISEF)

    - gal_redlaw: Calculates the ISEF for the Galaxy by Savage & Mathis (1979)

    - ccm_redlaw: Calculates the ISEF for the Galaxy by Cardelli, Clayton & Mathis (1989)
    
    - lmc_redlaw: Calculates the ISEF for the LMC by Howarth (1983)
    
    - smc_redlaw: Calculates the ISEF for the SMC by Prevot, et al. (1984)
    
    - jbk_redlaw: Returns the ISEF of Whitford (1958), as adapted by Kaler (1976)
  
