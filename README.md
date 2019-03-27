This is a Cosmic variance calulator for high redshift (7<z<10) galaxies.

The calculator is within the ipython notebook "COSMIC_VARIANCE_AT_HIGH_Z.ipynp" 

Within this, file user can input the parameters of the survey:

#------------------------------------------LIST_OF_INPUTS AND THEIR DEFAULT VALUES---------------------------------------------------

H_band_threshold=30.   # Maximum threshold H band magnitude

redshift=8.0         # Mean redshift 

redshift_width=0.1     # Redshift width

survey_length_in_arc_sec=200.    # Length of the survey 

survey_aspect_ratio=2.          # Aspect ratio of the survey

#------------------------------------------------------------------------------------------------------------------------------------

To change the cosmology, edit the file 'cosmology.txt'. However, note that the default parameters are set to match the BlueTides cosmology, using which the calculator was callibrated.
