cmake_minimum_required(VERSION 3.3)
project(AHPP_lab4)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp)
add_executable(AHPP_lab4 ${SOURCE_FILES})