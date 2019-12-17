# Image-Stitching
This repo contains stitching number of images using sift feature descriptors and mouse points and create a Panorama. 
FLANN feature matching (Fast Approximate Nearest Neighbor Search Library ) is used for match the SIFT features of images.
cv.findHomography is used in order to compute the Homography of 2 images and RUNSAC is used to remove outliers.
