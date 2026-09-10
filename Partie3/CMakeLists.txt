cmake_minimum_required(VERSION 3.10)
project(Partie3)

add_executable(programme main.cpp Tugabudoire.cpp
        main.cpp)

include(FetchContent)

FetchContent_Declare(
        googletest
        URL https://github.com/google/googletest/releases/download/v1.18.0/googletest-1.18.0.tar.gz
        DOWNLOAD_EXTRACT_TIMESTAMP TRUE
)

FetchContent_MakeAvailable(googletest)
enable_testing()
add_subdirectory(tests)