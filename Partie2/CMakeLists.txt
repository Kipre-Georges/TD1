cmake_minimum_required(VERSION 3.10)
project(Partie2)

add_subdirectory(Tugabudoire)

add_executable(programme main.cpp
        Tugabudoire/Tugabudoire.cpp)


target_link_libraries(programme PRIVATE tugabudoire)