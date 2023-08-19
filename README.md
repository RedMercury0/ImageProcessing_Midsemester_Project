# ImageProcessing_Midsemester_Project
This is an implementation of the imfilter() function and function called my_compose that combine 2 images with parts of their MBS and LSB of each pixel.

Part 1: Implementing the imfilter function.
Write r=my_imfilter(s,filter,pad) a function that "filters" the source image (a square matrix of some size) according to a filter of some size. 
with the help of the function you wrote, you will perform smoothing and sharpening of the given image.

Implement 3 types of padding\n
Work on photos you took, transfer them to gray levels, size (256X256)
Compare the result with running the cipher functions. What is the biggest difference? from where Where does the difference come from? Is it visually noticeable?
Compare the performance against the library functions.
Do not use library functions in the implementation.



Part 2: Creating new function, my_compose.

Write a function r=my_compose(s,s1,m2) that receives 2 images and creates "combined" image where the m high bits (msb) of the result are from the first image, and the lower 8-m are the high bits (msb) of the second image.

Also, write a function that checks whether the image is "fake". Explain what you did (what is the algorithem).

If m is not given, the default is 3.

Work on photos you took (move them to gray level 256X256).

