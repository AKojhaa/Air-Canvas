# Air Canvas 
Air Canvas, often referred to as the Virtual Pen
In This Project it will detect BLUE color on the Camera 
Whatever u Drawn int the Camera it will written on paint pad .

# Requirements 
-Python3
-NumPy
-OpenCV

# Algorithum 
-Start reading the frames and convert the captured frames to HSV color space (Easy for color detection). 
=Prepare the canvas frame and put the respective ink buttons on it. 
-Adjust the track bar values for finding the mask of the colored marker. 
-Preprocess the mask with morphological operations (Eroding and dilation). 
-Detect the contours, find the center coordinates of largest contour and keep storing them in the array for successive frames (Arrays for drawing points on canvas). 
-Finally draw the points stored in an array on the frames and canvas.
