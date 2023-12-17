cmake_minimum_required(VERSION 3.12)
project(My_Lib)

add_subdirectory(src)
add_executable(main main.cpp)
target_link_libraries(main PUBLIC math)