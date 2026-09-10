add_library(tugabudoire STATIC Tugabudoire.cpp)


target_include_directories(tugabudoire PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})

target_compile_features(tugabudoire PUBLIC cxx_std_14)