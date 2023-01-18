cmake_minimum_required(VERSION 3.24)
project(2048v1)

set(CMAKE_CXX_STANDARD 17)

add_executable(2048v1 2048.cpp config.h.in )
