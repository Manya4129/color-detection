# color-detection
In this work includes the detection of color from each region of the given image

# Required materials 
Using a CSV file which contains five columns colour, name of the colour, hexadecimal code for the colour and the three channels red, green and blue. The CSV file contains in total of 865 rows of different shades of colour. Three different images are taken from the internet which contains a variety of shades. 

# Description
Our program first read the image using the OpenCV function imread() and then resizes it properly to be able to fit within the window. Created a named window which pops up when the image is read. Connected the mouse event through setMouseCallback() function which uses a function whose main purpose is to take the location of the mouse pointer and output the three colour channel values. Colour values are compared with the RGB values of CSV file and those values with a minimum absolute difference are picked as our colour and then we draw a rectangle within the image to show up the RGB values and the associated colour with the value.

#### Youtube Video Link - https://youtu.be/Or2KTJPC8zM
