cmake_minimum_required (VERSION 3.0)

project (my_best_app)

add_subdirectory(app_3)
add_subdirectory(app_1)
add_executable (my_best_app "main.cpp" "common.h")
