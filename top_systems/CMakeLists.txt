cmake_minimum_required(VERSION 3.5.0)
project(
    shapes 
    LANGUAGES CXX
    VERSION 1.0.0)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(shapes shapes.cpp)