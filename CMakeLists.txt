cmake_minimum_required(VERSION 3.16)
project(nbody)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std:c++latest")
set(CMAKE_CXX_STANDARD 11)
set(PYTHON_FILES nbody.py)
add_executable(nbody
        nbody.cpp)

