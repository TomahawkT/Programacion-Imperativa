INCLUDE(CMakeForceCompiler)
CMAKE_FORCE_C_COMPILER(gcc GNU)
CMAKE_FORCE_CXX_COMPILER(g++ GNU)
cmake_minimum_required(VERSION 3.20)
project(PI C)

set(CMAKE_C_STANDARD 99)

add_executable(PI main.c)
