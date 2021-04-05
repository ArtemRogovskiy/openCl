cmake_minimum_required(VERSION 3.15)
project(openCl C)

set(CMAKE_C_STANDARD 99)

include_directories(/usr/include/CL/)

add_library(openCl library.c library.h main.c)