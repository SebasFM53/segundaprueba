cmake_minimum_required(VERSION 3.24)
project(segundaprueba)

set(CMAKE_CXX_STANDARD 14)

include_directories(src, include)

add_executable(segundaprueba
        src/AAAAA.cpp
        include/AAAAA.h
        README.md src/Main.cpp)
