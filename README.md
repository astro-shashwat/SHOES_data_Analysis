# SHOES_data_Analysis
This Repository deals with calculating Hubble Constant $H_0$ , Hubble Tension $H_tensio$, Universe Age $T_U$ , Universe Spatial Curvature Type $\Omega_k$ and Matter density $\Omega_m$ .

#Read the Header (Column ) of PantheonSHOES.dat as:

- CID Supernova identifier (internal ID)
- IDSURVEY Survey ID the SN came from (e.g. SDSS, SNLS, Pan-STARRS, etc.)
- zHD	Redshift used for the Hubble Diagram (corrected redshift, including peculiar velocity corrections)
- zHDERR	Error on zHD
- zCMB	Redshift in the Cosmic Microwave Background (CMB) frame
- zCMBERR	Error on zCMB
- zHEL	Heliocentric redshift (before CMB correction)
- zHELERR	Error on zHEL
- m_b_corr	Corrected apparent magnitude of the SN (standardized after light-curve fitting & bias corrections)
- m_b_corr_err_DIAG	Diagonal (statistical) uncertainty on m_b_corr
- MU_SH0ES	Distance modulus (µ) calibrated with SH0ES Cepheid ladder
- MU_SH0ES_ERR_DIAG	Diagonal uncertainty on MU_SH0ES
- CEPH_DIST	Cepheid distance modulus (if host galaxy has Cepheid calibration, else missing)
- IS_CALIBRATOR	Flag (1 if SN is in a Cepheid-calibrator host, 0 otherwise)
- USED_IN_SH0ES_HF	Flag indicating whether this SN is used in the SH0ES Hubble-flow fit
- c	SALT2 color parameter (from SN light-curve fitting)
- cERR	Uncertainty in c
- x1	SALT2 stretch parameter (light-curve shape)
- x1ERR	Uncertainty in x1
- mB	Raw apparent B-band magnitude from SALT2 fit
- mBERR	Uncertainty in mB
- x0	SALT2 amplitude parameter
- x0ERR	Uncertainty in x0
- COV_x1_c	Covariance between stretch (x1) and color (c)
- COV_x1_x0	Covariance between x1 and x0
- COV_c_x0	Covariance between c and x0
- RA	Right Ascension of the supernova
- DEC	Declination of the supernova
- HOST_RA	Right Ascension of host galaxy
- HOST_DEC	Declination of host galaxy
- HOST_ANGSEP	Angular separation between SN and its host galaxy
- VPEC	Peculiar velocity correction (km/s)
- VPECERR	Uncertainty on peculiar velocity correction
- MWEBV	Milky Way dust reddening $E(B-V)$ from dust maps
- HOST_LOGMASS	Logarithmic stellar mass of host galaxy (log10 of $M/M_\odot$)
- HOST_LOGMASS_ERR	Error in HOST_LOGMASS
- PKMJD	Modified Julian Date of SN peak brightness
- PKMJDERR	Error in PKMJD
- NDOF	Degrees of freedom of the light-curve fit
- FITCHI2	$\chi^2$ value of the light-curve fit
- FITPROB	Fit probability (from $\chi^2$/NDOF)
- m_b_corr_err_RAW	Raw error on m_b_corr before extra corrections
- m_b_corr_err_VPEC	Contribution of peculiar velocity uncertainty to error in m_b_corr
- biasCor_m_b	Bias correction applied to m_b_corr (from simulations)
- biasCorErr_m_b	Error on biasCor_m_b
- biasCor_m_b_COVSCALE	Covariance scaling factor for bias correction
- biasCor_m_b_COVADD	Additional covariance contribution from bias correction




