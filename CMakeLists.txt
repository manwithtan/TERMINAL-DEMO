cmake_minimum_required(VERSION 3.10)
project(CWH_Compiler)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(cwh_compiler main.cpp)

target_include_directories(cwh_compiler PRIVATE ${CMAKE_CURRENT_SOURCE_DIR})