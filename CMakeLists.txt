cmake_minimum_required(VERSION 3.15)
project(oelf C)

set(CMAKE_C_STANDARD 11)

add_library(oelf SHARED oelf.c)