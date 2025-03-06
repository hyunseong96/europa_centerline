# europa_centerline

This is for drawing centerlines on band features on Europa.
It uses techniques based on Xiao et al. (2022), https://doi.org/10.3390/rs14092074
After polynomial regression, polynomial line is broken down into points by certain to build final centerline.

centerline_sample.ipynb is the jupyter notebook file for centerline python code.
complex.tif is the image sample for centerline production.
one_band_wgs.tif is secondary sample you can try

following libraries whould be downloaded
numpy, matplotlib, scipy, sklearn, PIL, gdal, skimage, cv2
