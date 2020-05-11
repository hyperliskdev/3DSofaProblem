cmake_minimum_required(VERSION 3.16)
project(3dSofaProblem)

set(CMAKE_CXX_STANDARD 14)

add_executable(3dSofaProblem main.cpp main.h)

target_link_libraries(3dSofaProblem -lglut -lGL -lGLU)