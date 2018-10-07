cmake_minimum_required(VERSION 3.12)
project(laba2)

set(CMAKE_CXX_STANDARD 14)

include_directories(src)
include_directories(test)

add_executable(laba2
        src/HeaderCount.cpp
        src/HeaderCount.h
        src/main.cpp
        test/HeaderCountTest.cpp
        test/HeaderCountTest.h
        test/main.cpp)
