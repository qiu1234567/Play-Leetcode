cmake_minimum_required(VERSION 3.5)
project(cpp_0116)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main3.cpp)
add_executable(cpp_0116 ${SOURCE_FILES})