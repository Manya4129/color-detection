# color-detection
In this work includes the detection of color from each region of the given image

# Required materials 
Using a CSV file which contains five columns color, name of the color, hexadecimal code for the color and the three channels red, green and blue. The CSV file contains in total 865 rows of different shades of color. Three different images are taken from internet which contains variety of shades. 

# Description
Our program first read the image using the openCV function imread() and then resizes it properly to be able to fit within the window. Created a named window which pops up when image is read. Connected the mouse event through setMouseCallback() function which uses a function whose main purpose is to take the location of the mouse pointer and output the three color channel values. Color values are compared with the RGB values of CSV file and those values with minimum absolute difference are picked as our color and then we draw a rectangle within the image to show up the RGB values and the associated color with the value.
