##Task
We create 2D objects analytically and save in a dxf file (d26.dxf).
The meaning of execution in obtaining a list of necessary objects for a particular case
Iterating then this list, we call the available functions. With each execution, an object is added to our drawing
##Execution idea
We must choose shapes from the following list: circle, ellipse, polyline with 6 points. 2 shapes from connected rectangles (bl1, bl2) are also available. bl1 has an already defined hole in the center. We set the parameters of two rectangles in bl2 ourselves from the command line.  
So, first we list all the forms on the command line. Then, in response to requests, enter the form parameters in the same place. 
##Idea for development
Improve the code by creating blocks from more complex shapes 
This project is licensed by MIT.

© Vadim Stetsenko 2020


