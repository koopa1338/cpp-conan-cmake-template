project(Projectname)
cmake_minimum_required(VERSION 3.17)
add_definitions("-std=c++17")
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

include(${CMAKE_BINARY_DIR}/conanbuildinfo.cmake)
conan_basic_setup()

add_subdirectory(src)
