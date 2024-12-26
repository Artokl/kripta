cmake_minimum_required(VERSION 3.28)
project(kripta)

set(CMAKE_CXX_STANDARD 23)

add_executable(kripta main.cpp
        PackingBackpack.cpp
        PackingBackpack.h)
