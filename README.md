# ImageProcessing Midsemester Project

## Description
This repository contains an implementation of the `imfilter()` function and a function called `my_compose()` that combines two images using parts of their Most Significant Bits (MSB) and Least Significant Bits (LSB) of each pixel.

### Part 1: Implementing the `imfilter` function
- Implement a function `r=my_imfilter(s, filter, pad)` that filters the source image (a square matrix of some size) according to a given filter.
- Work on photos, convert them to grayscale, and resize them to 256x256 pixels.
- Compare the results of the filtering with different types of padding (e.g., zero-padding, mirror-padding, etc.).
- Analyze and discuss the biggest differences in the results, their origins, and whether they are visually noticeable.
- Evaluate the performance of your implementation against standard library functions for image filtering.
- Avoid using library functions in your implementation.

### Part 2: Creating the `my_compose` function
- Implement a function `r=my_compose(s, s1, m)` that takes two images and creates a combined image where the `m` high bits (MSB) of the result are from the first image, and the lower `8-m` bits are the high bits (MSB) of the second image.
- Create an additional function to check whether an image is "fake" and explain the algorithm used.
- If `m` is not provided, use a default value of 3.
- Work on photos, convert them to grayscale, and resize them to 256x256 pixels.
