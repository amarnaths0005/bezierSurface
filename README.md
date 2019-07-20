# bezierSurface
HTML5 Application to draw a Bezier surface with 16 control points (4 x 4), and to manipulate these control points.

Requirements:
   1. Should enable the user to modify the x, y, z coordinates of the 16 control points
       forming a 4 x 4 grid of control points for the Bezier Surface.
       The range for coordinates of the corner points should be [-1,1]. For the middle 
       points, the range should be [-3, 3]. The user should be able to modify these 
       through sliders.
   2. Should display the Bezier 4 x 4 Surface on the screen, and this surface should 
      change dynamically as the user modifies any of the values using sliders. 
      Perspective View. Should display a wireframe of the surface if the 
      Wireframe checkbox is checked. 
   3. Should display the bounding box of dimension 2 units, centred at the origin.
   4. Should enable the user to modify the camera angle (degrees), from which 
      viewing is done.
   5. Should enable the user to modify the u, w values of a chosen point, and should 
      display a moving point on the surface as the user modifies these values 
      using the sliders.
   6. All user input should be via sliders.
   7. Should use WebGL, in the form of three.js. 

Tested on Chrome, Firefox and Edge, on Windows.
Uses WebGL as available in three.js

Please report issues to amarnaths.codeproject@gmail.com

Screenshot

![Screenshot of BezierSurface](https://github.com/amarnaths0005/bezierSurface/blob/master/bezierSurface.png)
