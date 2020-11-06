cmake_minimum_required(VERSION 3.17) # common to every CLion project
project(firstOpenGlApp) # project name

set(CMAKE_CXX_STANDARD 20)

set(OpenGlLinkers -lglut -lGLU -lGL) # setting all the Glut libraries as one variable.

################################################

add_executable(firstOpenGlApp1 main.cpp ) #common to all clion project
target_link_libraries(firstOpenGlApp1 ${OpenGlLinkers}) # linking opengl libraries to the project

#################################################