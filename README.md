# Computer Vision

## Project 1

1) Write a function that filters (convols) the image with a given kernel.


- Compute horizontal gradient (with sobel)→ save as image_sx

- Compute vertical gradient (with sobel) → save as image_sy

- Compute the magnitude of gradients → save as image_grad

- Compute edge orientations  → save as image_orient


2) The sobel operator is a 3x3 kernel. However, vertical and horizontal gradients can be implemented with different sizes such as 5x5, 7x7, etc. Write a function that generalizes sobel kernel to any size.

## Project 2

1) Apply all necessary steps for the Canny edge detection algorithm.
 
- Horizontal and vertical filtering
- Find magnitude and orientation of gradient
- Non-maximum suppression 
- Linking and thresholding
- Implementing scale-space to detect edges in different scales. 


2) Implement Harris corner detector.
- Compute Ix, Iy as in the first question.
- Construct Hassin matrix M for every (i,j) pixel of the image
