Project:  Finding Lane Lines on the Road

Overview:

This project is heavily based on Python programming langues and the knowledge of OpenCV modules  to find lane lines in the road images.  

The following techniques are used:

1. Use Python to read the list of images from the given directory and display them.  This is the common function we will be using for all the conversions we do in the entire project.
2. Convert to Gray Scale images.
3. Apply Canny Edge Detection Algorithm for all the images and smooth the images with Gaussian kernel.
4. Filter Region of Interest Selection
5. Apply Hough Transform Line Detection

Finally, apply all the techniques to process video clips to find lane lines.
