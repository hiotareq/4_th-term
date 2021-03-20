cmake_minimum_required(VERSION 3.17)
project(double_link_list_c C)

set(CMAKE_C_STANDARD 99)

add_executable(double_link_list_c main.c dl_list.cpp)