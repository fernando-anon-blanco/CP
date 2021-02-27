cmake_minimum_required(VERSION 3.17)
project(CP C)

set(CMAKE_C_STANDARD 11)

include_directories(p1)

add_executable(CP
        p1/bank.c
        p1/options.c
        p1/options.h)
