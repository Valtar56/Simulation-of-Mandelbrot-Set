# Simulation-of-Mandelbrot-Set

Mandelbrot set is a set of complex numbers, for which the function: 
			Zn+1 = Zn² + C 
     does not diverge when iterated from Z = 0 and remains bounded within absolute value 2.
### Aim: 
Drawing best fit regression curves for different colour pixels in different images formed by changing the value of the new variables introduced in the modified Mandelbrot set.
Determining the degree of best fit curves and corresponding R² values for different colour pixels.
Finding the equation of best fit curves for each colour.
Observing the effects of newly introduced variables on the shape of the Mandelbrot set.

### Methodology:
The variables to be added are K and L such that, the Mandelbrot function becomes:
Zn+1 = Zn² + C +K +L
	where K and L are real and imaginary numbers respectively.

By assuming horizontal axis as real axis and vertical axis is imaginary axis, we plot the modified set on it.
-Doing this project on Jupyter notebook and by using various python libraries like numpy, matplotlib, pandas, pillow, sklearn  etc.
-Made a data frame of all coloured pixels which were in the plot and made different scatter plots for different colour, giving cyan more priority.
-Drew best fit curves for different coloured pixel and find out the degree and coefficients of the curves by using machine learning approach.
-Calculated R² values for the best fit curves, where R² > 0.95.

### Implementation Details:
Plotted the normal Mandelbrot set.
-Generated as many images(100) as possible by varying the values of:
K alone,
L alone,
K and L both,
-Generated an animated file by combining these graphs For all the 3 cases.
-Tabulated the number of pixels for each colour for each graph
-Plotted the pixels numbers for each colour for each case and observed how they are varying.
-Fitted regression curves on the pixel values with R² > 0.95.
-Calculated coefficients for each case for each colour.
-Determined the degree of polynomial at which they were varying by trial and error.

### Graphical Visualisation:
Degree of each polynomial found out: 8
-Cyan colour is analysed here because only this colour converges for all the iterations.
-Different colours on image shows different levels of instability.
-Depth of colour gives an idea of how many iterations it took to explode.

