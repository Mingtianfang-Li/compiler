cmake_minimum_required(VERSION 3.22)
project(compiler)

set(CMAKE_CXX_STANDARD 17)

add_executable(compiler src/main.cpp
        src/tokenization.hpp)
