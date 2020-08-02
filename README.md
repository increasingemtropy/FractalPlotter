# FractalPlotter
Python function to plot Fractal sets

Default fractal is the Mandelbrot set, given by the equation
Z_{n} = Z_{n+1}^2 + c
Z_0 = c

cf: https://mathworld.wolfram.com/MandelbrotSet.html

Initialise a grid of points in the complex plane, then use each one as a starting point for the iterative equation (up to a fixed n)
If the point appears to converge to zero (it dips under some threshold within the number of iterations) then the value is coloured depending on the number of iterations it takes to converge. If it does not converge within n iterations, then the point is coloured blue.
