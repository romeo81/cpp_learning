cmake_minimum_required(VERSION 3.6)

project(cpp_learning)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        source/main.cpp
        source/headers/sample.cpp
        source/headers/sample_class.cpp
        source/headers/inheritance_sample_class.cpp
    )

add_executable(cpp_learning ${SOURCE_FILES})

message(STATUS "Finished")