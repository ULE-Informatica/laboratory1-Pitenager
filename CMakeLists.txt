cmake_minimum_required(VERSION 3.10)

# set the project name
project(exampleStrings)

# add the executable
add_executable(exampleStrings exampleStrings_def.c)

# just for example add some compiler flags
target_compile_options(exampleStrings PUBLIC -std=c11 -Wall -pedantic --verbose)