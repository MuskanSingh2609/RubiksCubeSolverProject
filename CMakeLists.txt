cmake_minimum_required(VERSION 3.26)
project(RubiksCubeSolverProject)

set(CMAKE_CXX_STANDARD 14)

add_executable(RubiksCubeSolverProject main.cpp
        Model/GenericRubiksCube.cpp
        Model/GenericRubiksCube.h
        Model/RubiksCube1dArray.cpp)
