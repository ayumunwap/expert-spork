# Current pipeline used
In the main function to process an image,
- cropping a trapezoid region from a glayscale and blurred image.
- running canny edge and hough image on the cropped image.
- hough lines are drawn in green per each left and right plane. 
- final output lines are drawn in red after linear approximations.

# The shortcomings(situation where the pipeline might fail or factors that might affect the pipeline) 
Parameters are not optimized as the white lines are not always detected.

# Suggestions for improving this algorithm.
W.r.t. algorithm, averaging the red lines with the last flames could be done, as well as Parameter optimization.
