cmake_minimum_required(VERSION 3.5)
project(HelloWorld
        VERSION 0.1
        DESCRIPTION "Hello World"
        LANGUAGES CXX)  
add_executable(HelloWorldBinary main.cpp) 
target_compile_features(HelloWorldBinary PRIVATE cxx_std_20)