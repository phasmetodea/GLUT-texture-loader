# GLUT texture loader
 C header file to load bitmap images

How to install:
1. Download the C header file
2. Put the header file in your compilers "include" folder (or in your project folder)
3. Add it to your program by using #include "GLtexture.h"


To load a .bmp file you use the function GLloadtexture("image.bmp").
The image data will be loaded into the gltexture variable.
To bind the current texture you can use glBindTexture(GL_TEXTURE_2D, gltexture).

