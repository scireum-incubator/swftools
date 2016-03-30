cmake_minimum_required(VERSION 3.3)
project(swftools)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES src/pdf2swf.c)
add_executable(pdf2swf ${SOURCE_FILES})