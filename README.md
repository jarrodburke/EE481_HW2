# EE481_HW2

Homework 2: (100 points) In all cases, show all images with their corresponding intermediate results
1. (10 pt) Given an input image on the right, (a) compute
output with the filter �1 −1
1 −1�.
1. (10) Design a one dimensional filter of Gaussian, first
derivative of Gaussian, and the second derivative of Gaussian
with sigma = 2.4. Plot these filters with clear annotations
along X and Y direction.
2. (30) Synthetic images are widely used in image analysis to
assess performance of a method. Create a synthetic image as
shown to the right where the background and foreground are
50 and 150, respectively. The large square should be 150-by-
150 pixels, and the small square should be 75-by-75 pixels. Add Gaussian noise
and increase the amount of noise to generate 2 additional corrupt images with
variance of 0.005, 0.05. You will need to normalize these variances if you are
using matlab imnoise command.
b. Apply LoG Filter with sigma of 0.5, 2, 4 and compute zero crossing.
Estimate the LoG filter with a DoG filter.
c. Compute and show the edge magnitude and direction for synthetic and corrupted images.
Study the edge direction along the square. Do you see the edge direction changing? Do you
see that the edge directions are antiparallel at the opposite sides of the square?
3. (20) Use the stent image and apply the following operations
a. Enhance image
b. Add original image with a response of LoG filter and then enhance
c. Create a blurred version of the image with a 3-by-3 filter. Subtract the original from the
blurred version. Add the difference to the original image. Report the results
4. (30) Use Lenna Image
a. Implement a derivative of Gaussian, with sigma of 1, 3, and 5, and convolve with the
Lenna image. Show the derivatives in X and Y directions. Compute and show magnitude
and edge direction.
b. Show the zero-crossing image for sigma = 1, 2, 8.
c. What is your insights based on a-b?
