cmake_minimum_required(VERSION 3.8)
project(stdinredir2)

set(CMAKE_C_STANDARD 11)

set(SOURCE_FILES main.c)
add_executable(stdinredir2 ${SOURCE_FILES})