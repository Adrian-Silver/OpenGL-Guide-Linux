How to Install and Use OpenGL in Debian Based Linux Versions 

What is OpenGl?

OpenGL(Open Graphics Library) is a cross-language, cross-platform Application Programming Interface(API) that has a wide variety of functions that enable manipulation of graphics(3d and 2d vectors) and images.



Who is this guide for?

This guide is useful to Computer Science students that are taking Computer Graphics as a unit or those who are simply trying to use OpenGL on a Debian OS.



How to Install OpenGL

    1. sudo apt update.

    2. sudo apt install freeglut3-dev

    3. sudo apt-get install freeglut3 freeglut3-dev libglew-dev

    4. sudo apt-get install mesa-utils  
           -  mesa-utils package enables use of glxinfo command.

    5. glxinfo  
           -  lists info about the OpenGLvcapable visuals

    6. g++ <file_name.cc> -lglut -lGL -lGLEW -lGLU -o OpenGLExample  

           -  This will link the OpenGL libraries to the program and compile it.

    7. ./OpenGLExample  
           -   is the name used to open the OpenGL visual referenced from the file
       

Cons of using OpenGL on Linux

There is little documentation regarding how to tackle errors in.
