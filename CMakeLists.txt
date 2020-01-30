cmake_minimum_required(VERSION 3.9)
project(kip_sequential)

set(CMAKE_CXX_STANDARD 11)

add_executable(kip_sequential main.cpp image.cpp image.h ppm.cpp ppm.h utils.h kernels.h)