cmake_minimum_required(VERSION 3.10)
project(SubmoduleProject)

# Create the submodule executable
add_library(submodule STATIC cmain.c)