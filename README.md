#A simple tool of visualizing 3-D datacubes in FITS format

The visualization is implemented by MayaVI and the interface is made with TraitsUI.

##Denpendencies

* Mayavi,
* TraitsUI,
* astropy,
* numpy,
* scipy,
* and ImageMagick to make the movies.

##Render the P-P-V datacubes in three options

1. Iso-surfaces colored by velocities.
2. Iso-surfaces colored by intensities.
3. Scattered dots colored by intensities.

The first two can be saved in a 'mesh' file and be imported to softwares such as Blender or Meshlab, and be uploaded to Sketchfab.

##Known issues

1. Cannot load a different fits file if the current file name includes path: have to delete the current 'fitsfile' name first...
2. The latest Mayavi (v4.4+) does not allow a random name for a new attribute of a field. I have to revert to the previous Mayavi version (v4.3).
3. To be found...
