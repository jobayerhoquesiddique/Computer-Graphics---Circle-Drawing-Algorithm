# Computer-Graphics---Circle-Drawing-Algorithm
OpenGL Program: Rendering a Smiling Cloud Using GL_TRIANGLE_FAN and GL_LINE_STRIP This OpenGL program utilizes the GLUT (OpenGL Utility Toolkit) to render a visually appealing, cartoon-style cloud with a smiling face. The graphical elements are constructed using GL_TRIANGLE_FAN for smooth, filled circles and GL_LINE_STRIP for curved line segments.
Features and Implementation Details:
Cloud Formation:

The cloud is represented as an overlapping set of seven circles to achieve an organic, fluffy appearance.
The cloud is colored in a light blue shade to create a soft and natural look.
Facial Features:

Eyes and cheeks are drawn using filled circles with appropriate shading.
A curved smiling mouth is created using GL_LINE_STRIP, simulating an arc.
Rendering Techniques:

The drawCircle() function utilizes GL_TRIANGLE_FAN to create smooth, filled circles by defining multiple vertices around a center point.
The drawSmile() function generates a curved smile using trigonometric calculations to plot an arc between specified angles.
Coordinate System & Projection:

The program uses glOrtho(0.0, 1.0, 0.0, 1.0, -1.0, 1.0) to define a normalized coordinate space for precise control over object placement.
Double Buffering:

The function glutSwapBuffers() ensures smooth rendering by preventing flickering artifacts.
Applications:
Suitable for educational purposes, demonstrating fundamental OpenGL rendering techniques.
Can be extended for animated scenes or interactive graphics applications.
