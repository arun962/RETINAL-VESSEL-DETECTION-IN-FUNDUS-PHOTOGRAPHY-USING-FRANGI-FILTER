# RETINAL-VESSEL-DETECTION-IN-FUNDUS-PHOTOGRAPHY-USING-FRANGI-FILTER

## ALGORITHM:
1) Start
2) Read the RGB retinal fungus photography
3) Convert it into grayscale image
4) Create a mask to filter out the input image
5) Perform Frangi filtering for the input image with the help of eigenvalues computed
from the hessian matrix to detect the blood vessels.
6) Convolve the filtered image with the mask.
7) Then, do gray-thresholding & convert to binary image.
8) Compute the connected components
9) Perform morphological operations such as dilation and erosion & 2 selections are
made based on Area computation
10) Final selection section is based upon Eccentricity.
11) Display retinal vessel detected image.
12) Stop
