![alt text][image0]

[//]: # (Image References)
[image0]: ./images/s_triangle.gif
[image1]: ./images/s_triangle.png

## Constructing Fractals  
This repository is intended to contain code for generating fractals. Most will likely be of the 2D variety, but time allowing, I will learn to produce more complex 3D fractals.


#### Sierpinski triangles
The Sierpiński sieve is a fractal described by Sierpiński in 1915. Sierpinski triangles, the shapes generated by the sieve, is one of the simplest fractal shapes in existence, yet they are fascinating since one can play for hours altering the algorithm to change behavior. The steps to produce the images shown in the GIF above are simple:

1. define 3 points on the plane to be vertices of a triangle, call them points A, B, & C
2. choose a starting point anywhere on the plane (the image)
3. choose at random either point A, B, or C and then move halfway towards that point
4. Repeat step 3 until you get tired of it

The following of the steps, like those above, to fill-in points in a fractal is called a "[https://en.wikipedia.org/wiki/Chaos_game](Chaos Game)".

[Here is the program to produce the images](Sierpinski_triangle.py). As is, it shows every 10th generated image. You can change this as you like. You can also write the images to file instead of viewing them.

#### next one in progress ...  
