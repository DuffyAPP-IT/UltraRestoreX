cmake_minimum_required(VERSION 3.15)
project(src C)

set(CMAKE_C_STANDARD 99)

add_executable(src main.c prereq.c header.h ver.h installer.c ios.c ios.h)