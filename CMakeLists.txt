cmake_minimum_required(VERSION 3.0)

project(boost_geometry_dissolve)

FIND_PACKAGE( Boost 1.76 REQUIRED )
INCLUDE_DIRECTORIES( ${Boost_INCLUDE_DIR} )
ADD_EXECUTABLE(example example.cpp)
ADD_EXECUTABLE(test test.cpp)
ADD_EXECUTABLE(boost_test boost_test.cpp)
# ADD_EXECUTABLE(break_sym break_sym.cpp)
