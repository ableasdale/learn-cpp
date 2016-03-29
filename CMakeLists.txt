cmake_minimum_required(VERSION 3.4)
project(learn_cpp)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    src/main/cpp/main.cpp)
    #src/test/cpp/testmain.cpp)

add_executable(learn_cpp ${SOURCE_FILES})