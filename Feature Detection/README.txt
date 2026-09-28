# Feature Detection from Scratch

Notebooks implementing classic feature detection algorithms, mostly from scratch in NumPy for conceptual understanding. OpenCV is used only for basic operations such as drawing, and edge detection as an input step.

1. **Canny Edge Detection**: Gaussian smoothing, gradients, non-max suppression, and double thresholding with hysteresis
2. **Line Detection with the Hough Transform**: voting in $(\rho, \theta)$ space, peak detection, and non-max suppression
3. **Circle Detection with the Hough Transform**: voting in a 3D $(a, b, r)$ accumulator, with suppression of nearby detections
4. **Harris Corner Detection**: gradients, structure tensor, Harris response, and non-max suppression