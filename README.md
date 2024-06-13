# OpenGL Computer Graphics-Project
 Computer Graphics Lab project built on C++ using OpenGL freeGLUT library





## Project Objectives

The key objectives of the project included:

### A. 3D Windmill Construction
- The creation of the windmill's base, tower, and blades using various OpenGL primitive shapes, such as polygons, lines, and planes.

### B. Camera Controls
- The implementation of camera controls to allow the user to navigate and explore the 3D windmill scene.

### C. Transformations and Rotations
- The application of transformations, such as translation, rotation, and scaling, to position and orient the windmill components in the 3D space.







## Methodology

To achieve the goal of creating a 3D windmill scene using OpenGL and the GLUT library, the following methodology was followed:

### A. Selection of OpenGL Library
- After reviewing available options, the GLUT (OpenGL Utility Toolkit) library was chosen as the appropriate library to use for this project. GLUT provides a convenient set of functions and utilities for creating and managing OpenGL-based applications.

### B. Windmill Shape Breakdown
- The 3D windmill was broken down into its primary components, including the base, tower, and blades. Each of these elements was further analyzed to  determine the best approach for rendering them using OpenGL primitives.

### C. Coordinate Planning
- On paper, the edge points for each curved and flat object were mapped to specific coordinate values. This step was crucial for ensuring the accurate placement and proportions of the windmill components within the 3D space.

### D. Curved Object Rendering
- For the curved objects, such as the windmill blades, an infinite number of `GL_LINES` were used to approximate the shape. The x and y coordinates were determined using the `cos(x)` and `sin(x)` functions, respectively, while the z coordinate was set to a fixed height `h`.

### E. Flat Object Rendering
- The flat objects, such as the base and tower, were rendered using `GL_POLYGON` with fixed coordinate points that were predetermined on paper.

### F. Coding the Shapes in OpenGL
- The planned polygons and lines were then implemented using OpenGL functions and commands to draw the individual components of the windmill.

### G. Integration with GLUT
- The OpenGL shapes were integrated with the GLUT library to provide additional functionality, such as camera controls and object transformations (rotation, translation, and scaling).





## Tutorial

1. Install freeGLUT
 [FreeGLUT Installation Documentation](https://freeglut.sourceforge.net/docs/install.php) 
2. Compile main.cpp and run the compiled executable target file.
