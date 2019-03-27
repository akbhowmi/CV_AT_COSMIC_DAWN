This is a Cosmic variance calulator for high redshift (7<z<10) galaxies.

The calculator is within the ipython notebook "COSMIC_VARIANCE_AT_HIGH_Z.ipynp" 

Within this, file user can input the parameters of the survey:

#------------------------------------------LIST_OF_INPUTS AND THEIR DEFAULT VALUES---------------------------------------------------

H_band_threshold=30.   # Maximum threshold H band magnitude. Stay within 30 and 25

redshift=8.0         # Mean redshift. Stay within 7 and 10 

redshift_width=0.1     # Redshift width. Do not exceed box size of BlueTides i.e. 400 Mpc/h.

survey_length_in_arc_sec=200.    # Length of the survey. Do not exceed box size of BlueTides i.e. 400 Mpc/h. 

survey_aspect_ratio=2.          # Aspect ratio of the survey

#------------------------------------------------------------------------------------------------------------------------------------

To change the cosmology, edit the file 'cosmology.txt'. However, note that the default parameters are set to match the BlueTides cosmology, using which the calculator was constructed. Therefore, I do not recommend changing these parameters.
