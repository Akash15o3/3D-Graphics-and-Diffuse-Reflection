# 3D-Graphics-and-Diffuse-Reflection
Use of LPC 1769 and McuXpresso as Software to display 3D Graphics and Diffuse Reflection

# Lab 3 Shading Models for Advanced Microprocessor 3D GE Design   

# 1. This lab is for 3D shading model and diffuse reflection computation on LPC1769 micro processor platform, you will need to 
   (1) generate 3 decorated solid cubes, each with different size, and with different orientation angle (orientation of the cube is by its normal 
       vector, denoted here as n=(nx, ny, nz), which is a vector perpendicular  to the top surface of the cube). 
   
   
   (2) Note, you may want to try the size of the cube with side length of 50 
       to begin with, and the virtual camera location E = (ex,ey,ez) = 
       (100, 100, 100) for example.  
   
   
   (3) The decoration of each surface for each cube can be re-used from 
       Lab 2, for example, for surface 1, S1, the screen savers on it; for 
       surface 2, S2, the trees (forest) on it, and for surface 3, S3, the self
       designed one letter of your name initial on it (for example, for 
       Akash, you will put self designed font "H" on surface 3).  
   
   
   (4) place a point light source P_s(xs, ys, zs) in the world coordinate 
       system, you design its location, as a reference, you may consider 
       P_s(xs, ys, zs) = (40,60,120) as a testing location and you can may 
       adjustment later accordingly.  
   
   
   (5) compute the ray equation and its intersection with the x_w-y_w plane.
       For each cube there are 4 ray equations, hence, each of these ray 
       equation will form intersection point with the x_w-y_w plane, there are 
       4 intersection points for each cube, total 12 intersection points. So,  
       keep track each set of 4 points and produce a shade for each cube 
       by plotting 4 vertices polygons. Be sure to use dark blue or to produce
       the shade. 
   
   
   (6) compute diffuse reflection on the top surface of the cube. 

# 2. For the requirements of 3 decorated solid cubes, 
   (1) use 3D linear transformation matrices to create different location, 
       different size.
   
   
   (2) compute normal vector for each cube by using vector cross product, then 
       use 3D arbitrary rotation matrics to rotate each different size cubes 
       (three of them).    
  
  
  (3) use the above 2 steps (1) and (2) matrics to apply them on the linear 
       decoration algorithm, so each cube is also decorated accordingly.    
   
# 3. For the requirements of generating 3 shades, 
   (1) First compute 4 intersection points for each cube, then plot the shade 
       on the x_w-y_w plane by painting it in dark colour, such as dark blue or 
       black. 
   
   
   (2) To make sure the shade looks good, you may want to first paint
       x_w-y_w plane by light blue.  
  
  
  (3) then repeat the shade computation for the rest of the cubes.
