# Intensity-calculation-of-coacervates
This repository provides Python code for calculating Fluorescence intensity of coacervates from microscopic images.
This Python script processes .tif microscopy images of coacervate droplets to extract average intensities, segment droplets, and visualize them with boundary overlays. 
To ensure proper sorting and processing, all image files must follow a strict naming format:
Name your image files as sequential numbers:
1.tif, 2.tif, 3.tif, ..., n.tif
Do not name the blank reference image with a number. It must be named:
blank.tif
For each image:
A CSV file of droplet intensities is saved
A boundary-marked image is saved as .png
