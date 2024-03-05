cmake_minimum_required(VERSION 3.26)
project(Model)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Model
        GenericRubiksCube.cpp
        GenericRubiksCube.h
        RubiksCube1dArray.cpp
        RubiksCube3dArray.cpp)
