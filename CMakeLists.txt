cmake_minimum_required(VERSION 3.28)

project(test)

find_package(raylib CONFIG REQUIRED)

add_executable(main main.c)

target_link_libraries(main PRIVATE raylib)
