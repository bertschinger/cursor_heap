cmake_minimum_required(VERSION 3.5)

project(testlib)

##
### Source definitions ###
##

include_directories("${PROJECT_SOURCE_DIR}")

#file(GLOB sources "${PROJECT_SOURCE_DIR}/src/*.c")

#add_executable(testy ${sources})
add_library(cheaptest cheap_testlib.c random_buffer.c xrand.c )

