cmake_minimum_required(VERSION 2.8)
project(svmdigits)
find_package(OpenCV REQUIRED)
include_directories(${OpenCV_INCLUDE_DIRS})
add_executable(svmdigits main.cpp)
target_link_libraries(svmdigits ${OpenCV_LIBS})
