# CG4Games

Created by Eric Ameres for my Computer Graphics for Games Students May 2021
Simple OpenGL applpication for sandboxing Graphics Algorithms

I created this file as a framework for experimenting with shaders and testing primitive graphics algorithms within OpenGL

To work with pixel by pixel algorithms, a small texture is used that is written into directly, but then used as a texture

using IMGUI the program also allows for "hot swapping" the basic vertex and fragment shaders

building requires VS 2019 (likely works with earlier versions as well) and CMAKE

Find the build directory and run the setup batch file.  In the file that it creates you will find a VS2019 sln file you can launch
