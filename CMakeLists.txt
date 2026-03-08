cmake_minimum_required(VERSION 4.0)
project(rational)

set(CMAKE_CXX_STANDARD 20)

add_executable(rational
        header.cpp
        rational.h
        main.cpp
)
