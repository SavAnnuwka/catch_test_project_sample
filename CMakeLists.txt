cmake_minimum_required(VERSION 3.13)
project(catch_test_project_sample)

set(CMAKE_CXX_STANDARD 14)
include_directories(lib)
add_executable(catch_test_project_sample test_failed.cpp test_passed.cpp)