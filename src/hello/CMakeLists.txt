cmake_minimum_required(VERSION 2.8)
project(hello)
set(SOURCE_LIB hello.cpp)
add_library(hello STATIC ${SOURCE_LIB})