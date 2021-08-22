cmake_minimum_required(VERSION 2.8)
project(dome CXX)
aux_source_directory(. DIR_SRC)
add_executable(demo ${DIR_SRC})