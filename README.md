# ImageProcessingFilters

This Python program demonstrates various image processing filters using the OpenCV library. It applies filters such as averaging, Sobel, and noise reduction to grayscale images.

Averaging Filter
The program uses a simple averaging filter (kernel) to smooth the input image. The kernel is defined as a 5x5 matrix with equal weights. The resulting image is displayed.

Sobel Filter
The Sobel filter is applied in both vertical and horizontal directions to detect edges in the image. The vertical and horizontal edge images are displayed, and the maximum edges are obtained by combining the two. The resulting image showcases edge detection using the Sobel filter.

Noise Reduction
The program includes a function to reduce "Salt and Pepper" noise in the image. It uses a median blur to iteratively filter out noisy pixels. The noise
