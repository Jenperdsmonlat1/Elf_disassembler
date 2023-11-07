cmake_minimum_required(VERSION 3.26)

project(ElfAnalyzer C)
set(CMAKE_C_STANDARD 99)

include_directories(include)
add_executable(
    src/main.c
)
