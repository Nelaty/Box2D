cmake_minimum_required(VERSION 3.8)

project(box2d)

set(box2d_include "${CMAKE_SOURCE_DIR}/include/")

set(CMAKE_ARCHIVE_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/lib)
set(CMAKE_LIBRARY_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/lib)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)

include_directories("${box2d_include}")

add_subdirectory(src)
