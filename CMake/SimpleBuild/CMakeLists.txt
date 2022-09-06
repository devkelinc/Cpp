cmake_minimum_required(VERSION 3.10)

project(simple)

add_executable(simple ${CMAKE_SOURCE_DIR}/SourceCode/simple.cpp)

# specify the C++ standard
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

install(TARGETS simple DESTINATION bin)
