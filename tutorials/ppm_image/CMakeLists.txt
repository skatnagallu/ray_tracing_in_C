cmake_minimum_required(VERSION 3.10)
project(PPMImage)

# Set C++ standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Create an executable from main.cc
add_executable(ppm_image main.cc)