# webgl-mandelbrot

## Simple mandelbrot viewer using WebGL. On the fractal the mouse pointer selects the area, on which the corresponding Julia sets are rendered as an X-Ray overlay. 

![Alt text](screenshot.png?raw=true "Title")

## [<<-- Live preview -->>](http://htmlpreview.github.io/?https://github.com/zbendefy/webgl-mandelbrot/blob/master/index.html)

The Mandelbrot and Julia sets are basically two views of the same 4D fractal geometry. The 4D julia set is defined as the points where the z(n) = z(n-1) + c series does not diverge. The 2D Mandelbrot set is defined as 2D plane in this 4D geometry, where the series start from (0,0), so z(0) is fixed to (0,0). The 2D julia set, is defined as the 2D plane in the 4D geometry, where the C constant is fixed. In other words, a *P* point of the 2D Mandelbrot set is the origin (center) point of the Julia set, where the Julia set's *C* constant is *P*.
Displaying the Julia overlay is just one of many ways to visualize this 4D fractal on a 2D screen. For other visualizations, look up Buddhabrots, and 3D cross-sections of the Julia sets.

Based on paulirish's [webgl-boilerplate](https://github.com/paulirish/webgl-boilerplate)! 
