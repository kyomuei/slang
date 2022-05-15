cmake_minimum_required(VERSION 3.21)

project(slang 
    VERSION 0.0.0.1
    DESCRIPTION "tiny swift language"
    LANGUAGES C
)

set(CMAKE_C_STANDARD 11 CACHE STRING "C standard to conform to")
set(CMAKE_C_STANDARD_REQUIRED YES)
set(CMAKE_C_EXTENSIONS NO)

set(SLANG_INCLUDE_DIR ${PROJECT_SOURCE_DIR}/Includes)

add_subdirectory(Sources)
