# Air-Canvas
 Created an Air Canvas with the help of Open-CV module

Working Module: 

Start reading the frames and convert the captured frames to HSV colour space.(Easy for colour detection).

Prepare the canvas frame and put the respective ink buttons on it. Adjust the trackbar values for finding the mask of coloured marker.

Preprocess the mask with morphological operations.

Detect the contours, find the center coordinates of largest contour and keep storing them in the array for successive frames.

Finally draw the points stored in array on the frames and canvas .

Requirements: python3 , numpy , opencv installed on your system.
