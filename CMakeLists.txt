cmake_minimum_required(VERSION 3.10)

project(SHRIMP-DETECTOR VERSION 1.0)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED True)

set(SOURCES 
    src/main.cpp
)

include_directories(${PROJECT_SOURCE_DIR}/include)

add_executable(shrimp-detector ${SOURCES})

target_compile_options(shrimp-detector PRIVATE)