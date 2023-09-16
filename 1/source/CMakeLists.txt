cmake_minimum_required(VERSION 3.0.0)
project(FirstProject
        VERSION 0.0.1
        DESCRIPTION "This is my first CMake Project..."
        LANGUAGES CXX)
add_executable(FirstProjectBinary main.cpp)
target_compile_features(FirstProjectBinary PRIVATE cxx_std_17) 